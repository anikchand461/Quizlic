Quizlic - AI-Powered Quiz Generation Application

Quizlic is a state-of-the-art quiz generation application that uses the Google Gemini Generative AI API to create sophisticated, context-aware multiple choice questions. It now supports extracting text from PDFs and images (using the OCR Space API), making it ideal for creating questions from documents, images, or other learning materials.

Developed with a robust FastAPI backend, an interactive HTML/CSS/JavaScript frontend, and powered by SQLite for data storage, Quizlic delivers a seamless and personalized user experience.

Features
	•	AI-Driven Quiz Generation across topics, PDFs, and images
	•	Uses OCR Space API to read images and extract text for quiz generation
	•	Provides instant feedback and explanations
	•	Implements user authentication and profile management
	•	Maintains user data in a secure SQLite database
	•	Features a live leaderboard to track user progress
	•	User-friendly, clean, and minimalist interface

Tech Stack

Layer	Technology
Backend	FastAPI
Frontend	HTML, CSS, JavaScript
AI Model	Google Gemini via Generative AI API
Database	PostgreSQL
OCR Service	OCR Space API

Installation
	1.	Clone the Repository:

git clone https://github.com/your-username/Quizlic.git
cd Quizlic


	2.	Install Dependencies:

pip install -r requirements.txt


	3.	Setup Environment Variables:
Create a .env file:

GENAI_API_KEY=your_google_gemini_api_key
OCR_SPACE_API_KEY=your_ocr_space_api_key


	4.	Run the Application Locally:

uvicorn app:app --reload



Deployment
	•	Render: Set the start command as:

uvicorn main:app --reload


	•	Render: Configure your app and obtain the deployment URL from the Render Dashboard.

Usage
	1.	Open the app in a browser.
	2.	Sign up or log in to access your profile and track scores.
	3.	Enter topics, or upload PDFs and images.
	4.	Choose the number of questions, click “Generate Quiz,” and get started.

Contributing

We welcome contributions. If you’d like to propose changes or enhancements:
	•	Open an issue for discussion first.
	•	Ensure PRs adhere to project coding and documentation standards.

License

Distributed under the MIT License.
