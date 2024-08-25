# Zen Recovery

**A full-stack e-commerce application for purchasing recovery products, developed using React for the frontend and Spring Boot for the backend.**

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup and Installation](#setup-and-installation)
- [License](#license)

## Overview

Zen Recovery is an e-commerce platform that offers a seamless shopping experience for recovery products. The platform includes user-friendly features like secure payment processing, order tracking, and subscription to newsletters.

## Features

- **Product Listings**: View detailed information on various recovery products.
- **Cart and Checkout**: Add products to the cart, manage orders, and proceed to secure checkout.
- **Order Management**: Track orders and receive order confirmations via email.
- **Newsletter Subscription**: Subscribe to the newsletter to receive updates and special offers.

## Tech Stack

- **Frontend**: React, HTML, CSS, JavaScript
- **Backend**: Spring Boot, Java
- **Database**: PostgreSQL (deployed on Heroku)
- **Payment Processing**: Stripe API
- **Email Service**: JavaMailSender

## Setup and Installation

### Prerequisites

- **Java 21** or later
- **Node.js** (for React)
- **PostgreSQL** database

### Backend

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/zen-recovery.git
    cd zen-recovery
    ```

2. Set up the PostgreSQL database and update the `application.properties` file with your database credentials.

3. Run the Spring Boot application:
    ```bash
    ./mvnw spring-boot:run
    ```

### Frontend

1. Navigate to the frontend directory:
    ```bash
    cd frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm start
    ```

  
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
