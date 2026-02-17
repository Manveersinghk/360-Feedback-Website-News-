# 360 News Feedback

**360 News Feedback** is a web application that delivers real-time news using a public News API and enhances credibility through **community-driven feedback**.
Users can read the latest news, share their opinions, rate authenticity, and view feedback from other readers — creating a transparent and trust-based news experience.

---

## 🚀 Features

* **Live News Fetching**

  * Displays latest news articles using a News API
  * Category-based and real-time updates

* **User Feedback System**

  * Users can submit feedback on each news article
  * Rate credibility or share opinions

* **Community Transparency**

  * All feedback is visible to other users
  * Helps readers judge the reliability of news

* **Database Integration**

  * Stores user feedback securely using MySQL
  * Persistent and scalable data management

* **Responsive Interface**

  * Built with HTML, CSS, and JavaScript
  * Clean and user-friendly design

---

## 🛠️ Tech Stack

| Technology | Purpose                       |
| ---------- | ----------------------------- |
| PHP        | Backend logic & API handling  |
| MySQL      | Database for storing feedback |
| HTML       | Structure of the web pages    |
| CSS        | Styling and layout            |
| JavaScript | Client-side interactivity     |
| News API   | Fetching real-time news data  |

---

## 📂 Project Structure

```
360-news-feedback/
│
├── index.php          # Main homepage displaying news
├── config.php         # Database connection
├── fetch_news.php     # API request handling
├── submit_feedback.php # Stores user feedback
├── styles.css         # Styling
├── script.js          # Frontend interactions
└── database.sql       # SQL file for table creation
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**

```
git clone https://github.com/your-username/360-news-feedback.git
```

2. **Move project to server directory**

* For XAMPP: `htdocs/`
* For WAMP: `www/`

3. **Create Database**

* Open phpMyAdmin
* Create a database: `news_feedback`
* Import `database.sql`

4. **Configure Database**

* Open `config.php`
* Update:

```php
$host = "localhost";
$user = "root";
$password = "";
$dbname = "news_feedback";
```

5. **Add News API Key**

* Open `fetch_news.php`
* Replace with your API key:

```php
$apiKey = "YOUR_API_KEY";
```

6. **Run the Project**

* Start Apache & MySQL
* Open browser:

```
http://localhost/360-news-feedback
```

---

## 📊 How It Works

1. News articles are fetched from the API.
2. Users read the article and submit feedback.
3. Feedback is stored in MySQL.
4. Other users can view community responses.
5. Collective feedback helps determine the **credibility of the news**.

---

## 🎯 Objective

In the era of misinformation, this project aims to:

* Increase transparency in news consumption
* Enable community-based credibility checks
* Encourage responsible and informed readership

---

## 🔮 Future Improvements

* User authentication system
* Like/Dislike or credibility score system
* AI-based fake news detection
* Sentiment analysis on feedback
* Admin dashboard for moderation

---

## 📜 License

This project is for educational and personal use. You are free to modify and improve it.

---

## 👨‍💻 Author

**Manveer Singh**
B.Tech CSE | Web & AI Enthusiast
