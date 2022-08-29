# Data-Pipelining

# Mobile Price Classification 
This project represents the sales data of mobile phones from various competitor brands.
In this dataset, we are going to estimate price of mobiles for a new company by considering competitive mobile phone market 
Data visualization has been carried to find out some relation between features of a mobile phone(eg:- RAM,Internal Memory etc) and its selling price.
Dataset as 21 features and 2000 entries. The meanings of the features are given below*<br>

battery_power: Total energy a battery can store in one time measured in mAh

blue: Has bluetooth or not

clock_speed: speed at which microprocessor executes instructions

dual_sim: Has dual sim support or not

fc: Front Camera mega pixels

four_g: Has 4G or not

int_memory: Internal Memory in Gigabytes

m_dep: Mobile Depth in cm

mobile_wt: Weight of mobile phone

n_cores: Number of cores of processor

pc: Primary Camera mega pixels

px_height: Pixel Resolution Height

px_width: Pixel Resolution Width

ram: Random Access Memory in Mega Bytes

sc_h: Screen Height of mobile in cm

sc_w: Screen Width of mobile in cm

talk_time: longest time that a single battery charge will last when you are

three_g: Has 3G or not

touch_screen: Has touch screen or not

wifi: Has wifi or not

price_range: This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).

# New York City Taxi Fare Prediction
We are predicting the fare amount (inclusive of tolls) for a taxi ride in New York City given the pickup and dropoff locations.<br>
While you can get a basic estimate based on just the distance between the two points, this will result in an RMSE of 8, depending on the model used (see the starter code for an example of this approach in Kernels)<br>
the aim is to predict the fare of a taxi ride given the starting time, the starting and ending latitude / longitude, and the number of passengers.<br>
Let’s look at the features of this data :*<br>

key - the key represents the pickup date and time in local time (NYC)

fare_amount - a USD value to two decimal places representing the cost of the trip, tolls included

pickup_datetime - the pickup date and time for the specific trip in UTC format

pickup_longitude - the pickup longitude position, presumably from an on-board GPS

pickup_latitude - the pickup latitude position

dropoff_longitude - the dropoff longitude position

dropoff_latitude - the dropoff latitude position

passenger_count - an integer value representing the number of passengers in the taxi 
