# GOBDI Database Design

## Users

- id
- fullName
- phoneNumber
- email
- password
- profilePhoto
- role
- country
- city
- createdAt

## Drivers

- driverId
- userId
- vehicleType
- vehicleNumber
- drivingLicense
- nationalId
- status
- rating
- onlineStatus

## Vehicles

- vehicleId
- type
- brand
- model
- color
- plateNumber

## Bookings

- bookingId
- riderId
- driverId
- pickupLocation
- destination
- fare
- distance
- status
- paymentMethod
- createdAt

## Payments

- paymentId
- bookingId
- amount
- paymentMethod
- paymentStatus

## Reviews

- reviewId
- bookingId
- riderId
- driverId
- rating
- comment
