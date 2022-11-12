# Bike Sharing Assignment
>A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.




## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
- The company wants to analyse
  * Which variables influence demand for the bike booking
  * What is the realtion of  variables on bike booking demand
- What is the dataset that is being used?
  * day.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.21.6
- pandas - version 1.3.5
- matplotlib - version 3.1.2
- seaborn - version 0.12.0
- sklearn - version 0.0
- statsmodels - version 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions
- We have finalised a model with R2 score of 0.79.
- The influencing Factors in the final Model with coefficients are 
    * const              0.2036 
    * year(yr)           0.2338 
    * temperature(temp)  0.4923
    * windspeed          -0.1498     
    * mnth_Jul           -0.0486     
    * mnth_Sep            0.0721      
    * weekday_Sun        -0.0451    
    * weathersit_Mist    -0.0816    
    * weathersit_Snow    -0.2856     
    * season_spring      -0.0680     
    * season_summer       0.0467      
    * season_winter       0.0831  

- We have found the top 3 influencing factors on bike booking are 
    *	Temperature -temp(0.4923), If temperature increases by 1 unit then bike demand increases bike demand by 0.4923  units
    *	Weather Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds -weathersit_snow(-0.2856)- If Weather Snow increases by 1 unit then bike demand decreases bike demand by 0.2856 units
    *	Year - yr(0.2338) If year increases by 1 unit then bike demand increases bike demand by 0.2338 units



## Acknowledgements
Give credit here.
- This project was inspired by Upgrad tutorial on MultiLinearRegression
- This project was based on [Upgrad tutorial](https://learn.upgrad.com/course/4431?courseId=26360).


## Contact
Created by [@shruthiannappa] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->