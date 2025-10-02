# Analyzing Crime in Los Angeles  Daten

![Los Angeles skyline](la_skyline.jpg)

This repository contains an analysis of crime data from the city of Los Angeles. The project aims to identify patterns in criminal behavior to help the Los Angeles Police Department (LAPD) allocate resources more effectively.

## The Data

The dataset used for this analysis is `crimes.csv`, which is a modified version of the original data publicly available from Los Angeles Open Data.

### Dataset Columns

| Column | Description |
|---|---|
| `'DR_NO'` | Division of Records Number: Official file number made up of a 2-digit year, area ID, and 5 digits. |
| `'Date Rptd'` | Date reported - MM/DD/YYYY. |
| `'DATE OCC'` | Date of occurrence - MM/DD/YYYY. |
| `'TIME OCC'` | In 24-hour military time. |
| `'AREA NAME'` | The 21 Geographic Areas or Patrol Divisions are also given a name designation that references a landmark or the surrounding community that it is responsible for. |
| `'Crm Cd Desc'` | Indicates the crime committed. |
| `'Vict Age'` | Victim's age in years. |
| `'Vict Sex'` | Victim's sex: `F`: Female, `M`: Male, `X`: Unknown. |
| `'Vict Descent'` | Victim's descent. |
| `'Weapon Desc'` | Description of the weapon used (if applicable). |
| `'Status Desc'` | Crime status. |
| `'LOCATION'` | Street address of the crime. |

## Getting Started

To run the analysis, you will need to have Python installed, along with the following libraries:

* pandas
* numpy
* matplotlib
* seaborn

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn
