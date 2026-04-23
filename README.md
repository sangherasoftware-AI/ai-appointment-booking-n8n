# 📅 Online Appointment Booking System
A fully automated appointment booking system built using n8n, designed to handle the complete lifecycle of bookings from creation to cancellation with integrated payment and refund processing via Stripe.

## 🚀 Features
* New Booking
* View Upcoming Bookings
* Reschedule Booking
* Cancel Booking
* Payment Integration (Stripe)
* Refund Handling

## 🛠 Tech Stack
* n8n (Workflow Automation)
* Stripe (Payments API)

## 📂 Project Structure
* `/workflows` → n8n workflow JSON files
* `/docs` → system design and flow explanation

## ⚙️ Setup Instructions
1. Import workflows into n8n
2. Add your environment variables
3. Connect Stripe API
4. Activate workflows

## 💳 Payment Flow
* Create Payment Intent
* Confirm Payment
* Handle Refund on Cancellation

## 🔄 Booking Flow
1. User creates booking
2. Payment processed
3. Booking stored
4. User can reschedule or cancel
5. Refund triggered on cancellation

## 📌 Future Improvements
* Email notifications
* SMS reminders
* Admin dashboard

