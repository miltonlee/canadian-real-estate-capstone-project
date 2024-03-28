# Canadian Real Estate Market Trends

## Project Overview 🏠

This data analysis focuses on the housing markets of Calgary and Edmonton aiming to identify some key factors that may have a potential influence on the assessed value of residential properties. Additionally, we will be examining the evolving popularity of dwelling types in Calgary over the years. Through this analysis, we aim to build a greater understanding of Calgary's housing market to assist homebuyers and investors in making informed decisions.

## Datasets Used 📈

* [Total Property Assessed Value - Calgary](https://data.calgary.ca/Government/Total-Property-Assessed-Value/dmd8-bmxh)

* [Property Assessment Data - Edmonton](https://data.edmonton.ca/City-Administration/Property-Assessment-Data-Historical-/qi6a-xuwt/about_data)

* [Annual Resident Count by Dwelling Type - Calgary](https://data.calgary.ca/Demographics/Annual-Resident-Count-by-Dwelling-Type/kji3-kmu4)

## Process ⏩
1. Formulated a set of business questions we were interested in analyzing
2. Identified datasets that aligned with our business questions and export it to a CSV file
3. Import datasets into Jupyter Notebook along with the Pandas library and SQL to examine the raw data, carefully evaluating each column variable to assess its suitability for our models
4. Removed irrelevant columns and values such as nulls 
5. Addressed outliers
6. Made visualizations using PowerBi

## Results 📊
### What are some key factors influencing the housing market trends in Calgary and Edmonton, and how do they impact buying and investing opportunities in these cities?

**Year Built**
![Year_Built](https://github.com/miltonlee/canadian-real-estate-capstone-project/assets/41603809/d15fac10-02ef-41c4-80aa-407ee560cf76)


* Housing prices are constantly fluctuating. Some years are higher, and some years are lower. 
* Calgary Vs Edmonton: Fluctuations change more drastically in Calgary. Edmonton shows fluctuations, but changes are less obvious. 
* There is no definitive trend with the year built and the assessed value.

**Lot Size**
![Land_Size](https://github.com/miltonlee/canadian-real-estate-capstone-project/assets/41603809/5ef03910-9315-4865-bd6e-cef7447c8dc9)
![Neighbourhood](https://github.com/miltonlee/canadian-real-estate-capstone-project/assets/41603809/4708dc9c-4950-4d9b-b327-d6dc54be29d9)

*Lot sizes categorized into arbitrary values of small ( 0 –50,000 m/sq), medium ( 50,001 – 100,000 m/sq), and large (100,001 – greater m/sq) using the standard deviation*

* Calgary: 
  * If the lot size is very large, then the assessed value can be considerable large. 
  * Small lots can be larger in value than medium lot sizes. 
  * Calgary isn’t entirely dictated by the lot size. Also consider looking at neighborhoods 

* Edmonton:
  * The lot size is consistent with and has an effect on the assessed value
  * There is a upward trend in the assessed values to the relative lot size. 
  * It was possible but not exclusively to get higher returns based off lot size. 

### What are the projected future trends in the types of dwellings in Calgary, and how might these trends impact buying and investing decisions in the real estate market?

![dwelling_type_CGY](https://github.com/miltonlee/canadian-real-estate-capstone-project/assets/41603809/948792ae-c72e-4165-84af-ab19d8f92213)
![dwelling_count_CGY](https://github.com/miltonlee/canadian-real-estate-capstone-project/assets/41603809/d13bd444-fa41-4e8e-a22e-816d827637b1)

* Increase in the number of single detached and apartment dwellings could indicate a growing preference for these types of properties among homebuyer

* The data doesn’t provide a large enough scope to determine whether single detached homes and apartments are necessarily preferred or if there are other factors that are also affecting this trend such as more single detached homes and apartments being built more than any other dwelling

* A high occupancy rate suggests a strong demand for housing, indicating a potentially competitive market and potentially driving property values upward. On the other hand, a high vacancy rate may indicate an oversupply of certain types of dwellings, which could lead to increased competition among sellers and potentially affect property prices negatively


## Recommendations 🔎

* For investing:  
  * In **Edmonton**: Then a key factor that could yield a decent  amount of returns could be the lot size.
  * In **Calgary**: Lot size is a key factor for larger ones. When deciding to invest in medium and large lots. Calgary relies on two possible factors including neighborhood and lot size to potentially make a decent judgement 
  * Year built would not be a good determining factor when understanding if an investment in a house is worth it or not in either Calgary or Edmonton
  * Different areas and neighborhoods can attract varying levels of demand based on factors such as affordability, dwelling types, amenities, transportation options, schools, and proximity to the downtown core

* **Investors looking to invest in a rental property**: Monitoring occupancy and vacancy rates and tracking the trends in popular dwelling types is also important, as a higher occupancy rate can be used as an indication there may be a strong demand for potential rental opportunities

## Technical Challenges

* Large datasets

  * Calgary dataset (3.9 M)
  * Edmonton dataset (8.4M)

* Hardware/Software issues

  * Difficulties loading and reading data on Excel/Power BI
  * Slow lag times, crashes due to the dataset size

* Unidentifiable columns

* Finding datasets with similar columns and column values when working with a comparable

* Python errors, finding the right code to run to remove outliers, categorizing, finding standard deviation, working with the for loops, merging two tables, plot legend not showing.

* Amalgamating different datasets and workbooks into one PBIX file

## Contributors 🤝

* **Kristyn Ho** [![Linkedin](https://i.stack.imgur.com/gVE0j.png)](https://www.linkedin.com/in/kristyn-ho/) &nbsp;[![GitHub](https://i.stack.imgur.com/tskMh.png)](https://github.com/Alex-Kris)

* **Milton Lee** [![Linkedin](https://i.stack.imgur.com/gVE0j.png)](https://www.linkedin.com/in/miltonlee1/) &nbsp;[![GitHub](https://i.stack.imgur.com/tskMh.png)](https://github.com/miltonlee)
