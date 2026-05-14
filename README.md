# SoftwareDesingAssignment
Code revesion assignment

This project is a simple Java-based campus food ordering system developed for the Software Design Patterns homework.

The main purpose of the project is to demonstrate how Factory Pattern and Singleton Pattern can improve software design and code organization.

In the system, students can place food orders and receive different types of notifications such as:

 Email notification
SMS notification
 Push notification

The project was refactored from an initial poorly designed version into a cleaner and more maintainable structure.


Factory Pattern is used to create notification objects.

Instead of creating objects directly inside the main service class, the system uses NotificationFactory to generate the correct notification type.

This makes the code:

 cleaner
 easier to maintain
 easier to extend



Singleton Pattern is used for the AppConfig class.
This class stores shared system information such as:

 university name
 delivery fee
 system version
Only one AppConfig object exists during the application lifecycle.

How to Compile the Project
Open terminal inside project folder and run:
javac *.java

How to Run the Project
After compiling, run:
java CampusFoodOrderService

Order created for: Ali
Food: Chicken Sandwich
Delivery fee: 25.0 TL
Sending EMAIL notification...

Order created for: Zeynep
Food: Vegetarian Pizza
Delivery fee: 25.0 TL
Sending SMS notification...

Order created for: Omar
Food: Coffee
Delivery fee: 25.0 TL
Sending PUSH notification...






