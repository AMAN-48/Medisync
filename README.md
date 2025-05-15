MediSync - Doctor Appointment Booking App
MediSync is a health-tech platform that allows patients to discover, book, and pay for doctor appointments online. It streamlines the connection between patients and healthcare professionals using a user-friendly interface and secure payment processing via Razorpay.

❓ Problem Statement
Make a digital healthcare platform where:
Patients can explore available doctors
Appointments can be booked directly through the application
Payments can be securely processed online

Note: Razorpay is used for handling secure transactions for appointments.

🛠 Technology Stack
Frontend: HTML, CSS, JavaScript, Bootstrap
Backend / Server: Node.js, Express.js
Database: MongoDB (or MySQL if used)
Payment Gateway: Razorpay Integration
Authentication: Basic login / OTP (if implemented)

✅ Features
Doctor listing with specialization and fees
User-friendly appointment scheduling
Secure online payments using Razorpay
Confirmation messages on successful booking

⚙️ Setup Instructions
Clone the repository

git clone https://github.com/your-username/medisync.git
cd medisync

Install dependencies
npm install

Configure .env
RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_key_secret
MONGO_URI=your_mongodb_uri

Run the application
npm start

🔒 Razorpay Integration
Patients are redirected to Razorpay’s secure checkout.
Once payment is successful, appointment data is saved.
Payment confirmation shown with booking summary.

Future Scope
Video consultation module
Prescription management
SMS/email appointment reminders
Doctor dashboard & analytics

