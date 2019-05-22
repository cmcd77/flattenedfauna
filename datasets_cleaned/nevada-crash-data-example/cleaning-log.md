# Cleaning Log

### Dataset: NVCrashData_2015-2017.csv
#### Original Download: http://data-ndot.opendata.arcgis.com/datasets/c02ff49455704f0fb64fa012ff2109d3_0



Removed trailing and leading spaces

Replaced all empty cells of String format with 'Null'

Replaced all empty cells of Numeric format with '-9999'

Changed Data format to YYYY-MM-DD

Escaped all special characters

OpenRefine JSON:

[
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Crash_Severity using expression value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Crash_Severity",
    "expression": "value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column X using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "X",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Crash_Time_Original using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Crash_Time_Original",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Date using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Date",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Crash_Date_Original using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Crash_Date_Original",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column County using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "County",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Crash_Severity using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Crash_Severity",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column OBJECTID using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "OBJECTID",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Y using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Y",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Injured using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Injured",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Fatalities using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Fatalities",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Weather using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Weather",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Secondary_Street using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Secondary_Street",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Dir using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Dir",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Distance using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Distance",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Primary_Street using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Primary_Street",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Crash_Time using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Crash_Time",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V1_Lane_Num using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V1_Lane_Num",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V1_Driver_Age using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V1_Driver_Age",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V1_Dir using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V1_Dir",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V1_Type using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V1_Type",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Total_Vehicles using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Total_Vehicles",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Crash_Type using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Crash_Type",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Injury_Type using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Injury_Type",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Property_Damage_Only using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Property_Damage_Only",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V2_Dir using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V2_Dir",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V2_Type using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V2_Type",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V1_All_Events using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V1_All_Events",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V1_Most_Harmful_Event using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V1_Most_Harmful_Event",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V1_Vehicle_Factors using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V1_Vehicle_Factors",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V1_Driver_Distracted using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V1_Driver_Distracted",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V1_Driver_Factors using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V1_Driver_Factors",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V1_Action using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V1_Action",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V2_All_Events using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V2_All_Events",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V2_Most_Harmful_Event using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V2_Most_Harmful_Event",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V2_Vehicle_Factors using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V2_Vehicle_Factors",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V2_Driver_Distracted using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V2_Driver_Distracted",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V2_Driver_Factors using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V2_Driver_Factors",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V2_Action using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V2_Action",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V2_Lane_Num using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V2_Lane_Num",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column V2_Driver_Age using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "V2_Driver_Age",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Pedalcyclist using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Pedalcyclist",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Accident_Rec_Num using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Accident_Rec_Num",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Agency using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Agency",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column HWY_Factors using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "HWY_Factors",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Lighting using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Lighting",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Factors_Roadway using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Factors_Roadway",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Nonmotorist_Factors using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Nonmotorist_Factors",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column First_Harmful_Event using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "First_Harmful_Event",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column GlobalID using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "GlobalID",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column CrashDateTimeUTC using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "CrashDateTimeUTC",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column AnimalType using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "AnimalType",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Motorcyclist using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Motorcyclist",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  },
  {
    "op": "core/text-transform",
    "description": "Text transform on cells in column Pedestrian using expression grel:value.trim()",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Pedestrian",
    "expression": "grel:value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10
  }
]
