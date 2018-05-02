# Cars and Services Database C++
## Project description
The purpose of this program is to create, edit and handle a database of cars and the services done on them. The code is implemented in **Object Oriented Programming language C++**. It consists of two classes named Car and Service for creating objects to be handled by the file handling functions. 
* The Car data is consisted of the car model, plate number and year. The Service data is consisted of its description, time between two services in months, the last date when the service was done, and the next service date calculated inside the class using the last date as reference. Service class incorporates a static function that displays the current system date and time. 
* The program offers the option to create or edit a file named “CarsAndServices.txt” in which all the data for cars and services will be added line by line sequentially. There is a interactive menu in the program that shows 5 options for the user to choose from. 
  1. Option 1 is to store a car's model followed by its service, if the plate number already exists the car is not added.
  2. Option 2 is to store a service to be done on a car, if the plate number is not in the file the car is not added.
  3. Option 3 is to perform a search on the file for a specific car by its plate number and list all its service records to be done, if car is not found the program returns an error message.
  4. Option 4 is to display all cars to be serviced on a specified date, if date is not found the program will return an error message.
  5. Option 5 exits the program. 
* The code contains file error handling and overloads the operator “<<” in the Car and Service classes.
