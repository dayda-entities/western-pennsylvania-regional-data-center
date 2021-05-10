---
title: Allegheny County 911 Dispatches - EMS and Fire
created: '2020-11-30T02:49:54.700398'
modified: '2020-11-30T02:49:54.700405'
state: active
type: dataset
tags:
  - '911'
  - _etl
  - Cad
  - Dispatch
  - Emergency
  - Emergency Services
  - Ems
  - Fire
  - Medical
groups:
  - Local Government
csv_url: >-
  https://data.wprdc.org/dataset/abba9671-a026-4270-9c83-003a1414d628/resource/7a9b3eea-3b3a-4dc4-aae0-02b864fa6f41/download/cad_priority_codes.csv
json_url: ''
layout: post

---
The Allegheny County 911 center answers and dispatches 911 calls for 111 out of 130 municipalities in Allegheny County. Agencies are dispatched via a computer aided dispatch (CAD) system. This dataset contains dispatched EMS and Fire events from the CAD and includes details about the nature of the emergency.

To protect the privacy of callers and prevent sensitive health or other identifying information being revealed, the following steps were taken:
  
* Aggregated event location to census block groups.  
* Aggregated call date/time to quarter and year. 
* Shortened call types to remove potentially identifying information. 
* Flagged certain call types as containing sensitive health information, such as mental health issues, overdose, etc.  
* Checked frequency of calls with sensitive health information: 
    * If the number of calls (in a particular category related to sensitive health information) for a certain quarter/year and census block group was greater than or equal to 5, the call description was included.  
    * If less than 5, the call description was redacted. 

Events requiring EMS and Fire services will appear in both datasets with a different Call ID. Events requiring two agencies of the same service (e.g. two or more different fire companies responded to a major fire) will only list the primary responder.

The call descriptions are based on information provided by the caller. The calls are not later updated with a disposition or correction if the original description was inaccurate. For example, if EMS is dispatched to the scene of a stroke, but the person actually had a heart attack, that record would not be updated later with the correct description. 

A small subset of the CAD data had no call type recorded. These records are preserved with a "null" in the Description_Short field. Redacted call types are listed as "Removed".

The 19 municipalities that dispatch their own EMS, Fire, and/or Police services are called "ringdown municipalities". These are subject to change. The list can be found in the Ringdown Municipalities 2019 resource.
