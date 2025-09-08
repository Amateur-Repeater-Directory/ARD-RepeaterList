# Repeater Data (We need your help)
**Free • Verified • Community-Maintained**

<img src="https://github.com/user-attachments/assets/b677c6cf-5a66-459f-bd1f-95d3ee820921"
     width="160" height="160"
     alt="ARD Logo"
     style="float:left; margin:0 1em 1em 0;" />
<h3>Free, Verified, Community-Maintained</h3>

This repository contains the open, community-maintained master list of amateur radio repeaters for the Amateur Repeater Directory (ARD).  Our mission is to build the most accurate, transparent, and freely available repeater database in the United States — created by hams, for hams.

## State Progress
We’re tracking progress toward completing all 50 states. A checkmark means that state’s data has been entered and verified.

| State           | Status | State           | Status | State           | Status |
|-----------------|--------|-----------------|--------|-----------------|--------|
| Alabama         | ☐      | Kentucky        | ☐      | North Dakota    | ☐      |
| Alaska          | ☐      | Louisiana       | ☑      | Ohio            | ☐      |
| Arizona         | ☐      | Maine           | ☑      | Oklahoma        | ☐      |
| Arkansas        | ☐      | Maryland        | ☐      | Oregon          | ☐      |
| California      | ☑      | Massachusetts   | ☑      | Pennsylvania    | ☑      |
| Colorado        | ☑      | Michigan        | ☐      | Rhode Island    | ☑      |
| Connecticut     | ☑      | Minnesota       | ☑      | South Carolina  | ☐      |
| Delaware        | ☐      | Mississippi     | ☐      | South Dakota    | ☐      |
| Florida         | ☑      | Missouri        | ☐      | Tennessee       | ☐      |
| Georgia         | ☐      | Montana         | ☐      | Texas           | ☐      |
| Hawaii          | ☐      | Nebraska        | ☐      | Utah            | ☑      |
| Idaho           | ☑      | Nevada          | ☐      | Vermont         | ☑      |
| Illinois        | ☐      | New Hampshire   | ☑      | Virginia        | ☐      |
| Indiana         | ☑      | New Jersey      | ☑      | Washington      | ☑      |
| Iowa            | ☐      | New Mexico      | ☑      | West Virginia   | ☑      |
| Kansas          | ☐      | New York        | ☑      | Wisconsin       | ☐      |

☑ = Completed  ☐ = Not yet complete

## How You Can Help
We’re working toward **all 50 states** — and we need your help to get there.  
If your state isn’t listed as complete above, you will soon be able to add repeaters through either:  
- Bulk data submissions (both JSON and CSV formats will be published soon)  
- The ARD web interface for adding or editing individual repeaters  

### Important Data Policy
T**You must not** copy repeater information from these proprietary sources:  
1. RepeaterBook  
2. Artsci Publishing  

Contributors should use publicly available information, direct coordination with repeater owners, and their own verified data.

## Data Format Example
Each repeater entry follows this JSON structure:

```json
  {
    "repeaterId": "fc802c7a-656d-404a-98e6-20801edf5610",
    "transientId": 0,
    "outputFrequency": 442.750000,
    "inputFrequency": 447.750000,
    "offset": 5.000,
    "offsetSign": "+",
    "band": "70cm",
    "elevation": 34.000,
    "aboveGroundLevel": 60.960,
    "toneMode": "TSQL",
    "ctcssTx": 0.00,
    "ctcssRx": 103.50,
    "isCrossTone": false,
    "callsign": "N1FL",
    "latitude": 28.6700000000,
    "longitude": -81.3500000000,
    "state": "Florida",
    "county": "Seminole",
    "nearestCity": "Altamonte Springs",
    "isLatLongPrecise": false,
    "isOperational": true,
    "isOpen": true,
    "isCoordinated": true,
    "ares": false,
    "races": false,
    "skywarn": false,
    "createdDate": "2025-08-16T19:47:46.8748557",
    "updatedDate": "2025-08-16T19:47:46.8748557",
    "hasLatLongError": false
  }
```
