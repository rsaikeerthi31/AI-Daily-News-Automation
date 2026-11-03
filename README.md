# 🤖 AI Daily News Automation

An automated Python application that fetches the latest AI news, generates a daily report, saves it as a Markdown file, and emails it automatically.

---

## 🚀 Features

- Fetches the latest AI news
- Generates a daily AI news report
- Saves the report as a Markdown file
- Sends the report to Gmail automatically
- Uses environment variables to protect API keys
- Version controlled with Git & GitHub

---

## 🛠 Technologies Used

- Python 3.12
- News API
- Google Gemini API
- SMTP (Gmail)
- Python Dotenv
- Git
- GitHub

---

## 📂 Project Structure

```
AI-Daily-News-Automation/
│
├── main_ai.py
├── news_client.py
├── content_generator.py
├── send_email.py
├── requirements.txt
├── .env.example
├── README.md
└── daily_ai_script_YYYY-MM-DD.md
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/rsaikeerthi31/AI-Daily-News-Automation.git
```

Go to the project folder

```bash
cd AI-Daily-News-Automation
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file.

```env
NEWS_API_KEY=your_news_api_key
GEMINI_API_KEY=your_gemini_api_key

EMAIL_ADDRESS=your_email@gmail.com
EMAIL_PASSWORD=your_google_app_password
```

---

## ▶️ Run

```bash
python main_ai.py
```

---

## 📧 Output

The application will:

- Fetch the latest AI news
- Generate a Markdown report
- Save the report locally
- Send the report via Gmail

---

## 📸 Sample Output

```
Fetching AI news from Hacker News...
Found 10 AI articles.
Generating report...

Email sent successfully!
```

---

## 📌 Future Improvements

- HTML email support
- Daily scheduling
- Better AI summaries
- GitHub Actions automation
- Web dashboard

---

## 👩‍💻 Author

**Sai Keerthi**

GitHub:
https://github.com/rsaikeerthi31
