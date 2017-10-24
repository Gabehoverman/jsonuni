# Json List of Higher Education Institutions.
Comprehensive Json file of Higher Education Universities sorted by the state in which they are located.

### A University has the following details


University Attribute | Details
---------------------|--------------
Title | Name of University
Established | YYYY-MM-DD format
Location | City Name, State name
Colors | Colors of University
Nickname | Nickname of University

### Example University

Example University | Details
-------------------| -------
Title | University of Michigan
Established | 1817-08-26
Location | Ann Arbor, Michigan
Colors | Maize and Blue
Nickname | Wolverines

### Example University File

```json 
{
    "Title": "University of Michigan",
    "Established": "1817-08-26",
    "Colors": [
        "Maize", 
        "Blue"
    ],
    "Nickname": "Wolverines"
}

