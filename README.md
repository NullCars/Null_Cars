# Null_Cars
## Overview

**Null_Cars** is a web application designed to simplify the process of renting vehicles.
 The platform allows users to create accounts, browse available cars, make reservations, and manage their bookings with ease.
 The admin panel provides comprehensive control over vehicle management, locations, and user interactions.


## Features

### User Features
- **User Authentication**: Sign up and log in to manage reservations.
- **Reservation System**: Browse available cars and make reservations for specific dates and locations.
- **Account Management**: Users can view and manage their reservations.

### Admin Panel Features
- **Car Management**: Add, edit, or remove car brands and models.
- **Location Management**: Manage rental locations, including adding and editing details.
- **Contact Form Management**: View and respond to messages submitted through the contact form.
- **Reservation Management**: View all reservations made by users and cancel bookings if necessary.

## Technologies Used
- **Bootstrap:** For styling and layout.
- **React:** For building user interfaces.
- **Redux:** For managing application state.
- **Firebase:** For authentication, database, and hosting.
- **Nodemailer:** For email notifications

## Purpose

The purpose of this project is to provide a seamless and userfriendly platform for vehicle rentals, allowing users to easily
book cars online and manage their bookings. The admin panel
gives administrators full control over the platform's content and
user interactions.



## Setup and Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/NullCars/Null_Cars.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Null_Cars
    ```
3. Install dependencies:
    ```bash
    npm install 
   
        or
   
       npm i 
    ```
4. Create a `.env` file in the root directory and add the following environment variables:
    ```plaintext
    REACT_APP_FIREBASE_API_KEY=AIzaSyANTOlDO1G0wuZZQx8-hcaPFvHVkoSq71k
    REACT_APP_FIREBASE_AUTH_DOMAIN=null-cars.firebaseapp.com
    REACT_APP_FIREBASE_PROJECT_ID=null-cars
    REACT_APP_FIREBASE_STORAGE_BUCKET=null-cars.appspot.com
    REACT_APP_FIREBASE_MESSAGING_SENDER_ID=439051282793
    REACT_APP_FIREBASE_APP_ID=1:439051282793:web:387e5f1b49b3f0220575f8
    REACT_APP_FIREBASE_MEASUREMENT_ID=G-38R23EK5QB
    
    REACT_APP_RECAPTCHA_SITE_KEY=6LfS-WYpAAAAACNhWYiooRcnwxuNn1jy7In0I7-F
    REACT_APP_RECAPTCHA_TEST_SITE_KEY=6LeIxAcTAAAAAJcZVRqyHh71UMIEGNQ_MXjiZKhI
    ```








