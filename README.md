
# 🌍 AI-Powered Travel Planning Agent

This project is an AI-powered travel planning assistant developed using **IBM Watsonx Assistant** and supporting cloud tools. It helps users create customized travel itineraries based on destination, budget, interests, and duration.

---

## ✈️ Overview

The assistant interacts with users through natural conversation and dynamically generates full travel itineraries including:
- Daily activities
- Hotel and local transport suggestions
- Budget-aware recommendations
- Real-time weather updates
- Local attraction highlights

---

## 💡 Features

- 🗺️ Tailored itineraries for any city worldwide
- 🎯 Suggestions based on user interests (food, adventure, beaches, museums, etc.)
- 💸 Budget-conscious planning for hotels, transport, and activities
- 🌦️ Weather-aware scheduling
- 🔁 Follow-up questions if user input is incomplete or unclear
- 📱 Accessible via mobile or web interface

---

## 🧠 Technologies Used

- **IBM Watsonx Assistant** – Core agent orchestration and conversation handling
- **Python Runtime (Interpreter Tool)** – For logic, date calculations, etc.
- **Internet Access Tools** – DuckDuckGo, Web Search, Weather APIs
- **IBM Deployment Space** – To deploy and test the assistant
- **Secure Token Authentication** – To control access

---

## 🛠 System Architecture

1. User sends a message (e.g., "Plan a 5-day trip to Tokyo under ₹40,000")
2. Watsonx Assistant interprets and extracts travel parameters
3. Calls Python tool for logic, date calculation, or budget handling
4. Uses Internet tools to fetch:
   - Real-time weather
   - Hotel options
   - Attractions
5. Returns full itinerary to the user with emojis and formatting

---

## 📈 Potential Enhancements

- Integrate flight APIs for ticket suggestions
- Add Google Maps or Booking.com support
- Expand to handle group trips and real-time re-planning
- Use advanced LLMs or Edge AI for faster performance

---

## 📸 Screenshots (Optional)

_Add screenshots of your assistant chat interface or cloud setup here._

---

## 📂 Repository Contents

