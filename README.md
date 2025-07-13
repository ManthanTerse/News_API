
# 🗞️ News Fetcher using Python and NewsAPI

This is a simple command-line Python project that fetches the latest news based on the user's query using the [NewsAPI](https://newsapi.org/).

## 📌 Features

- Takes user input for a news topic (e.g., technology, sports, politics).
- Uses the `requests` library to fetch real-time articles from NewsAPI.
- Displays:
  - Article number
  - Title
  - Link to the full news article
- Easy to understand!

## 🛠️ Requirements

- Python 
- `requests` library

Install dependencies using:

```bash
pip install requests
```

## 🚀 How to Run

```bash
python news_fetcher.py
```

You'll be prompted with:

```
What type of news are you interested in today? :
```

Enter your topic (e.g., `AI`, `sports`, `climate change`), and it will display the latest articles.

## 📄 Example Output

```
What type of news are you interested in today? : space

1
NASA prepares to launch new telescope into deep space
https://www.example.com/article1

************

2
SpaceX sets new record with 12th rocket launch this month
https://www.example.com/article2

************
```

## 🔐 API Key

To run this project, you need a **free API key** from [https://newsapi.org/](https://newsapi.org/).  
Replace the `api` variable in the script with your API key:

```python
api = "your_api_key_here"
```

## 📁 File Structure

```
.
├── news_api.py     # Main Python script
└── README.md           # Project README file
```

## 📚 Concepts Used

- HTTP requests with `requests`
- JSON handling in Python
- API integration
- Command-line interaction

---

👨‍💻 Created as part of a Python learning journey.

