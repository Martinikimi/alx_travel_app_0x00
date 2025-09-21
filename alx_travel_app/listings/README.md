# Listings Application

## Models
- **Listing**: Property listings with details, pricing, and availability
- **Booking**: Reservation system with status tracking  
- **Review**: User reviews and ratings system

## Serializers
- Custom Django REST Framework serializers for all models
- Proper validation and relationship handling
- Nested serialization for related objects

## Management Commands
- **seed**: Populates database with sample data for testing
- Supports customizable quantities for each model type

## Database Schema
- UUID primary keys for all models
- ForeignKey relationships between models
- Proper indexing and constraints
- Data validation at model level

## Usage
```bash
# Run seeding command
python manage.py seed --listings 10 --bookings 20 --reviews 30

# Start development server
python manage.py runserver
