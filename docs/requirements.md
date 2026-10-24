# 3.0 Requirements

## 3.1 Functional Requirements

| No. | Functional Requirement |
| --- | --- |
| FR1 | The system shall extract visible vehicle registration plate numbers from camera footage. |
| FR2 | The system shall flag a possible obstruction when a tracked vehicle remains within a predefined access zone behind occupied parking bays for more than 60 seconds. |
| FR3 | The system shall allow students to confirm their detected parking location. |
| FR4 | The system shall allow students to correct their detected parking location by selecting a location on the car park map. |
| FR5 | The system shall match recognised plate numbers to associated student accounts using authorised vehicle-registration records. |
| FR6 | The system shall notify the associated student when a possible obstruction is detected behind their parked car. |
| FR7 | The system shall allow a blocked student to submit a relocation request to the account associated with the identified blocking vehicle. |
| FR8 | The system shall allow the recipient of a relocation request to send an acknowledgement to the requesting student. |
| FR9 | The system shall inform the requesting student when no registered account can be matched to the identified blocking vehicle. |


## 3.2 Non-Functional Requirements

| No. | Type | Non-Functional Requirement |
| --- | --- | --- |
| NFR1 | Performance | The system shall display at least 95% of relocation notifications within 10 seconds of request submission during a test of 100 requests with both devices online and notifications enabled. |
| NFR2 | Privacy | The system shall prevent student users from viewing other students’ phone numbers, student identification numbers and email addresses through its screens or API responses. |
| NFR3 | Usability | The system shall enable at least 9 out of 10 first-time student test users to submit a relocation request within 60 seconds, starting from the obstruction alert screen, without assistance. |
| NFR4 | Reliability | The system shall preserve every acknowledged relocation request and its status after a service restart in a test involving 100 saved requests. |
