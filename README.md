
# Medisync-Doctor Appointment Booking App

MediSync is a health-tech platform that allows patients to discover, book, and pay for doctor appointments online. It streamlines the connection between patients and healthcare professionals using a user-friendly interface and secure payment processing via Razorpay.




## ❓ Problem Statement

 Make a digital healthcare platform where:
Patients can explore available doctors
Appointments can be booked directly through the application
Payments can be securely processed online.

Note- Razorpay is used for handling secure transactions for appointments.





## Documentation

[Documentation](https://1drv.ms/p/c/2c82f468193248ca/EYCCnrJZAtFNqXmAgdzTua4BQ3XZxlZcqg1bstJzUuee1A?e=XgQ8BO)


## Features

- Doctor listing with specialization and fees
- User-friendly appointment scheduling
- Secure online payments using Razorpay
- Confirmation messages on successful booking



## Setup Instruction


```bash
 Clone the repository

git clone https://github.com/AMAN-48/medisync.git
cd medisync

```
    
## Install Dependencies
```bash
-npm install
```


## Configure .env

RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_key_secret
MONGO_URI=your_mongodb_uri

## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```


## 🔒 Razorpay Integration

Patients are redirected to Razorpay’s secure checkout.
Once payment is successful, appointment data is saved.
Payment confirmation shown with booking summary.

## Tech Stack

**Client:**  React, Redux, TailwindCSS

**Server:** Node, Express

**Database:** MongoDB




## Future Scope

Video consultation module

Prescription management

SMS/email appointment reminders

Doctor dashboard & analytics


## Work Flow of medisync

[User Opens MediSync App]

             |
             v
   [Patient Login / Register]

             |
             v
   [Browse Doctors List Page]

             |
             v
 [Select Doctor + Choose Slot]

             |
             v
   [Initiate Payment (Razorpay)]

             |
             v
   [Payment Successful?]

         /       \
       Yes        No
       |           |
       v           v
[Appointment     [Show
 Confirmed] OR   Error Message]
 
       |
       v
[Show Booking Summary to Patient]

       |
       v
 [Notify Doctor of Appointment]


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aman-tiwary-ab4262271)
