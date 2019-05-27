## Florida Panther Roadkill Cleaning Log
### Filter cause of death by: Vehicle

```[
  {
    "op": "core/row-star",
    "description": "Star rows",
    "engineConfig": {
      "facets": [
        {
          "type": "list",
          "name": "CAUSE",
          "expression": "value",
          "columnName": "CAUSE",
          "invert": false,
          "selection": [
            {
              "v": {
                "v": "Disease or Other??",
                "l": "Disease or Other??"
              }
            },
            {
              "v": {
                "v": "Unknown",
                "l": "Unknown"
              }
            },
            {
              "v": {
                "v": "Disease",
                "l": "Disease"
              }
            },
            {
              "v": {
                "v": "Pseudorabies",
                "l": "Pseudorabies"
              }
            },
            {
              "v": {
                "v": "ISA",
                "l": "ISA"
              }
            },
            {
              "v": {
                "v": "Other",
                "l": "Other"
              }
            }
          ],
          "selectNumber": false,
          "selectDateTime": false,
          "selectBoolean": false,
          "omitBlank": false,
          "selectBlank": false,
          "omitError": false,
          "selectError": false
        }
      ],
      "mode": "record-based"
    },
    "starred": true
  },
  {
    "op": "core/row-removal",
    "description": "Remove rows",
    "engineConfig": {
      "facets": [
        {
          "type": "list",
          "name": "CAUSE",
          "expression": "value",
          "columnName": "CAUSE",
          "invert": false,
          "selection": [
            {
              "v": {
                "v": "Disease or Other??",
                "l": "Disease or Other??"
              }
            },
            {
              "v": {
                "v": "Unknown",
                "l": "Unknown"
              }
            },
            {
              "v": {
                "v": "Disease",
                "l": "Disease"
              }
            },
            {
              "v": {
                "v": "Pseudorabies",
                "l": "Pseudorabies"
              }
            },
            {
              "v": {
                "v": "ISA",
                "l": "ISA"
              }
            },
            {
              "v": {
                "v": "Other",
                "l": "Other"
              }
            }
          ],
          "selectNumber": false,
          "selectDateTime": false,
          "selectBoolean": false,
          "omitBlank": false,
          "selectBlank": false,
          "omitError": false,
          "selectError": false
        }
      ],
      "mode": "record-based"
    }
  }
]
