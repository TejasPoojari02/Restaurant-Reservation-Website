# Restaurant Reservation Website

## Overview

This is a fully functional Restaurant Reservation Website created using HTML, CSS, JavaScript, and PHP. The website has four main pages: Home, Reservation, Menu, and Speciality. Users can reserve a seat by entering their details and receive a confirmation email upon submission.

## Features

- **Home Page**: Welcome page with an introduction to the restaurant.
- **Reservation Page**: Form for users to reserve seats by providing their name, email ID, mobile number, number of seats, date, and timeslot.
- **Menu Page**: Display of the restaurant's menu items.
- **Speciality Page**: Showcasing images of the restaurant's speciality dishes.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/restaurant-reservation-website.git
    ```
2. Navigate to the project directory:
    ```bash
    cd restaurant-reservation-website
    ```
3. Set up your server environment. Ensure PHP is installed and configured.
4. Place the project directory in your server's root directory (e.g., `htdocs` for XAMPP).

## Configuration

1. **Database Setup**:
    - Create a database for the reservation system on Xampp server.
    - View the stored data on the Xampp Server with Time stamp.

2. **Email Configuration**:
    - Update the email settings in `reservation.php` with your SMTP server details to enable email confirmation functionality.

## Usage

1. **Home Page**: Navigate to the Home page to get an overview of the restaurant.
2. **Reservation Page**: Go to the Reservation page, fill in the reservation form, and submit your details.
    - The form includes fields for:
        - Name
        - Email ID
        - Mobile Number
        - Number of Seats
        - Date
        - Timeslot
    - Upon submission, you will receive a confirmation email.
3. **Menu Page**: Browse through the restaurant's menu items.
4. **Speciality Page**: View images of the restaurant's speciality dishes.

## Pages Overview

### Home Page

- Introduction to the restaurant.
- Navigation links to other pages.

### Reservation Page

- Reservation form with fields for user details.
- Form validation using JavaScript.
- PHP backend to handle form submission and send confirmation email.

### Menu Page

- Display of the restaurant's menu items.
- HTML and CSS for layout and styling.

### Speciality Page

- Images of the restaurant's speciality dishes.
- HTML and CSS for layout and styling.

## Code Structure

- `home.html`: Home page
- `reservation.html`: Reservation page
- `menu.html`: Menu page
- `speciality.html`: Speciality page
- `styles.css`: Stylesheet for the website
- `script.js`: JavaScript for form validation and interactivity
- `reservation.php`: PHP script to handle form submission and send confirmation email

## Contributing

If you would like to contribute to this project, please fork the repository and create a pull request with your changes.



## Contact

If you have any questions or suggestions, feel free to contact me at tejaspoojari02@gmail.com.

---

**Note:** This is a basic implementation intended for demonstration purposes. For a production-level application, additional features and security measures should be implemented.

---

Enjoy making reservations at our restaurant!
