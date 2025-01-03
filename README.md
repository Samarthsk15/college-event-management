
# Event Registration System

This is a web-based Event Registration System that allows users to register for various events hosted by an organization or institution. The system features a user-friendly interface to capture participant details and validate the input, including the following essential fields:

- Full Name
- Email
- Mobile Number
- College and Branch
- Event Category
- Event Type
- UTR Number (for payment confirmation)

The system ensures the accuracy of participant information with robust input validation using regular expressions. It prevents duplicate registrations by checking if the participant's email is already registered for the same event.

## Features:
- **Responsive Design**: Mobile-friendly design for ease of use on any device.
- **Input Validation**: Ensures that users provide valid information (e.g., email, mobile number, UTR number).
- **Event Management**: Allows participants to choose from multiple event categories and types, such as technical events, gaming fests, and seminars.
- **Payment Verification**: Includes an option to upload a UTR number to confirm payment for registration.

## Technologies Used:
- **Frontend**: HTML, CSS, JavaScript (Bootstrap)
- **Backend**: PHP (MySQL for database storage)
- **Database**: MySQL (for participant data and event details)

## How It Works:
1. The user fills out the registration form with necessary details.
2. The system validates the input and checks if the email is already registered for the selected event.
3. Upon successful validation, the data is stored in the database, and a confirmation message is displayed.
4. If there are any errors, appropriate messages are shown for the user to correct their input.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/event-registration-system.git
