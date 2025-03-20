# News Summarization and Text-to-Speech Application

🚀 **Akaike Internship Assignment**  

## **🔹 Project Overview**  
This is a web-based application that extracts key details from multiple news articles related to a given company, performs sentiment analysis, conducts comparative analysis, and generates a **text-to-speech (TTS) output in Hindi**.

## **🛠 Features**  
✅ **News Extraction:** Extracts and displays 10+ news articles using web scraping (BeautifulSoup).  
✅ **Sentiment Analysis:** Classifies each article as Positive, Negative, or Neutral using **Hugging Face models**.  
✅ **Comparative Analysis:** Compares sentiment across articles and highlights variations.  
✅ **Text-to-Speech (TTS):** Converts the summarized content into Hindi speech using **gTTS**.  
✅ **User Interface:** Built using **Gradio** for an easy-to-use web interface.  
✅ **API Support:** Backend developed using **Flask APIs**.  
✅ **Deployment:** Hosted on **Hugging Face Spaces**.  

---

## **🚀 How to Install and Run the Application**  

### **🔹 1. Clone the Repository**  
```sh
git clone https://github.com/JK5261/news-summarization-project.git
cd news-summarization-project
```

### **🔹 2. Install Dependencies**  
```sh
pip install -r requirements.txt
```

### **🔹 3. Run the Application**  
```sh
python app.py  
```

---

## **📌 Project Structure**  
```
📁 news-summarization-project  
│── app.py  (Main Flask application)  
│── api.py  (Handles API requests)  
│── utils.py  (Helper functions like web scraping, sentiment analysis, and TTS)  
│── requirements.txt  (List of dependencies)  
│── README.md  (Documentation file)  
│── deployment_link.txt  (Hugging Face Spaces ka link)  
```

---

## **📊 API Endpoints (Flask Backend)**  
| Method | Endpoint | Description |  
|--------|----------|-------------|  
| `POST` | `/extract-news` | Fetches news articles based on the company name |  
| `POST` | `/analyze-sentiment` | Performs sentiment analysis on extracted articles |  
| `POST` | `/generate-tts` | Generates Hindi speech output of the sentiment report |  

---

## **🧠 Models Used**  
1️⃣ **News Summarization:** Hugging Face transformer model for text summarization.  
2️⃣ **Sentiment Analysis:** Pre-trained model from Hugging Face to classify sentiments.  
3️⃣ **Text-to-Speech (TTS):** **gTTS (Google Text-to-Speech)** for Hindi audio generation.  

---

## **🌐 Deployment Link**  
👉 **Live Demo:** [Hugging Face Spaces](https://huggingface.co/spaces/Kishorjante/Gardio/tree/main)  

---

## **⚠️ Assumptions & Limitations**  
- The application scrapes news only from **non-JS websites**.  
- Sentiment analysis accuracy depends on data quality.  
- TTS pronunciation may have minor errors.  

---

## **📝 Submission Details**  
🔹 **GitHub Repository:** [news-summarization-project](https://github.com/JK5261/news-summarization-project/tree/main)  
🔹 **Deployment Link:** [Hugging Face Spaces](https://huggingface.co/spaces/Kishorjante/Gardio/tree/main)   

---

## **📌 Author**  
👤 **Kishor Jante**  
📧 **jantekishor38@gmail.com**  
📍 Pune, India  

---



