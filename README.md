# 🌟 NewsGenius: AI-Powered Article Summarizer

## 💡 About the Project
NewsGenius is an AI-powered web application that extracts and summarizes news articles from any given URL. It also provides sentiment analysis based on the article's content.

## 🚀 Features
- Extracts and summarizes news articles from any URL.
- Provides sentiment analysis (Positive, Negative, or Neutral).
- Displays the article title, author(s), publication date, and top image.
- User-friendly dark theme UI with a theme toggle option.
- Built with Flask and NLP tools like `newspaper3k` and `TextBlob`.

---

## 🛠️ Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask (Python)
- **NLP Libraries**: `newspaper3k`, `TextBlob`, `nltk`
- **Other Dependencies**: `validators`, `requests`

---

## 📦 Installation & Setup

### **Step 1: Clone the Repository**
```sh
git clone https://github.com/your-username/NewsGenius.git
cd NewsGenius
```

### **Step 2: Create and Activate a Virtual Environment**
```sh
# On Windows
python -m venv venv
venv\Scripts\activate

# On Mac/Linux
python3 -m venv venv
source venv/bin/activate
```

### **Step 3: Install Dependencies**
```sh
pip install -r requirements.txt
```

### **Step 4: Run the Application**
```sh
python app.py
```
or use **Gunicorn** for production:
```sh
gunicorn app:app
```

### **Step 5: Open the Application**
Visit `http://127.0.0.1:5000/` in your browser.


---

## ⚙️ Project Structure
```
NewsGenius/
│── static/               # CSS and JS files
│── templates/            # HTML templates
│   ├── index.html        # Main UI page
│── app.py                # Main Flask backend
│── requirements.txt      # Python dependencies
│── README.md             # Documentation
```

---

## 🤖 Dependencies
Make sure you have the following installed:
- Python 3.7+
- Flask
- newspaper3k
- TextBlob
- NLTK
- validators
- requests

Install them using:
```sh
pip install flask newspaper3k textblob nltk validators requests
```

---

## 🛠️ Deployment (Render)
This project is already deployed on **Render**:  
🔗 **[Live Demo](https://newsgenius2.onrender.com/)**

To deploy it yourself:
1. Push your code to GitHub.
2. Create a **Render Web Service**.
3. Set the **Start Command** to:
   ```sh
   gunicorn app:app
   ```
4. Deploy and enjoy!

---

## 👨‍💻 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

---

## 📝 License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 📱 Contact
For questions or feedback, reach out:
- ✉️ Email: `your-email@example.com`
- 🔗 GitHub: [your-username](https://github.com/your-username)
