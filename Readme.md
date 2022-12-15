# How to use Hyper API to extract data from Tableau TWBX and load it in Pandas Dataframe

<img src="https://raw.githubusercontent.com/simboli/Extract-data-from-Tableau-TWBX/main/00.Media/Grumpy.png" alt="Grumpy" width="400px"/>

## List of workbooks
001. [Unpackaging of Tableau TWBX file](https://github.com/simboli/Extract-data-from-Tableau-TWBX/blob/main/001.Unpackaging%20of%20Tableau%20TWBX%20file.ipynb)
002. [Extracting data from Tableau extract to Pandas dataframe with Tableau Hyper API](https://github.com/simboli/Extract-data-from-Tableau-TWBX/blob/main/002.Extracting%20data%20from%20Tableau%20extract%20to%20Pandas%20dataframe%20with%20Tableau%20Hyper%20API.ipynb)

## Credits
For this example, I have used the "Salaries by College type in USA" dashboard of O. Agbolabori. You can see and download it from [this page on the Tableau Public gallery](https://public.tableau.com/app/profile/oluwadunsin.agbolabori/viz/SalariesbyCollegetypeinUSAEduvizzers/Dashboard1).

## Packages
In this workbook I have used the following modules:
- shutil
- pathlib
- pandas
- tableauhyperapi ([download page](https://www.tableau.com/support/releases/hyper-api/0.0.16123))
- zipfile
- os

I strongly suggest using a virtual environment and installing packages from the requirements file
```
pip install -r requirements.txt
```

