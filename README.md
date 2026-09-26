# SafeVoyage
SafeVoyage is an AI-powered travel safety platform that provides real-time alerts, SOS support, and smart route insights. It integrates location tracking, risk analysis, and emergency communication to help travelers stay informed, connected, and safe throughout their journey.
🛡️ SafeVoyage — AI-Powered Travel Safety Platform

Travel Smart. Stay Alert. Travel Safe. 🌍

SafeVoyage is a travel-safety web application designed to help travelers monitor destination risks, plan safer trips, receive timely alerts, and respond quickly during emergencies.

Built during a 24-hour hackathon, SafeVoyage combines travel planning, safety intelligence, weather information, location services, emergency communication, and an AI-powered travel assistant into a single platform.

The system analyzes a traveler's destination, itinerary, activity, date, and time to identify potential safety concerns and provide understandable recommendations.

✨ Key Features
🤖 1. AI Travel Assistant

SafeVoyage includes an AI-powered assistant that helps travelers with safety-related questions and travel decisions.

Example:

User: "Is it safe to visit the beach tomorrow afternoon?"

The assistant provides relevant travel and safety information based on available destination, weather, and advisory data.

📊 2. Travel Risk Dashboard

The dashboard provides an overall view of the traveler's safety status.

It displays:

Overall risk score
Weather risk
Health risk
Safety risk
Active advisories
Upcoming activity warnings

Example:

Overall Risk: 72 / 100
Status: HIGH

Weather: Moderate
Health: Low
Safety: High
Advisories: High

⚠️ Upcoming Warning:
Day 2 • 3:00 PM
Marina Beach
High-Surf Advisory
🗓️ 3. Smart Itinerary Safety Analysis

Travelers can create a multi-day itinerary with destinations, activities, dates, and times.

SafeVoyage checks planned activities against relevant safety advisories using:

Location + Category + Date + Time Window

Example:

🟢 Day 1 • 10:00 AM
City Palace — CLEAR

🟢 Day 1 • 3:00 PM
Government Museum — CLEAR

🟢 Day 2 • 10:00 AM
City Tour Bus — CLEAR

🔴 Day 2 • 3:00 PM
Marina Beach — AFFECTED
High-Surf Advisory

🟢 Day 3 • 11:00 AM
T. Nagar Shopping Street — CLEAR
🗺️ 4. Interactive Safety Map

The Safety Map provides a visual overview of important safety-related locations.

It can display:

🟢 Safe zones
🟡 Caution areas
🔴 Higher-risk areas
🏥 Hospitals
🚔 Police stations
📍 Important locations
🌦️ 5. Weather & Safety Alerts

SafeVoyage provides weather-related information that can affect travel plans.

Examples include:

🌧️ Heavy Rain
💨 Strong Winds
🌊 High Surf
⛈️ Storm Conditions

When a weather condition affects a planned activity, the traveler can receive a corresponding warning.

🚨 6. Emergency SOS & Location Sharing

SafeVoyage provides an emergency SOS feature for critical situations.

When SOS is activated:

The traveler confirms the emergency.
The system captures the current location.
Emergency information is prepared.
The configured emergency contact can be notified.
The traveler's location can be shared for assistance.

Example:

🚨 EMERGENCY SOS ACTIVATED

Location:
Marina Beach Promenade

Coordinates:
13.0500, 80.2824

Emergency contact notification initiated.
📱 7. Emergency SMS Alerts

The platform can integrate with Twilio to send emergency SMS notifications.

Example:

SAFEVOYAGE ALERT 🚨

Rahul has activated Emergency SOS.

Current Location:
Marina Beach Promenade

Please contact the traveler immediately.
👨‍👩‍👧 8. Family & Co-Traveller Monitoring

Travel groups can be represented with individual safety statuses.

Example:

Rahul   🟢 Safe
Anu     🟢 Safe
Priya   🟡 Caution
Arjun   🔴 Alert

This helps the primary traveler monitor family members or other people in the group.

🌗 9. Light & Dark Mode

SafeVoyage supports both light and dark themes, allowing users to switch the interface according to their preference.

🧠 How SafeVoyage Works
Traveler
   ↓
Enter Trip Details
   ↓
Destination + Date + Time + Activity
   ↓
Safety & Weather Information
   ↓
Risk / Advisory Analysis
   ↓
┌───────────────────────────┐
│ SafeVoyage Safety Engine  │
└───────────────────────────┘
   ↓
Risk Score + Alerts
   ↓
Dashboard / Map / AI Assistant
   ↓
Emergency SOS if Required
🛠️ Technology Stack
Frontend
React.js
Vite
JavaScript
HTML5
CSS3
Backend
Node.js
Express.js
Database
MongoDB
APIs & Services
Google Maps API
OpenWeather API
Twilio
AI Integration
Authentication & Security
JWT Authentication
Environment Variables
🚀 Quick Start
1. Clone the Repository
git clone <your-repository-url>
cd SafeVoyage
2. Start the Backend
cd backend
npm install
npm start

Backend:

http://localhost:5000
3. Start the Frontend

Open another terminal:

cd frontend
npm install
npm run dev

Frontend:

http://localhost:5173
🔑 Environment Variables
Backend .env
PORT=5000
JWT_SECRET=your_secret_key

TWILIO_ACCOUNT_SID=
TWILIO_AUTH_TOKEN=
TWILIO_PHONE_NUMBER=

OPENWEATHER_API_KEY=
Frontend .env
VITE_GOOGLE_MAPS_API_KEY=
VITE_WEATHER_API_KEY=

⚠️ Never commit real API keys, passwords, JWT secrets, or other credentials to GitHub.

🎯 Example User Journey

A traveler planning a trip to Chennai creates a 3-day itinerary.

Step 1 — Plan the Trip
Day 1
10:00 AM → City Palace
3:00 PM  → Government Museum

Day 2
10:00 AM → City Tour
3:00 PM  → Marina Beach

Day 3
11:00 AM → T. Nagar
Step 2 — Analyze the Itinerary

SafeVoyage compares planned activities with available safety and advisory information.

Step 3 — Detect a Risk
🔴 Marina Beach
High-Surf Advisory
Day 2 • 3:00 PM
Step 4 — Alert the Traveler

The dashboard highlights the affected activity so the traveler can reconsider their plan.

Step 5 — Emergency Response

If an emergency occurs, the traveler can activate:

🚨 Emergency SOS

The system can share the traveler's location and initiate emergency-contact communication
