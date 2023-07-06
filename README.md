**# Vehicle-parking-management-system
Code Description**

This code is an implementation of a vehicle parking management system using object-oriented programming concepts in C++. The program allows users to park vehicles such as cars, rickshaws, and buses and keeps track of the number of vehicles parked and the parking fee collected.
The code defines a base class called parking, which has data members for the name and ID of the vehicle owner. It also defines two virtual functions getdata() and putdata() for inputting and displaying the data, respectively. The parking class serves as the parent class for the Car, Riksha, and Bus classes, which represent different types of vehicles.
The Car, Riksha, and Bus classes inherit from the parking class and add specific data members for each type of vehicle, such as car number, car model, car color, etc. These classes also override the getdata() and putdata() functions to input and display the specific vehicle data.
In the main() function, the program presents a menu to the user to choose the type of vehicle they want to park. Based on the user's selection, it dynamically creates an object of the respective vehicle type using polymorphism. The user is then prompted to input the vehicle and owner details, and the data is displayed on the console.
The program keeps track of the number of vehicles parked using an array of pointers to the base class parking. Each time a vehicle is parked, a new object is created, and its address is stored in the array. The program also calculates the total amount collected as parking fees.
The program continues to prompt the user for vehicle parking until the user chooses to exit. Once the user exits the parking system, the total number of vehicles parked is displayed, and the program terminates.
