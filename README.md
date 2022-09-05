# :biking_man: Bike Sharing :biking_woman: :bicyclist:

## 1. Overview of the statistical analysis:

### 
**The purpose of this analysis is to see if bike sharing trends in NYC can translate into creating a successful bike sharing business in Des Moines.  Investors would like to see various visualizations as part of a sales pitch, such as the duration of the rides, what time of day people ride, whether riders are Subscribers or Customers, and the number of bike trips taken at each hour of each day of the week.  This presentation will also present other variables pertaining to localizing/marketing such a product into Des Moines.**


## 2. Results:

### Visualizations for the NYC Citibike analysis

#### 1. Checkout Times For Users
- Trips are typically between 1 to 25 minutes long with a mode of 5 minutes.  Most users are  not traveling beyond an hour in length.

![1_Checkout_Times_For_Users](https://github.com/Super-Manda/bikesharing/blob/main/Resources/1%20Checkout%20Times%20for%20Users.png)


#### 2. Checkout Times for Users by Gender
- Males are most apt to check out Citi Bikes, but the average trip duration with the bike is stable across genders.

![2_Checkout_Times_for_Users_by_Gender](https://github.com/Super-Manda/bikesharing/blob/main/Resources/2%20Checkout%20Times%20for%20Users%20by%20Gender.png)


#### 3. Trips by Weekday For Each Hour
- This is a heat map illustrating that the rush hours are the most popular time to ride.  This would be weekdays from 7-9 AM with a mode of 8 AM, and from 5-7 PM in the weekday evenings with a mode of 6 PM.  
- The most popular day is Thursday.  
- There is more activity on Saturday than Sunday.  The weekend biking is centered around the midday rather than the rush hours.

![3_Trips_by_Weekday_For_Each_Hour](https://github.com/Super-Manda/bikesharing/blob/main/Resources/3%20Trips%20by%20Weekday%20For%20Each%20Hour.png)


#### 4. Trips by Gender Weekday per Hour
- Males take a lot of bike rides, especially at the rush hour.  
- Females also ride at rush hour, but take fewer trips than males do.  
- The unknowns tend to ride at the midday on the weekends.

![4_Trips_by_Gender_Weekday_per_Hour](https://github.com/Super-Manda/bikesharing/blob/main/Resources/4%20Trips%20by%20Gender%20(Weekday%20per%20Hour).png)


#### 5. User Trips by Gender by Weekday
- Subscribers tend to check out bikes most often on weekdays, whereas Customers tend to check out bikes most often on weekends.  
- The least popular day for subscribers is Sunday and the most popular is Thursday.  
- The unknowns tend to be Customers who ride on weekends.  
- In general, Customers ride mostly on weekends.  
- Overall, Wednesday appears to suffer low ridership in both groups (Customers and Subscribers).

![5_User_Trips_by_Gender_by_Weekday](https://github.com/Super-Manda/bikesharing/blob/main/Resources/5%20User%20Trips%20by%20Gender%20by%20Weekday.png)


#### 6. Top Starting Locations
- Does NYC Relate to Des Moines?  In NYC, there is tourism in Manhattan, so bike rotation would be a good idea if Customers tend to pick up the bikes from Times Square and then leave them somewhere else.  On this map below, the 14,571 corresponds to approximately Times Square.  Des Moines is not as dense as NYC, so rotating the bikes may be a little easier to predict if tourists have to travel farther and if there is no subway there for riders to take their bike on.  It is unknown if workers would subscribe to ride to work the way they might in NYC, but Des Moines has similar square-like streets to Manhattan.  These are very different locations, but Des Moines would have a smaller bike fleet to be concerned about, which may make it more manageable.

![8_Top_Starting_Locations](https://github.com/Super-Manda/bikesharing/blob/main/Resources/8%20Top%20starting%20locations.png)


#### 7. Highest to Lowest Ridership Times
- The optimal time to repair the bikes and rotate the fleet without impacting users would be when ridership is lowest, around 3-4 AM.

![9_Highest_To_Lowest_Ridership_Times](https://github.com/Super-Manda/bikesharing/blob/main/Resources/9%20Highest%20to%20Lowest%20Ridership.png)




## 3. Summary:

### High-level summary of the results 

![Dashboard1_Module](https://github.com/Super-Manda/bikesharing/blob/main/Resources/NYC%20Citi%20Bike%20Dashboard%20from%20Module.png)

![Dashboard2_Challenge](https://github.com/Super-Manda/bikesharing/blob/main/Resources/NYC%20Citi%20Bike%20Dashboard2%20from%20Challenge.png)

- Thus far, the analysis has been lacking the specifics of the age demographics of the NYC riders, so these are presented below.  The age demographics will likely influence whether someone is a Subscriber or a Customer and the time of day/ day of the week when they may frequently ride.  It would be important for Des Moines to adjust their bike sharing program to the market needs if their age demographics are older or younger than NYC's demographics. 

### Two additional visualizations for future analysis:
#### 1. Sum of Trip Duration by Generation and Gender
- There is an unknown group of 1960s Baby Boomers who spend a lot of time biking.  
- Younger people, born in the 1980s and 1990s, are the most avid bikers.  
- Generation Z appears to not know how to ride a bike anymore, and/or has no interest in biking, given that the people born in the 1950s are more avid bikers than they are, despite being around 70 years old.  Perhaps Generation Z does know how to ride bikes, but they're still in college or not yet fully in the workforce (although at least half of them should be by now).
- Men tend to out-bike women at all ages.
![6_Trip_Duration_by_Generation_and_Gender](https://github.com/Super-Manda/bikesharing/blob/main/Resources/6%20Trip%20Duration%20by%20Generation%20and%20Gender.png)


#### 2. Trip Duration by Generation and UserType
- Customers only need a day pass, whereas subscribers need an annual pass.  
- In this case, the annual subscribers are the younger people, for the most part.  
- Those born in the 1960s are more apt to be customers, suggesting that they may not need to bike every day.  Some may be retired.
![7_Trip_Duration_by_Generation_and_UserType](https://github.com/Super-Manda/bikesharing/blob/main/Resources/7%20Trip%20Duration%20by%20Generation%20and%20UserType.png)
