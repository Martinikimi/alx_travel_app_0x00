# ALX Travel App

A Django-based travel accommodation booking application that allows users to browse listings, make bookings, and leave reviews.

## Features

- **Listings Management**: Hosts can create and manage property listings
- **Booking System**: Users can book accommodations with various status tracking
- **Reviews & Ratings**: Guests can leave reviews and ratings for their stays
- **User Authentication**: Secure user registration and login system
- **Search & Filter**: Advanced search and filtering for listings

## Models

### Listing
- Property details (type, bedrooms, bathrooms, amenities)
- Location information (address, city, country, coordinates)
- Pricing and availability
- Host information

### Booking
- Reservation details (check-in, check-out, guests)
- Pricing and status tracking
- User and listing relationships

### Review
- Rating system (1-5 stars)
- Text reviews
- User and listing relationships

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd alx_travel_app
