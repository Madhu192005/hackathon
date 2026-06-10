# 🏛️ District Collectorate Museum, Thanjavur – AI-Based Ticket Booking & Visitor Guide System

An intelligent museum management and visitor assistance platform developed for the **District Collectorate Museum, Thanjavur**. The system enables visitors to explore museum exhibits, plan visits, generate personalized itineraries, interact with an AI-powered museum guide, and book tickets online through Razorpay integration.

---

## 📖 Project Overview

The District Collectorate Museum, Thanjavur, was inaugurated on **14 January 2023** under the **Smart Cities Mission**. Located in a historic building designed by British architect **Robert Chisholm** in the Indo-Saracenic architectural style, the museum showcases the rich cultural and historical heritage of Thanjavur.

This web application serves as a digital platform that enhances visitor experience through:

- Online ticket booking
- AI-powered visitor assistance
- Personalized visit planning
- Smart itinerary generation
- Heritage information and exhibit exploration

---

## ✨ Features

### 🏠 Home Page
- Museum introduction and branding
- Government initiative highlights
- Quick access to ticket booking
- Call-to-action sections

### ℹ️ About Us
- Museum history
- Architectural significance
- Heritage and cultural information

### 🖼️ Gallery
- Interactive image gallery
- Museum building
- Tanjore Temple
- Saraswathi Mahal Library
- Maratha Palace

### 🎟️ Online Ticket Booking
- Adult ticket booking
- Child ticket booking
- Camera ticket booking
- Dynamic pricing calculation
- Razorpay payment integration
- Booking confirmation summary

### 🤖 AI Museum Guide
- Conversational chatbot interface
- Museum timings information
- Ticket pricing assistance
- Exhibit recommendations
- Booking support
- Voice input support

### 🧠 AI Visit Planner
Personalized recommendations based on visitor interests:

- 🗿 Sculptures & Bronze
- 🎨 Paintings & Art
- 🛕 Temple & Heritage
- 👑 Royal History
- 📚 Library & Manuscripts
- 🪙 Coins & Numismatics

### 🗺️ AI Smart Itinerary Builder
- Visit duration customization
- Hour-by-hour itinerary generation
- Smart route recommendations
- Expert visit tips

### 📞 Contact Us
- Museum contact details
- Visitor information
- Inquiry support

---

## 🛠️ Technology Stack

### Frontend
- HTML5
- CSS3
- JavaScript (Vanilla JS)

### Backend
- Node.js
- Express.js

### Database
- MySQL

### AI Features
- Custom Rule-Based Chatbot
- Interest Recommendation Engine
- Smart Itinerary Generator

### Payment Gateway
- Razorpay API

### Version Control
- Git & GitHub

---

# 📂 Project Structure

```text
museum-booking-system/
│
├── public/
│   │
│   ├── pages/
│   │   ├── index.html
│   │   ├── about.html
│   │   ├── gallery.html
│   │   ├── ticket.html
│   │   ├── bot.html
│   │   ├── contact.html
│   │   ├── museum.html
│   │   ├── tanjore.html
│   │   ├── maratha.html
│   │   └── sar.html
│   │
│   ├── css/
│   │   ├── styles.css
│   │   ├── ai-chatbot.css
│   │   └── ai-features.css
│   │
│   ├── js/
│   │   ├── script.js
│   │   ├── ai-chatbot.js
│   │   └── ai-features.js
│   │
│   └── images/
│       ├── gallery/
│       └── branding/
│
├── server/
│   │
│   ├── config/
│   │   ├── db.js
│   │   └── razorpay.js
│   │
│   ├── controllers/
│   │   ├── ticketController.js
│   │   └── chatbotController.js
│   │
│   ├── routes/
│   │   ├── ticketRoutes.js
│   │   └── chatbotRoutes.js
│   │
│   ├── services/
│   │   ├── paymentService.js
│   │   ├── recommendationService.js
│   │   └── itineraryService.js
│   │
│   ├── models/
│   │   ├── ticketModel.js
│   │   └── userModel.js
│   │
│   └── server.js
│
├── database/
│   ├── schema.sql
│   └── seed.sql
│
├── .env
├── .env.example
├── .gitignore
├── package.json
├── package-lock.json
└── README.md
```

---

# ⚙️ Installation & Setup

## Prerequisites

Before running the project, ensure the following software is installed:

- Node.js
- npm
- MySQL Server
- Git

---

## Step 1: Clone Repository

```bash
git clone https://github.com/your-username/museum-booking-system.git
cd museum-booking-system
```

---

## Step 2: Install Dependencies

```bash
npm install
```

---

## Step 3: Configure Environment Variables

Create a `.env` file:

```env
PORT=3000

DB_HOST=localhost
DB_USER=root
DB_PASSWORD=password
DB_NAME=museum_db

RAZORPAY_KEY_ID=your_key_id
RAZORPAY_SECRET=your_secret
```

---

## Step 4: Import Database

```bash
mysql -u root -p
```

```sql
CREATE DATABASE museum_db;
USE museum_db;
SOURCE database/schema.sql;
```

---

## Step 5: Start Server

```bash
node server.js
```

Or using nodemon:

```bash
npm run dev
```

---

## Step 6: Open Application

```text
http://localhost:3000
```

---

# 🤖 AI Modules

## AI Museum Guide

Provides:

- Ticket information
- Museum timings
- Exhibit details
- Booking assistance
- Voice interaction

---

## AI Visit Planner

Generates personalized recommendations using visitor interests.

Example:

Input:

```text
Interest: Temple & Heritage
Duration: 3 Hours
```

Output:

```text
1. Tanjore Temple Gallery
2. Bronze Sculpture Collection
3. Historical Archives
4. Saraswathi Mahal Library
```

---

## AI Smart Itinerary Builder

Creates optimized routes:

```text
10:00 AM - Entry & Orientation
10:30 AM - Heritage Gallery
11:15 AM - Bronze Collection
12:00 PM - Maratha Palace Exhibit
01:00 PM - Exit
```

---

# 💳 Ticket Booking Workflow

1. Visitor selects ticket type.
2. System calculates total amount.
3. Razorpay order is created.
4. User completes payment.
5. Booking details are stored in MySQL.
6. Confirmation is displayed.

---

# 🗄️ Database Design

## Ticket Table

| Column | Type |
|----------|----------|
| id | INT |
| name | VARCHAR |
| email | VARCHAR |
| adults | INT |
| children | INT |
| camera | INT |
| total_amount | DECIMAL |
| booking_date | DATE |

---

# 🔒 Security Features

- Environment variables for sensitive credentials
- Input validation
- SQL Injection prevention
- Payment verification
- Error handling

---

# 🚀 Future Enhancements

- User Authentication
- Admin Dashboard
- QR Code Tickets
- Email Notifications
- AI Recommendation Improvements
- Tamil Language Support
- Visitor Analytics Dashboard

---


