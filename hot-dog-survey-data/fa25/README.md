# Hot Dog Survey Data

This data was collected through a Google Form that was distributed by members of the DS 4002 class to UVA undergraduate students.
The raw data is contained in the fa25 folder [here](https://github.com/evelynmaxwell/DS-4002-EM/blob/e28f50899ea8c597c03020353b31adfac08b9352/hot-dog-survey-data/fa25/Is%20hotdog%20a%20sandwich_%20(Responses).xlsx).
The cleaned data was converted to csv format and is contained in the fa25 folder [here](https://github.com/evelynmaxwell/DS-4002-EM/blob/fba8a69058e6f2e503cfb5361381a50cdea96169/hot-dog-survey-data/fa25/Cleaned%20Hotdog%20Data.csv).

---

### Data Dictionary:

| Column Name | Type        | Description |
|-------------|-------------|-------------|
| `Year`        | Integer     | Integer (1-4) indicating the year of the student|
| `Raw Response`        | String     | String ("Yes" or "No") indicating the student's response to the question "Is a hot dog a sandwich?"|
| `Converted Response`      | Integer      | Integer (1 or 0) indicating the student's response to the question "Is a hot dog a sandwich?". 1 = Yes 0 = No |
