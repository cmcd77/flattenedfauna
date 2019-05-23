# Cleaning Log

### Dataset: USARoadkillDataGarneau_2012-2015.csv
#### Original Download: http://epicollectserver.appspot.com/project.html?name=RoadkillGarneau



Removed observations with no latitude or longitude

Left observations with no species name because there are associated pictures that can be used for identification

Replaced empty Date cells with value in corresponding 'Date Created' column

Replaced all empty cells of String format with 'Null'

Replaced all empty cells of Numeric format with '-9999'

Changed Data format to YYYY-MM-DD

Converted all values in 'Temperature' variable to Fahrenheit

Removed Sting characters in 'Temperature' variable

Escaped all special characters

Normalized State, County, Town, and Habitat in OpenRefine.

OpenRefine JSON:

```[
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "michigan",
          "Michigan",
          "MICHIGAN",
          "Michigan "
        ],
        "to": "MI"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "New York",
          "New york",
          "New York ",
          "new york"
        ],
        "to": "NY"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Pa",
          "PA",
          "pa",
          "PA "
        ],
        "to": "PA"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "NY",
          "Ny",
          "ny"
        ],
        "to": "NY"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "NC",
          "nc",
          "Nc"
        ],
        "to": "NC"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MA",
          "Ma"
        ],
        "to": "MA"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MI",
          "mi"
        ],
        "to": "MI"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "CO",
          "co"
        ],
        "to": "CO"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Pennsylvania",
          "Pennsylvanis"
        ],
        "to": "PA"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Florida"
        ],
        "to": "FL"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Fl"
        ],
        "to": "FL"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Georgia"
        ],
        "to": "GA"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Massachusetts"
        ],
        "to": "MA"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "minnesota"
        ],
        "to": "MN"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Montana"
        ],
        "to": "MT"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Nevada"
        ],
        "to": "NV"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "New Hampshire"
        ],
        "to": "NH"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "New Yorl"
        ],
        "to": "NY"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Oklahoma"
        ],
        "to": "OK"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Vermont"
        ],
        "to": "VT"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Texas"
        ],
        "to": "TX"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Vt"
        ],
        "to": "VT"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column State",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "State",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Nh"
        ],
        "to": "NH"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column County",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "County",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Clinton",
          "Clinton ",
          "clinton"
        ],
        "to": "Clinton"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Gratiot",
          "gratiot",
          "GRATIOT"
        ],
        "to": "Gratiot"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Cumberland",
          "Cumberland ",
          "cumberland"
        ],
        "to": "Cumberland"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Montgomery",
          "Montgomery "
        ],
        "to": "Montgomery"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Bucks",
          "bucks"
        ],
        "to": "Bucks"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "baraga",
          "baraga (?)"
        ],
        "to": "Baraga"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Saint lawrence",
          "Saint Lawrence"
        ],
        "to": "Saint lawrence"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "St lawrence",
          "St. Lawrence"
        ],
        "to": "Saint Lawrence"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Grand Isle",
          "Grand isle"
        ],
        "to": "Grand Isle"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "orange",
          "Orange"
        ],
        "to": "Orange"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column County",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "County",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Schoharie",
          "schoharie"
        ],
        "to": "Schoharie"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column County",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "County",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Saint lawrence",
          "Saint Lawrence"
        ],
        "to": "Saint Lawrence"
      }
    ]
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column County using expression value.toTitlecase()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "County",
    "expression": "value.toTitlecase()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column County",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "County",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Montgomery County"
        ],
        "to": "Montgomery"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column County",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "County",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Null"
        ],
        "to": "NULL"
      }
    ]
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Town using expression value.toTitlecase()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Town",
    "expression": "value.toTitlecase()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Town",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Town",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Peru",
          "Peru ",
          "Peru??"
        ],
        "to": "Peru"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Dannemora",
          "Dannemora "
        ],
        "to": "Dannemora"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Plattsburgh",
          "Plattsburgh "
        ],
        "to": "Plattsburgh"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Gainesville",
          "Gainesville "
        ],
        "to": "Gainesville"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Chazy",
          "Chazy "
        ],
        "to": "Chazy"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Saranac",
          "Saranac "
        ],
        "to": "Saranac"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Beekmantown",
          "Beekmantown "
        ],
        "to": "Beekmantown"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Town",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Town",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Rennselear Falls",
          "Rensselear Falls"
        ],
        "to": "Rennselear Falls"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Rensselear Falls",
          "Renssalear Falls"
        ],
        "to": "Rensselear Falls"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Beekmantown",
          "Beekmamtown"
        ],
        "to": "Beekmantown"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Plattsburgh",
          "Platsburgh"
        ],
        "to": "Plattsburgh"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Town",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Town",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Rensselear Falls",
          "Rennselear Falls"
        ],
        "to": "Rensselear Falls"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Town",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Town",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Rensselaer Falls",
          "Rensellaer Falls"
        ],
        "to": "Rensselaer Falls"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Town",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Town",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Rensselaer Falls",
          "Rensselear Falls"
        ],
        "to": "Rensselaer Falls"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Town",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Town",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Schuyler Falls",
          "Schulyer Falls"
        ],
        "to": "Schuyler Falls"
      }
    ]
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column SpeciesName using expression value.toTitlecase()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "SpeciesName",
    "expression": "value.toTitlecase()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column SpeciesName",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "SpeciesName",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Mallard",
          "Mallard "
        ],
        "to": "Mallard"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Skunk",
          "Skunk "
        ],
        "to": "Skunk"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Peromyscus Spp.",
          "Peromyscus Spp"
        ],
        "to": "Peromyscus Spp."
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Oppossum",
          "Oppossum "
        ],
        "to": "Oppossum"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Porcupine",
          "Porcupine "
        ],
        "to": "Porcupine"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Gray Squirrel",
          "Gray Squirrel "
        ],
        "to": "Gray Squirrel"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Whitetail Deer",
          "White-tail Deer"
        ],
        "to": "White-tail Deer"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Grey Squirrel",
          "Grey Squirrel "
        ],
        "to": "Gray Squirrel"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Opossum",
          "Opossum "
        ],
        "to": "Opossum"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Raccoon",
          "Raccoon "
        ],
        "to": "Raccoon"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Opposum ",
          "Opposum"
        ],
        "to": "Opposum "
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column SpeciesName",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "SpeciesName",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Opossum",
          "Possum",
          "Oppossum"
        ],
        "to": "Opossum"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "White Tail Deer",
          "White-tail Deer"
        ],
        "to": "White-tail Deer"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "White Tailed Deer",
          "White-tailed Deer"
        ],
        "to": "White-tailed Deer"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Cottontail Rabbit",
          "Cotton Tail Rabbit"
        ],
        "to": "Cottontail Rabbit"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Eastern Cottontail",
          "Eastern Cottontails"
        ],
        "to": "Eastern Cottontail"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Eastern Cottontail",
          "Eaatern Cottontail"
        ],
        "to": "Eastern Cottontail"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Nine-banded Armadillo",
          "Nine Banded Armadillo"
        ],
        "to": "Nine-banded Armadillo"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column SpeciesName",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "SpeciesName",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Unknown",
          "Unknown P"
        ],
        "to": "Unknown"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column SpeciesName",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "SpeciesName",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Racoon",
          "Racooon"
        ],
        "to": "Racoon"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column SpeciesName",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "SpeciesName",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Nine-banded Armadillo",
          "Nine Banded Armadillo's "
        ],
        "to": "Nine-banded Armadillo"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Opossum",
          "Opposum "
        ],
        "to": "Opossum"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Eastern Cottontail",
          "Eastern Cottontail Rabbit"
        ],
        "to": "Eastern Cottontail"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,Residential",
          "MaintainedGrass,MaintainedGrass,MaintainedGrass,Residential",
          ",MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,Residential",
          "MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,Residential",
          "MaintainedGrass,MaintainedGrass,Residential"
        ],
        "to": "MaintainedGrass,MaintainedGrass,Residential"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Agriculture,Agriculture,Agriculture,Residential",
          "Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Residential",
          "Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Residential",
          "Agriculture,Agriculture,Agriculture,Agriculture,Residential",
          "Agriculture,Agriculture,Residential"
        ],
        "to": "Agriculture,Agriculture,Residential"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Agriculture,Agriculture,Agriculture,DeciduousForest",
          "Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,DeciduousForest",
          "Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,DeciduousForest",
          "Agriculture,Agriculture,Agriculture,Agriculture,DeciduousForest"
        ],
        "to": "Agriculture,Agriculture,Agriculture,DeciduousForest"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Agriculture,Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,Agriculture,DeciduousForest,Residential",
          "Agriculture,Agriculture,Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,Agriculture,Agriculture,DeciduousForest,Residential",
          "Agriculture,Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,Agriculture,DeciduousForest,Residential",
          "Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,DeciduousForest,Residential"
        ],
        "to": "Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,DeciduousForest,Residential"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Agriculture,Meadow",
          "Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Meadow",
          "Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Meadow"
        ],
        "to": "Agriculture,Meadow"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,Urban",
          "MaintainedGrass,MaintainedGrass,MaintainedGrass,Urban",
          "MaintainedGrass,MaintainedGrass,Urban"
        ],
        "to": "MaintainedGrass,MaintainedGrass,Urban"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          ",Residential,Residential,Urban",
          "Residential,Residential,Residential,Residential,Residential,Residential,Residential,Residential,Urban",
          "Residential,Residential,Residential,Residential,Urban"
        ],
        "to": ",Residential,Residential,Urban"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Meadow,Meadow,Meadow,Residential",
          "Meadow,Meadow,Meadow,Meadow,Residential",
          "Meadow,Meadow,Residential"
        ],
        "to": "Meadow,Meadow,Residential"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Meadow,Meadow,Meadow,Meadow,Meadow,Meadow,Meadow,MixedForest",
          "Meadow,Meadow,Meadow,MixedForest"
        ],
        "to": "Meadow,Meadow,Meadow,MixedForest"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MixedForest,MixedForest,MixedForest,MaintainedGrass",
          "MixedForest,MixedForest,MixedForest,MixedForest,MixedForest,MaintainedGrass"
        ],
        "to": "MixedForest,MixedForest,MixedForest,MaintainedGrass"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MixedForest",
          "MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MixedForest"
        ],
        "to": "MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MixedForest"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,MixedForest",
          "Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,MixedForest"
        ],
        "to": "Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,MixedForest"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Urban,Urban,Urban",
          "Urban,Urban,Urban,Urban,Urban,Urban,Urban,Urban,Urban,Urban,Urban,Urban,Urban,Urban,Urban"
        ],
        "to": "Urban,Urban,Urban"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Agriculture,Agriculture,Agriculture,Agriculture,Agriculture",
          "Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture"
        ],
        "to": "Agriculture,Agriculture,Agriculture,Agriculture,Agriculture"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,MixedForest,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,MixedForest,Residential",
          "Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,MixedForest,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,MixedForest,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,MixedForest,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,MixedForest,Residential"
        ],
        "to": "Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,MixedForest,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,MixedForest,Residential"
      },
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          ",MaintainedGrass,MaintainedGrass,Pond",
          "MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,Pond"
        ],
        "to": ",MaintainedGrass,MaintainedGrass,Pond"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Agriculture,Agriculture,Agriculture,Agriculture,Agriculture"
        ],
        "to": "Agriculture"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Shrubland"
        ],
        "to": "Agriculture,Shrubland"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,MixedForest,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,MixedForest,Residential"
        ],
        "to": "MixedForest,Residential"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Agriculture,Lake"
        ],
        "to": "Agriculture,Lake"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          ",MaintainedGrass,MaintainedGrass,Pond"
        ],
        "to": "MaintainedGrass,Pond"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          ",Residential,Residential,Urban"
        ],
        "to": "Residential,Urban"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          ",RiverStream,RiverStream,Residential"
        ],
        "to": "RiverStream,RiverStream,Residential"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Agriculture,Agriculture,Agriculture,DeciduousForest"
        ],
        "to": "Agriculture,DeciduousForest"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,DeciduousForest,Meadow"
        ],
        "to": "Agriculture,DeciduousForest,Meadow"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,DeciduousForest,Agriculture,Agriculture,DeciduousForest,Residential"
        ],
        "to": "Agriculture,DeciduousForest,Residential"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Agriculture,Agriculture,Residential"
        ],
        "to": "Agriculture,Residential"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Agriculture,Agriculture,Residential,Agriculture,Agriculture,Residential,Agriculture,Agriculture,Residential,Agriculture,Agriculture,Residential,Agriculture,Agriculture,Residential,Agriculture,Agriculture,Residential,Lake"
        ],
        "to": "Agriculture,Residential,Lake"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Bog,Bog,MaintainedGrass,Bog,Bog,MaintainedGrass,MixedForest"
        ],
        "to": "Bog,Bog,MaintainedGrass,Bog,Bog,MaintainedGrass,MixedForest"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "ConiferForest,ConiferForest,ConiferForest,ConiferForest,ConiferForest,Residential"
        ],
        "to": "ConiferForest,Residential"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "ConiferForest,MixedForest,ConiferForest,MixedForest,Residential"
        ],
        "to": "ConiferForest,MixedForest"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "DeciduousForest,DeciduousForest,DeciduousForest,DeciduousForest,Agriculture,DeciduousForest,DeciduousForest,DeciduousForest,DeciduousForest,Agriculture,Meadow"
        ],
        "to": "DeciduousForest,Agriculture,Meadow"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "DeciduousForest,DeciduousForest,DeciduousForest,DeciduousForest,Fen,Residential"
        ],
        "to": "DeciduousForest,Fen,Residential"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "DeciduousForest,DeciduousForest,DeciduousForest,DeciduousForest,Meadow"
        ],
        "to": "DeciduousForest,Meadow"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "DeciduousForest,DeciduousForest,Lake"
        ],
        "to": "DeciduousForest,Lake"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "DeciduousForest,DeciduousForest,MixedForest"
        ],
        "to": "DeciduousForest,MixedForest"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "DeciduousForest,RiverStream,Residential,Ditch"
        ],
        "to": "DeciduousForest,RiverStream,Residential,Ditch"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Ditch,Ditch,MixedForest,Ditch,Ditch,MixedForest,Pond,Ditch,Ditch,MixedForest,Ditch,Ditch,MixedForest,Pond,Residential"
        ],
        "to": "Ditch,MixedForest,Pond,Residential"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Ditch,Ditch,Ditch,MixedForest"
        ],
        "to": "Ditch,MixedForest"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Floodplain,Floodplain,Floodplain,MixedForest"
        ],
        "to": "Floodplain,MixedForest"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,Lake,MixedForest"
        ],
        "to": "Lake,MixedForest"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Lake,Lake,Lake,Lake,Lake,Meadow"
        ],
        "to": "Lake,Meadow"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Lake,Lake,Lake,Lake,Lake,RiverStream"
        ],
        "to": "Lake,RiverStream"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Lake,Lake,Lake,Meadow,Lake,Lake,Lake,Meadow,Lake,Lake,Lake,Meadow,Residential"
        ],
        "to": "Lake,Meadow,Residential"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Lake,Lake,MaintainedGrass"
        ],
        "to": "Lake,MaintainedGrass"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Lake,Lake,MixedForest,Lake,Lake,MixedForest,Lake,Lake,MixedForest,Lake,Lake,MixedForest,Lake,Lake,MixedForest,Lake,Lake,MixedForest,Residential"
        ],
        "to": "Lake,MixedForest,Residential"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MaintainedGrass,MaintainedGrass,Lake"
        ],
        "to": "MaintainedGrass,Lake"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MaintainedGrass,MixedForest"
        ],
        "to": "MaintainedGrass,MixedForest"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MaintainedGrass,MaintainedGrass,MaintainedGrass,Meadow,Pond"
        ],
        "to": "Meadow,Pond"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MaintainedGrass,MaintainedGrass,Residential"
        ],
        "to": "MaintainedGrass,Residential"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MaintainedGrass,MaintainedGrass,Urban"
        ],
        "to": "MaintainedGrass,Urban"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Marsh,Marsh,Marsh,Marsh,Lake"
        ],
        "to": "Marsh,Lake"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Marsh,Marsh,Marsh,Marsh,Marsh,Agriculture"
        ],
        "to": "Marsh,Agriculture"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,Marsh,MixedForest"
        ],
        "to": "Marsh,MixedForest"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Marsh,Marsh,Marsh,Residential,Marsh,Marsh,Marsh,Residential,RiverStream"
        ],
        "to": "Marsh,Residential,RiverStream"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Meadow,Meadow,Meadow,Meadow,Ditch"
        ],
        "to": "Meadow,Ditch"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Meadow,Meadow,Meadow,Meadow,Meadow,Meadow,Lake"
        ],
        "to": "Meadow,Lake"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Meadow,Meadow,Meadow,MixedForest"
        ],
        "to": "Meadow,MixedForest"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Meadow,Meadow,Meadow,Urban"
        ],
        "to": "Meadow,Urban"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Meadow,Meadow,Residential"
        ],
        "to": "Meadow,Residential"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Meadow,Meadow,Residential,Meadow,Meadow,Residential,Urban"
        ],
        "to": "Meadow,Residential,Urban"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MixedForest,MixedForest"
        ],
        "to": "MixedForest"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MixedForest,MixedForest,Meadow,Bog"
        ],
        "to": "MixedForest,Meadow,Bog"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MixedForest,MixedForest,MixedForest,MaintainedGrass"
        ],
        "to": "MixedForest,MaintainedGrass"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MixedForest,MixedForest,MixedForest,MixedForest,MixedForest,MixedForest,MixedForest,MixedForest,MixedForest,MixedForest,Lake,Residential"
        ],
        "to": "MixedForest,Lake,Residential"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MixedForest,MixedForest,MixedForest,MixedForest,MixedForest,NotListed"
        ],
        "to": "MixedForest,NotListed"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MixedForest,MixedForest,MixedForest,Residential,MixedForest,MixedForest,MixedForest,Residential,MixedForest,MixedForest,MixedForest,Residential,RiverStream"
        ],
        "to": "MixedForest,Residential,RiverStream"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "MixedForest,Residential,Ditch,MaintainedGrass"
        ],
        "to": "MixedForest,Residential,Ditch,MaintainedGrass"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "NotListed,NotListed,NotListed,NotListed,NotListed,NotListed,NotListed,NotListed,NotListed,NotListed,NotListed,Urban"
        ],
        "to": "NotListed,Urban"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Residential,Residential,MixedForest"
        ],
        "to": "Residential,MixedForest"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Residential,Residential,Residential,Meadow"
        ],
        "to": "Residential,Meadow"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Residential,Residential,Residential,Residential,MaintainedGrass"
        ],
        "to": "Residential,MaintainedGrass"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Residential,Residential,Residential,Residential,Residential,Residential,Residential,Residential,Residential,Residential,Pond"
        ],
        "to": "Residential,Pond"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Residential,Residential,River"
        ],
        "to": "Residential,River"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "RiverStream,RiverStream,MixedForest"
        ],
        "to": "RiverStream,MixedForest"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "RiverStream,RiverStream,Residential"
        ],
        "to": "RiverStream,Residential"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "RiverStream,RiverStream,RiverStream,RiverStream,DeciduousForest"
        ],
        "to": "RiverStream,DeciduousForest"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "RiverStream,RiverStream,RiverStream,RiverStream,RiverStream,RiverStream,RiverStream,RiverStream,RiverStream,RiverStream,RiverStream,RiverStream,RiverStream,RiverStream,RiverStream,RiverStream,RiverStream,RiverStream,RiverStream,RiverStream,Lake"
        ],
        "to": "RiverStream,Lake"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Urban,Urban,Urban,Urban,MaintainedGrass"
        ],
        "to": "Urban,MaintainedGrass"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Urban,Urban,Urban,Urban,Urban,Ditch,Urban,Urban,Urban,Urban,Urban,Ditch"
        ],
        "to": "Urban,Ditch"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Urban,Urban,Urban,Urban,Urban,Urban,Ditch"
        ],
        "to": "Urban,Ditch"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Urban,Urban,Urban,Urban,Meadow"
        ],
        "to": "Urban,Meadow"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Urban,Urban,Urban"
        ],
        "to": ",Urban"
      }
    ]
  },
  {
    "op": "core/mass-edit",
    "description": "Mass edit cells in column Habitat",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Habitat",
    "expression": "value",
    "edits": [
      {
        "fromBlank": false,
        "fromError": false,
        "from": [
          "Urban",
          ",Urban"
        ],
        "to": "Urban"
      }
    ]
  }
]```
