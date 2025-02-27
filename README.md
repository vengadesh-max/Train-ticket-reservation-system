# Railway-Reservation-System

### Project Description
The Railway Reservation System is a Python-based application allowing users to book and cancel train tickets via a command-line interface. It leverages Object-Oriented Programming (OOP) principles, supports different compartment classes, tracks seat availability, handles payments, and generates booking codes.

### Key Features
##### Booking Tickets: 
Users can book tickets by selecting a compartment and completing the payment process.
##### Canceling Tickets: 
Users can cancel their bookings using a unique coupon code and receive a refund based on their ticket status.
##### Data Persistence: 
Booking details are stored in a CSV file, allowing for easy management and retrieval of booking information.
##### Seat Management: 
The system tracks the availability of seats across different compartment classes.
##### Refund Calculation: 
Automatically calculates refunds based on ticket status (confirmed or waiting list).

### Technologies Used
##### Python : Main programming language for application logic.
##### CSV Module: For data storage and management of booking details.
##### Object-Oriented Programming (OOP): To ensure a modular design and separation of concerns.

### How to Use
Clone the Repository:

bash
Copy code
### git clone [https://github.com/vengadesh-max/Railway-Reservation-System.git](https://github.com/vengadesh-max/Railway-Reservation-System.git)
### cd railway-reservation-system
Run the Application:

bash
Copy code
### python railway_reservation.py
Follow the prompts:

Enter passenger details (first name, last name, age, gender).
Choose to book or cancel a ticket.
If booking, select a compartment and proceed with payment.
If canceling, enter the coupon code associated with your booking.
Output:

Upon booking a ticket, details will be saved in bookings.csv.
Note
When a ticket is booked, all relevant booking details, including the passenger's information, compartment choice, and payment method, will be recorded in an Excel-like format in the bookings.csv file.

## 🚀 Setup Instructions
![Screenshot (1296)](![Screenshot (1466)](https://github.com/user-attachments/assets/ff407266-185f-46b3-b31b-8a4f7aa1d305)
)


License
This project is licensed under the MIT License - see the LICENSE file for details.



