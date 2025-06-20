Quizlic - AI-Powered Quiz Generator

Quizlic is an intelligent quiz generation application that uses the Google Gemini Generative AI API to create multiple-choice questions based on user-defined topics. The app is built with a FastAPI backend and a minimalist HTML, CSS, and JavaScript frontend.

Features
	•	Generates dynamic, multiple-choice questions from any user-specified topic
	•	Provides instant feedback for questions
	•	Leverages the Google Gemini (Generative AI) API for intelligent questions
	•	Features a clean and minimal user interface

Tech Stack

Layer	Technology
Backend	FastAPI
Frontend	HTML, CSS, JavaScript
AI Model	Google Gemini via API

Installation
	1.	Clone the repository:

git clone https://github.com/your-username/Quizlic.git
cd Quizlic


	2.	Install dependencies:

pip install -r requirements.txt


	3.	Create a .env file:

GENAI_API_KEY=your_google_gemini_api_key


	4.	Run the application:

uvicorn main:app --reload



Deployment

Deploy this app on platforms like Render, Railway, or Vercel.

For Render:

unicorn main:app --reload

For Railway:
Visit the project dashboard and obtain your app’s deployment URL.

Usage
	1.	Open the app in a browser.
	2.	Enter topics (comma-separated).
	3.	Choose the number of questions.
	4.	Click “Generate Quiz” and start answering!

Contributing

Pull requests are welcome. For major changes, open an issue first to discuss proposed changes.

License

MIT