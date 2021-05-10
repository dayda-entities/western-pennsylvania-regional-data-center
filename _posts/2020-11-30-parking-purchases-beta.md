---
title: Parking Purchases (Beta)
created: '2020-11-30T02:50:55.563806'
modified: '2020-11-30T02:50:55.563818'
state: active
type: dataset
tags:
  - Parking
groups:
  - Local Government
csv_url: >-
  https://data.wprdc.org/dataset/e87ccf87-90f6-4023-ba4e-5a2f58793a72/resource/4d5bf8ce-5f4b-493c-a9c9-03bc491bfe00/download/purchases-data-dictionary-w-examples.csv
json_url: ''
layout: post

---
This dataset contains transaction-level records of purchases of parking from the Pittsburgh Parking Authority.

Individual transactions are published with information including the zone or meter where the purchase was made, start time of the interval paid for, end time of the interval paid for,  purchase time (for meter transactions), date recorded in the database (a good proxy for purchase time for mobile transactions), amount paid in that transaction, whether the transaction was made through a smart phone (a "mobile" transaction) or at a meter (in which case the means of payment will be identified as cash, credit card, or a combination of the two), and whether a given purchase started a new parking session or extended an existing session.

The payment-interval start times are the same for all transactions in a given session: If someone pays to park at 9am and then 15 minutes later adds more money to extend their parking session, there will be two rows in the table (one for the 9am purchase and one for the 9:15am purchase), but both rows will have the same payment-interval start time (9am) since the payment interval is at the parking-session level.

This dataset is considered "beta" at this point. The formatting of values and the set of fields may change as this dataset approaches its final state.
