# Car-Data-Analysis
This project takes my data from the app Fuel Buddy and analyzes it to tell me my current gas mileage rates.

Services.csv - The output for all car services (oil changes, repairs, etc.) that occur as a result of mileage.
  Date - Date of service
  Odometer - miles on car at time of service. Many times this is an estimation.
  Services - a list of services done on the car. This may have multiple cells.
  Total Cost - cost of services.
  Service Center - Repair shop. If I repaired it, I will say MYSELF and whoever I bought the parts from
  Notes - any additional info. If the service was Repair, this was a non-regular service and there will be details here.
  
Expenses.csv - output for expenses with fixed time period (tag, etc.) that are not necessarily tied to mileage.
  Date - date of expense
  Odometer - miles at time of expense
  Expenses - list of expenses paid for.
  Total Cost - cost of expense
  Vendor 
  Notes

Fill-Ups.csv
  Date
  Odometer
  Quantity - Quantity of fuel in gallons
  Distance - distance traveled since last fill-up
  Total Cost - cost of fill-up in dollars
  Consumption - mpg
  Partial Tank - boolean, 0 if I filled the tank.
  Octane - fuel type
  Fuel Brand
  Filling Station
  Notes

Random Unused Code.csv - a 'dump' for all unused code that I do not want to throw away.

Financial Analysis.ipynb - My analysis of the finances of driving.
