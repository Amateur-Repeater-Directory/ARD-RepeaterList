# Repeater Data  
**Free • Verified • Community-Maintained**

This repository contains the open, community-maintained master list of amateur radio repeaters for the Amateur Repeater Directory (ARD).  
Our mission is to build the most accurate, transparent, and freely available repeater database in the United States — created by hams, for hams.

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
  "repeaterId": "abcd-1234-efgh-5678",
  "callsign": "W1ABC",
  "outputFrequency": 146.940,
  "inputFrequency": 146.340,
  "offset": "-0.6",
  "toneMode": "CTCSS",
  "ctcssTx": 123.0,
  "ctcssRx": 123.0,
  "latitude": 42.3601,
  "longitude": -71.0589,
  "elevation": 234,
  "state": "MA",
  "county": "Suffolk",
  "nearestCity": "Boston",
  "notes": "Linked to W2XYZ network",
  "isOperational": true,
  "isOpen": true
}
