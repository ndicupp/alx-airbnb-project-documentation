# alx-airbnb-project-documentation
Airbnb Clone - Use Case Diagram
Actors:
1. Guest (Unauthenticated User)

Browse properties

Search and filter listings

View property details

Register account

Login to system

2. Guest (Authenticated User)

All guest functionalities plus:

Book properties

Make payments

Manage bookings

Write reviews

Message hosts

Manage wishlists

Update profile

3. Host

All authenticated user functionalities plus:

Create property listings

Manage property availability

Update property details

Handle booking requests

Manage pricing

Respond to reviews

Receive payments

View host dashboard

4. Admin

All system functionalities

Manage users

Moderate content

Handle disputes

View analytics

System configuration

5. Payment Gateway (External System)

Process payments

Handle refunds

Verify transactions

Key Use Cases:
Authentication & Profile Management
Register User Account

Login to System

Logout from System

Update User Profile

Manage Account Settings

Reset Password

Property Management
Search Properties

Filter Listings

View Property Details

Create Property Listing

Edit Property Information

Manage Property Photos

Set Property Availability

Update Pricing

Delete Property Listing

Booking System
Check Availability

Create Booking Request

Confirm Booking

Modify Booking

Cancel Booking

View Booking History

Manage Booking Calendar

Payment Processing
Process Payment

Handle Refund

Calculate Total Amount

Apply Discounts

Manage Security Deposit

Process Host Payout

Reviews & Ratings
Write Review

Rate Property

Respond to Reviews

Report Inappropriate Content

Edit Review

Communication System
Send Message to Host/Guest

View Conversation Thread

Receive Notifications

Manage Inbox

Admin Functions
Manage User Accounts

Moderate Listings

Resolve Disputes

Generate Reports

View System Analytics

Configure Platform Settings

System Boundaries:
Core System:

User Management Module

Property Management Module

Booking Engine

Payment Processing Module

Review System

Messaging System

Admin Dashboard

External Systems:

Payment Gateway API

Email Service

Notification Service

Map Service (for location)

File Storage Service

Relationships:
Include Relationships:

"Book Property" includes "Check Availability"

"Process Payment" includes "Calculate Total Amount"

"Create Booking" includes "Validate Dates"

Extend Relationships:

"Register User" can extend to "Verify Email"

"Process Payment" can extend to "Apply Promo Code"

"Write Review" can extend to "Upload Photos"
