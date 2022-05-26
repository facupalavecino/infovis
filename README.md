# infovis

As part of the Data Visualization course - ECD - ITBA - 2022

# Description

There are 2 notebooks:

`main`: This notebook iterates over the ParticipantStatusLog files, extracts records from certain moments of the day
from each of them, concatenates the results and saves it in a new CSV file.

`analysis`: This notebook reads the CSV file previously generated to perform the analysis.

# Running the notebooks

If you have Poetry installed:

`poetry install`

If you don't ahve Poetry installed:

Generate a `requirements.txt` file with these dependencies:

```
numpy = "^1.22.4"
pandas = "^1.4.2"
matplotlib = "^3.5.2"
geopandas = "^0.10.2"
jupyter = "^1.0.0"
ipykernel = "^6.13.0"
```
