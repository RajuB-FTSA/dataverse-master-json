# dataverse-master-json

# Dataverse Master Configuration

This repository stores a centralized JSON configuration file (`MasterConfig.json`) used by a plugin in Microsoft Dataverse.

## Purpose
The JSON file provides real-time configuration values such as feature flags, thresholds, or limits that are read dynamically by a plugin triggered inside Dataverse.

## Structure
The `MasterConfig.json` file is structured like this:
```json
"Category": "P-led",
    "Parent category": "FastTrack Portfolio Engagement (15pts)",
    "Question": "Does the CoE  Proactively engage with FT regularly on Architeture and product guidance?",
    "ResponseType": "Qualitative Choice",
    "Max Score": 5,
    "Actual Score": "",
    "options": {
      "A+": 5.0,
      "A": 4.0,
      "B": 3.0,
      "C": 2.0,
      "D": 1.0,
      "E": 0.0
    }
