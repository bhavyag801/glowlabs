## Description

Glow Labs, a small business, has been using Square for booking appointments, managing clients and employees, and as a point of sale (POS) system.

## Features

- **Guest clients are able to:**
  - Add and remove facial treatments and add-ons (certain combinations disallowed) from their shopping cart.
  - Select a staff member they would like their service with (or, if no preference, select a random staff member).
  - Choose an available time and date for their appointment.
  - Fill out contact information and any appointment notes.
  - Submit credit card information securely through a [Square Payment Form](https://github.com/square/react-square-payment-form) to hold their appointment. This form is an iframe (no credit card information is stored on Glow Labs' MongoDB database. Rather, this information goes to Square's POS).
  - Book selected appointments and receive:
    - Link to fill out and sign a consent form.


## Technologies Used

- **Frontend:**
  - React
  - Redux
  - Apollo Client
  - Google Maps API
  - Square Payment Form
  - Twilio


