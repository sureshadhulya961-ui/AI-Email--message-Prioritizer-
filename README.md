 AI Email Prioritizer 📧

An AI-powered web application that analyzes emails and organizes them based on priority, category, required action, and deadline.

 Features

- **Email Priority Classification:** Classifies emails as Urgent, Important, or Low.
- **Category Detection:** Categorizes emails into Academic, Work, Personal, Finance, Meeting, Shopping, or Other.
- **AI Summarization:** Generates short summaries of emails.
- **Action Extraction:** Identifies the required action from each email.
- **Deadline Detection:** Extracts deadlines mentioned in emails.
- **Email Dashboard:** Displays analyzed emails and their details.
- **Priority Filters:** Filter emails by priority.
- **Local Database:** Stores analyzed emails using SQLite.
- **Local AI Processing:** Uses Ollama to analyze emails without requiring OpenAI API credits.

 Technologies Used

- Python
- Flask
- Ollama
- Llama 3.2
- SQLite
- HTML
- CSS

 Prerequisites

Install the following before running the project:

- Python
- Git
- Ollama

Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/sureshadhulya961-ui/AI-Email--message-Prioritizer-.git
cd AI-Email--message-Prioritizer-
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```powershell
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Download the AI model

```bash
ollama pull llama3.2
```

Make sure Ollama is running on your computer.

### 5. Run the application

```bash
python app.py
```

Open your browser and visit:

http://127.0.0.1:5000

## Project Structure

```text
AI-Email-Prioritizer/
├── app.py
├── requirements.txt
├── .gitignore
├── templates/
│   └── index.html
└── static/
    └── style.css
```

 Privacy

The application uses a local Ollama model for email analysis. Avoid submitting sensitive or confidential emails unless you understand how they are stored and processed. The local SQLite database stores analyzed emails on the computer running the application.

Future Improvements

- Gmail API integration
- Action-required filtering
- Improved deadline detection
- Supabase database integration
- Enhanced dashboard and analytics

 Author

AI & Data Science Student

 License

No license has been added yet. All rights are reserved unless a license is added to this repository.
