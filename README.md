# Audio / Speech to Sign Language Converter 🔊🤟

## Overview
This project converts **spoken audio or speech into sign language representations**, helping bridge the communication gap between hearing and speech-impaired individuals.

The system captures speech input, converts it into text using speech recognition techniques, and displays the corresponding sign language output through visual assets.  
This project is developed using **Python and Django** and focuses on accessibility and inclusive communication.

---

## Project Structure
Audio-Speech-To-Sign-Language-Converter/
│── A2SL/ # Main Django application
│── assets/ # Sign language images/videos and static assets
│── templates/ # HTML templates
│── manage.py # Django management script
│── requirements.txt # Python dependencies
│── setup.py # Project setup file
│── db.sqlite3 # SQLite database (ignored in GitHub)
│── README.md # Project documentation


---

## Technologies Used
- **Programming Language:** Python  
- **Web Framework:** Django  
- **Speech Processing:** Speech Recognition libraries  
- **Frontend:** HTML, CSS  
- **Database:** SQLite  

---

## Features
- Converts spoken audio into text  
- Maps recognized text to sign language visuals  
- Web-based user interface  
- Focus on accessibility and assistive technology  
- Easy-to-use and interactive design  

---

## How It Works
1. User provides speech input through the application  
2. Speech is converted into text  
3. The text is mapped to corresponding sign language gestures  
4. Sign language output is displayed visually on the web interface  

---

## How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Shamanthking/Audio-Speech-To-Sign-Language-Converter.git
cd Audio-Speech-To-Sign-Language-Converter
2️⃣ Create Virtual Environment
python -m venv venv
venv\Scripts\activate
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Run the Django Server
python manage.py runserver
5️⃣ Open in Browser
http://127.0.0.1:8000/
Use Cases
Assistive technology for hearing-impaired users

Educational applications

Accessibility-focused web systems

Future Enhancements
Support for multiple sign languages

Real-time animated sign avatars

Improved speech recognition accuracy

Mobile-friendly interface

Conclusion
This project demonstrates the integration of speech recognition and web technologies to create an inclusive system that enhances accessibility and communication.

License
This project is open-source and available for educational and research purposes.
