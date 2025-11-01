🌱 YieldWise AI
Python Version Flask Frontend Hackathon

An all-in-one platform for African farmers to plan profitable farms, diagnose plant diseases with a photo, and build their agricultural business using the power of AI.

Developed by Kipruto Andrew Kipngetich

🚀 View Live Demo
📖 About The Project
In Kenya and across Africa, millions of smallholder farmers face a critical information gap. Limited access to expert agronomic advice, the high cost of soil testing, and the devastating impact of pests and diseases lead to reduced yields and financial instability. This directly impacts food security and economic growth, a core challenge of SDG 2: Zero Hunger.

YieldWise AI is our solution. It's a web-based platform that puts an AI-powered agronomist and a plant pathologist in the pocket of every farmer, for free. By leveraging state-of-the-art AI, we provide instant, actionable intelligence that empowers farmers to make smarter, data-driven decisions, increase their profitability, and contribute to a more food-secure future.

✨ Core Features
Our platform is a suite of powerful, easy-to-use tools:

Feature	Description
📝 AI Farm Planner	Describe your land, budget, and location, and our AI generates a detailed, step-by-step business plan using the lightning-fast Groq Llama 3.1 model.
🔬 AI Plant Doctor	Upload a photo of an affected plant leaf, and our multimodal AI (Google Gemini 1.5 Flash) will diagnose the disease and suggest treatments.
🚀 Shareable Showcases	Turn any farm plan into a beautiful, public webpage to share with potential partners, investors, or customers.
📄 Professional PDFs	Download any farm plan as a professionally formatted PDF document, perfect for printing or sharing.
💬 Interactive Chat	Ask follow-up questions about your plans and diagnoses to get deeper, context-aware insights from the AI.
👤 Full User System	A complete user registration and login system allows users to save and manage their history of farm plans and diagnoses.
🛠️ Tech Stack
We chose a modern, scalable, and efficient tech stack to bring this vision to life:

python flask sqlite javascript html5 css3

Backend:
Framework: Flask (Python)
Database: SQLite 3
AI Integration: LangChain with Groq API (Llama 3.1) & Google Gemini 1.5 Flash API
User Management: Flask-Login
Security: Werkzeug (password hashing), Flask-Limiter (rate limiting)
Frontend:
Templating: Jinja2
Styling: Vanilla HTML5 & CSS3
Scripting: Vanilla JavaScript
PDF Generation:
WeasyPrint for converting HTML & CSS to high-quality PDF reports.
⚙️ Getting Started
To get a local copy up and running, follow these simple steps.

Prerequisites
Python 3.10+
pip and venv
Installation & Setup
Clone the repository:

git clone [https://github.com/Nwokike/yieldwise-ai.git](https://github.com/Nwokike/yieldwise-ai.git)
cd yieldwise-ai
Create and activate a virtual environment:

# For Windows (Git Bash)
python -m venv venv
source venv/Scripts/activate

# For macOS/Linux
# python3 -m venv venv
# source venv/bin/activate
Install the required packages:

pip install -r requirements.txt
Set up your environment variables: Create a file named .env in the project root and add your secret API keys.

# Get your key from [https://console.groq.com/](https://console.groq.com/)
GROQ_API_KEY="gsk_..."

# Get your key from [https://aistudio.google.com/](https://aistudio.google.com/)
GOOGLE_API_KEY="AIzaSy..."
Initialize the database and run the app: The database will be created automatically on the first run.

python app.py
The application will then be available at http://127.0.0.1:5000.

👨‍💻 About The Author
Kipruto Andrew Kipngetich

I am a software developer on a mission to improve the technology and build software applications to solve real world problems. As a current student at PLP Africa, I am passionate about leveraging AI to create practical, impactful solutions.

GitHub Gmail
