# Covid-19 Analysis AWS | PostgreSQL | Python

### Basic Information

* **Model date**: December, 2021
* **Model Type**: [Star Schema](https://github.com/ZAM1997/Covid-19-Analysis-Postgresql/blob/main/Star%20Schema.png)
* **Model version**: 1.0
* **License**: MIT
* **Model implementation code**: [Covid_19_Analysis](Covid_19_Analysis.ipynb)

### Intended Use
* **Primary intended uses**: This model was developed as the Final Project for the Data Management Course at the George Washington University
* **Primary intended users**: Students, Professors, Professionals having a similar focus


### Data Files and Basic Information
* **Cases and Deaths** - Includes US State wise cases - Active Cases, Recovered Cases, Deaths, Confirmed Cases with Geographic attributes Longitutde and Latitude
* **Vaccines** - Includes US State wise vaccine - Manufacturer, Doses shipped, Doses Administered with Geographic attributes Longitutde and Latitude
* **People Vaccinated** - Includes US State wise people vaccinated - People Fully Vaccinated and Partially vaccinated with Geographic attributes Longitutde and Latitude
* **Testing** - Includes US State wise Testings - PCR and Antigens conducted, positives and negatives from both the tests, total test conducted which includes PCR and Antigen
* **US Population** - US State wise population

### Questions Answered
* **What are the Top 10 states with the highest gap in people getting vaccinated as per the doses supplied?**
* **What are the top 10 states with the most covid tests taken & which test is the more dominant among PCR and Antigen in them?**
* **How was the number of cases impacted during the holiday season (Christmas, 25th December 2020), and what was the impact on neighboring states of the most impacted state?**
* **How did Delta Variant (May 31, 2021) affect cases, vaccination, and testing?**

### Sofware Problems
* AWS can pose several server issues

### Plots in the model:
* **Bar Graph**
* **Stacked Bar Graph**

