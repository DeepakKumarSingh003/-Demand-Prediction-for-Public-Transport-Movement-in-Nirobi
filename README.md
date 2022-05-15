# Demand Prediction For Public Transport Movement.
## Indroduction
* Transport demand forecasting is the process of using predictive analysis of historical data to estimate and predict customers' future demand for Vehicle and tickets bookings. Forecasting helps the Transport business to make better-informed supply decisions that estimate the total vehicles required and revenue from Bookings for a future period of time. 
* Mobiticket is one of those transport and travel technology company that enables travellers with a built-in transport ticket reservation and payment system via mobile.
## Data Description
Nairobi Transport Data.csv (zipped) is the dataset of tickets purchased from Mobiticket for the 14 routes from “up country” into Nairobi between 17 October 2017 and 20 April 2018. This dataset includes the variables: ride_id, seat_number, payment_method, payment_receipt, travel_date, travel_time, travel_from, travel_to, car_type, max_capacity. Uber Movement traffic data can be accessed here. Data is available for Nairobi through June 2018. Uber Movement provided historic hourly travel time between any two points in Nairobi. Any tables that are extracted from the Uber Movement platform can be used in your model.
## Features description
* **ride_id**: unique ID of a vehicle on a specific route on a specific day and time.
* **seat_number**: seat assigned to ticket
* **payment_method**: method used by customer to purchase ticket from Mobiticket (cash or Mpesa)
* **payment_receipt**: unique id number for ticket purchased from Mobiticket
* **travel_date**: date of ride departure. (MM/DD/YYYY)
* **travel_time**: scheduled departure time of ride. Rides generally depart on time. (hh:mm)
* **travel_from**: town from which ride originated
* **travel_to**: destination of ride. All rides are to Nairobi.
* **car_type**: vehicle type (shuttle or bus)
* **max_capacity**: number of seats on the vehicle
## Steps Performed
* **1.Extracting Target Variable**
* **2.Feature Engineering & Data Preprocessing**
* **3.EDA with Visualization**
* **4.Feature Selection**
* **5.ML Models Used**
    * 1.Logistic Regresion.
    * 2.Decision Tree Classifier
    * 3.Random Foreset Classifier
    * 4.XGBoost Classifier
* **6.Models Evaluation**
# Evaluation Matrices used
  * R Squqre
  * Accuracy
## Conclusion
* We used diffent algorithms.Out of all Random forest Regression and XGB worked worked well after hyperparameter tuning.

