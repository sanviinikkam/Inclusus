
# Inclusus

Inclusus is an inclusive and accessible job discovery platform that connects individuals from diverse backgrounds and marginalized communities to meaningful employment opportunities. It prioritizes accessibility, ease of use, and job readiness support.

---

## 🌟 Features

- 🔍 **Inclusive Job Listings**: Curated roles for individuals with varied educational, regional, or physical backgrounds.
- 🗣️ **Text-to-Speech**: Read-aloud functionality for improved accessibility.
- 🧠 **AI Resume Builder**: Integrated third-party AI to help users craft impactful resumes.
- 📊 **Skill Gap Awareness**: Personalized messaging on where users can upskill.
- 🎓 **Courses & Assistance Programs**: Connects users with educational resources and government support programs.
- 🔐 **Simple Auth**: Login/signup functionality using `localStorage`.

---

## 🧑‍💻 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python Flask API (`app.py`)
- **Others**: Google Fonts, AI-powered Resume Builder (external integration), ARIA accessibility standards

---

## 📁 Folder Structure

Inclusus/
├── app.py # Flask API for job listings
├── login.html # Login page
├── signup.html # Signup page
├── logout.html # Logout logic
├── assistance.html # Government and NGO programs
├── courses.html # Upskilling and training opportunities
├── job-details.html # Job detail view
├── hacky.html # Main landing page
├── hacky.js / hacky.css # Frontend logic and styling
├── style.css, job-details.css, etc.
├── attachments.zip # Supporting documents or assets
├── README.md # This file

---

## 🚀 Getting Started Locally

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/sanviinikkam/Inclusus.git
   cd Inclusus
Install Requirements
(Only Flask is needed)

bash
Copy
Edit
pip install flask flask-cors
Run the Server

bash
Copy
Edit
python app.py
The backend will run on http://localhost:5501.

Open hacky.html in Browser
The frontend can be opened directly via browser.

