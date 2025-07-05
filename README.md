# daily-ai-journal
Daily AI-Powered Journal – An Intelligent Journal App with Sentiment Analysis and Mood Tracking
# Daily AI Journal 🧠📓

A smart, privacy-first journaling web app built with Python, Flask, and OpenAI. It analyzes your entries for sentiment and trends to help you better understand your thoughts and habits.

## 🚀 Features
- ✍️ Clean, distraction-free journal entry interface
- 🔍 Real-time sentiment analysis using OpenAI API
- 📊 Mood tracking with auto-generated graphs
- 🔐 Local storage (no user data uploaded or tracked)
- 📅 Search your thoughts by keyword or mood

## 💡 Why I Built This
Journaling helps with mindfulness, but most apps are either overcomplicated or not private. I built this to create a simple, smart tool that respects your data and helps improve mental clarity through reflection and AI-powered insights.

## 📸 Screenshots
![Journal Entry](https://placehold.co/600x400?text=Journal+Entry+UI)
![Mood Graph](https://placehold.co/600x400?text=Mood+Tracking+Chart)

## 🛠️ Tech Stack
- Python 3.11
- Flask
- OpenAI GPT-4 (sentiment + topic extraction)
- Chart.js for data visualization
- HTML/CSS/JavaScript

## 🧠 How It Works
When you write an entry, the app sends it to OpenAI to:
- Detect overall sentiment
- Extract key emotions and topics
- Visualize trends over time

## 📦 Installation

```bash
git clone https://github.com/yourusername/daily-ai-journal.git
cd daily-ai-journal
pip install -r requirements.txt
python app/main.py
