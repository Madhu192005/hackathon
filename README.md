Project Overview
The District Collectorate Museum, Thanjavur, was inaugurated on January 14, 2023, as part of the Smart Cities Mission. The museum is located in a historic building constructed in 1900 by British architect Robert Chisol in the Indo-Saracenic architectural style. The website serves as the digital gateway for visitors to explore exhibits, plan visits, and book tickets online.

| Feature                  | Description                                                                                                                                                                 |
| ------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Home Page**            | Hero section with museum branding, government logos (Ministry of Culture, G20, Azadi Ka Amrit Mahotsav), and quick booking CTA                                              |
| **About Us**             | Museum history, architectural significance, and heritage information                                                                                                        |
| **Gallery**              | Interactive image gallery showcasing Tanjore Temple, Museum building, Saraswathi Mahal Library, and Maratha Palace                                                          |
| **Tickets**              | Online ticket booking system with Razorpay payment integration                                                                                                              |
| **AI Chatbot**           | Museum AI Guide for visitor assistance — provides timings, prices, exhibit info, and ticket booking via conversational interface                                            |
| **AI Visit Planner**     | Smart recommendation engine based on visitor interests (Sculptures & Bronze, Paintings & Art, Temple & Heritage, Royal History, Library & Manuscripts, Coins & Numismatics) |
| **AI Itinerary Builder** | Personalized hour-by-hour museum route generator                                                                                                                            |
| **Contact Us**           | Visitor information and contact details                                                                                                                                     |

Tech Stack
Frontend: HTML5, CSS3, JavaScript (Vanilla)
Backend: Node.js (server.js)
Database: MySQL (database.sql)
AI Features: Custom AI chatbot (ai-chatbot.js, ai-features.js) with CSS styling
Payment: Razorpay integration for online ticket booking
Styling: Custom CSS (styles.css, ai-chatbot.css, ai-features.css)

Project Structure
hackthon-main/
├── index.html              # Home page
├── about.html              # About the museum
├── gallery.html            # Photo gallery
├── ticket.html             # Ticket booking page
├── bot.html                # Chatbot interface
├── contact.html            # Contact information
├── museum.html             # Museum details page
├── tanjore.html            # Tanjore Temple details
├── maratha.html            # Maratha Palace details
├── sar.html                # Saraswathi Mahal Library details
├── styles.css              # Main stylesheet
├── ai-chatbot.css          # Chatbot styling
├── ai-features.css         # AI features styling
├── script.js               # Main JavaScript
├── ai-chatbot.js           # Chatbot logic
├── ai-features.js          # AI planner/itinerary logic
├── server.js               # Node.js backend server
├── database.sql            # MySQL database schema
├── package.json            # Node dependencies
├── .env / .env.example     # Environment variables
├── images/                 # Image assets
└── README.md               # This file


Key Functionalities
1. AI Museum Guide (Chatbot)
Conversational interface for visitor queries
Quick-action buttons: Timings, Prices, Book Ticket, Exhibits
Voice input support ("Ask or tap 🎤 to speak")
Real-time booking assistance with Razorpay checkout
2. AI Visit Planner
Interest-based recommendations:
🗿 Sculptures & Bronze
🎨 Paintings & Art
🛕 Temple & Heritage
👑 Royal History
📚 Library & Manuscripts
🪙 Coins & Numismatics
3. AI Smart Itinerary Builder
Customizable visit duration input
Generates personalized hour-by-hour museum routes
Expert tips for optimal experience
4. Online Ticket Booking
Dynamic pricing (Adults, Children, Camera tickets)
Razorpay payment gateway integration
Booking confirmation with summary

Installation & Setup
Prerequisites
Node.js installed
MySQL server running
Steps
Clone the repository
bash
git clone <repository-url>
cd hackthon-main
Install dependencies
bash
npm install
Set up environment variables
bash
cp .env.example .env
# Edit .env with your database and Razorpay credentials
Import database
bash
mysql -u root -p < database.sql
Start the server
bash
node server.js
Open in browser
plain
http://localhost:3000

Credits
Developed for: Smart Cities Mission, Thanjavur
District Administration: Thanjavur District Collector Office
Heritage Partner: Tamil Nadu Tourism Development Corporation

License
Madhusudhanan 


