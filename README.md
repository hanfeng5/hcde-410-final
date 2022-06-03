# hcde-410-final

## Project Overview:
This project is to create the analysis of modern electric vehicle models and offer suggestions to the cosutmers who wants to buy electric vehicles. The goal is to create conclusions in regards different electric car options, based on the price affordability and performance specifications, and encourage more people to purchase electric vehicles for the sake of environmental friendly. Additionally, the goal of this project is to examine the benefits and drawbacks of electric vehicles compared to normal gasoline vehicles, in terms of cost difference between owning a gasoline vehicle and an eletric vehicle, from both the purchase price and fuel economy aspects, and attempt to investigate if owning an electric vehicle will be cheaper and cost effective compare to owning a gasoline vehicle. Finally, to provide some references about which electric vehicle to get based on the needs. 

## Source Data In Analysis: 
- [Cheapest Electric Cars](https://www.kaggle.com/datasets/kkhandekar/cheapest-electric-cars). It records most of the popular electric vehicle models, along with their performance specifications and other statistical data, that will offer great analysis to each vehicle models.
    - **License:** This dataset uses the [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/) license, meaning that the author who collected these data give the rights to the public domain to copy, modify, and perform the work.
- [FuelEconomy.gov Web Services](https://www.fueleconomy.gov/feg/ws/index.shtml#fuelType1).Records the fuel economy of common vehicles available in the market. Selected the subset database that records all 2022 vehicles. The corresponding API documentation is here: [API documentation from fueleconomy.gov](https://www.fueleconomy.gov/feg/ws/index.shtml#ft7)
    - **License:** This data is directly downloaded from the fueleconomy.gov website as they have published the csv and json database. They did not specify the license for these data.
- [Car Prices Dataset](https://www.kaggle.com/datasets/sidharth178/car-prices-dataset?resource=download). Records the price of common popular vehicles
    - **License:** It does NOT have a licnese or the origin of the data contents. It seems to be composed by a data scientist who have done similar works in the past, but they did not release where they have got the data from. Unfortuntely, other better dataset require payment or the scope is only targeting "used cars", which is not plausible for this project.
    
## Python Libraries:
Most of the data collection were performed in Python. Therefore, I have imported different Python Libraries to support the analysis process.
- [Pandas Library](https://pandas.pydata.org/docs/): A library that helps to create data visualization and organize data.
- [csv](https://docs.python.org/3/library/csv.html): Help to red .csv files, which is the format that most of the database files are in
- [matplotlib](https://matplotlib.org): A plotting library within python that helps to create the charts and other data visualizations with given data
- [numpy](https://numpy.org): A numbering library within python that allows user to perform mathmetical operations

## Other Resources:
- [welch t-test calculator](https://www.statskingdom.com/150MeanT2uneq.html). This is to calculate the statistical significance between two dataset and obtain the p value to justify the difference between two dataset. 
- [US Department of Energy](https://afdc.energy.gov/fuels/electricity_charging_home.html). the price is 0.107 kWH based on the typical American electricity price.
- [Rocket HQ](https://www.rockethq.com/learn/personal-finances/how-much-does-it-cost-you-to-fill-up) a normal vehicle tank ranges from 12-16 gallon.
- [Electric vehicles get mixed reception from American consumers](https://www.pewresearch.org/fact-tank/2021/06/03/electric-vehicles-get-mixed-reception-from-american-consumers/). Motivation of doing this project. The reserach surved 13,749 US adults, with inclusion of 912 Gen Z adults born after 1996. Then, they have found out that 39% of adults says that they will likely purchase an electric vehicle and 46% says that they will not purchase one. 14% of the participants do not plan to buy a vehicle in the future.
- [Can an electric car really help you save money as gas prices soar? What experts say](https://www.miamiherald.com/news/nation-world/national/article259430229.html). Motivation of doing this project. This article has performed some basic comparision between the cost of EV vehicles and gasoline vehicles.

For a detailed propsoal, please visit the file [Final Plan + Project Report](https://jupyter.rttl.uw.edu/2022-spring-hcde-410-a/hub/user-redirect/lab/tree/hcde-410-final/Final%20Plan%20%2B%20Project%20Report.ipynb).