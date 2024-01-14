# Hotel Management System

## Overview

Welcome to the frontend repository of the Hotel Management System. This React-based web application provides a user-friendly interface for managing hotel-related operations. Below, you'll find detailed information about the key components and functionalities of the frontend.

## Table of Contents

1. [Components](#components)
2. [Authentication](#authentication)
3. [Booking](#booking)
4. [Profile](#profile)
5. [Registration](#registration)
6. [Booking Form](#booking-form)
7. [Booking Success](#booking-success)
8. [Booking Summary](#booking-summary)
9. [Find Booking](#find-booking)
10. [Usage](#usage)
11. [Important Note](#important-note)

---

## 1. Components

### 1.1. Admin

- **Path:** `/src/components/Admin.js`
- **Description:** Admin panel displaying a welcome message.

### 1.2. AuthProvider

- **Path:** `/src/context/AuthProvider.js`
- **Description:** Context provider for handling user authentication.

### 1.3. Logout

- **Path:** `/src/components/Logout.js`
- **Description:** Component for handling user logout.

### 1.4. Profile

- **Path:** `/src/components/Profile.js`
- **Description:** User profile displaying booking information.

### 1.5. Registration

- **Path:** `/src/components/Registration.js`
- **Description:** User registration form.

### 1.6. BookingForm

- **Path:** `/src/components/booking/BookingForm.js`
- **Description:** Form for making room bookings.

### 1.7. BookingSuccess

- **Path:** `/src/components/booking/BookingSuccess.js`
- **Description:** Page displayed upon successful room booking.

### 1.8. BookingSummary

- **Path:** `/src/components/booking/BookingSummary.js`
- **Description:** Component for summarizing booking details.

### 1.9. BookingsTable

- **Path:** `/src/components/BookingsTable.js`
- **Description:** Table displaying a list of bookings.

### 1.10. Checkout

- **Path:** `/src/components/Checkout.js`
- **Description:** Component for handling the checkout process.

### 1.11. FindBooking

- **Path:** `/src/components/FindBooking.js`
- **Description:** Component for finding and canceling a booking.

---

## 2. Authentication

### 2.1. AuthContext and AuthProvider

- **Path:** `/src/context/AuthProvider.js`
- **Description:** Context provider for handling user authentication.
- **Functionality:** Provides methods for user login and logout.

### 2.2. Login and Logout Components

- **Paths:** `/src/components/Login.js`, `/src/components/Logout.js`
- **Description:** Components for user login and logout.
- **Functionality:** Utilize the `useAuth` hook for authentication-related actions.

---

## 3. Booking

### 3.1. BookingForm

- **Path:** `/src/components/booking/BookingForm.js`
- **Description:** Form component for making room bookings.
- **Functionality:** Validates guest count and check-out date, then sends booking request.

### 3.2. BookingSuccess

- **Path:** `/src/components/booking/BookingSuccess.js`
- **Description:** Page displayed upon successful room booking.
- **Functionality:** Shows booking details and a link to the user profile.

### 3.3. BookingSummary

- **Path:** `/src/components/booking/BookingSummary.js`
- **Description:** Component for summarizing booking details.
- **Functionality:** Displays booking and payment information.

### 3.4. BookingsTable

- **Path:** `/src/components/BookingsTable.js`
- **Description:** Table displaying a list of bookings.
- **Functionality:** Fetches and displays booking data.

### 3.5. Checkout

- **Path:** `/src/components/Checkout.js`
- **Description:** Component for handling the checkout process.
- **Functionality:** Initiates the checkout process for completed bookings.

### 3.6. FindBooking

- **Path:** `/src/components/FindBooking.js`
- **Description:** Component for finding and canceling a booking.
- **Functionality:** Searches for a booking by confirmation code and cancels it.

---

## 4. Profile

### 4.1. Profile

- **Path:** `/src/components/Profile.js`
- **Description:** User profile displaying booking information.
- **Functionality:** Fetches and displays user-specific booking data.

---

## 5. Registration

### 5.1. Registration

- **Path:** `/src/components/Registration.js`
- **Description:** User registration form.
- **Functionality:** Registers a new user account.

---

## 6. Usage

1. **Clone Repository:**
   - Clone this repository to your local machine.

2. **Install Dependencies:**
   - Navigate to the project directory and run `npm install` to install dependencies.

3. **Start

 Development Server:**
   - Run `npm start` to start the development server.

4. **Access the Application:**
   - Open your browser and go to [http://localhost:3000](http://localhost:3000) to access the application.

---

## 7. Important Note

Make sure to connect this frontend application with the corresponding backend for full functionality. Update API calls and endpoints as needed.

---
