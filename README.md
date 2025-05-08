
# 🎬 IMDb Movie Recommendation System (2024)

This project is a content-based movie recommender system that suggests similar movies based on storyline input. It uses web scraping (Selenium), Natural Language Processing (TF-IDF & Cosine Similarity), and a Streamlit-powered interface.

---

## 📌 Project Description

The **IMDb Movie Recommendation System (2024)** is a content-based movie recommender tool that suggests similar movies based on a given storyline. This project combines data scraping, natural language processing (NLP), and machine learning to deliver relevant movie suggestions through an interactive web application.

The core idea is to extract movie data—specifically titles and plot summaries—from IMDb’s 2024 movie listings using **Selenium**. This scraped data is stored in a structured CSV file for further processing. Each movie storyline undergoes text preprocessing to remove noise such as punctuation and stop words. Then, using the **TF-IDF (Term Frequency-Inverse Document Frequency)** technique, the plot summaries are transformed into numerical vectors representing the importance of each word within the context of all storylines.

To generate recommendations, the system uses **cosine similarity**, a method that calculates the closeness between the input storyline and existing movie summaries. The five most similar movies are identified based on the highest similarity scores.

The entire recommendation logic is encapsulated in Python functions, and the user interface is built with **Streamlit**, making it simple and intuitive to use. Users can input any storyline, and within seconds, the app will return five movie titles along with their corresponding summaries, all ranked by relevance to the input.

This project demonstrates practical skills in **web scraping, NLP, machine learning**, and **frontend development**. It also emphasizes modular code design, ensuring scalability and maintainability. With its real-world use case in the entertainment domain, it’s ideal for movie enthusiasts and a solid example of how AI can enhance content discovery.

---

### 🔧 Key Features:
- Extracts 2024 movie data from IMDb using Selenium
- Preprocesses and vectorizes text using TF-IDF
- Computes similarity using cosine distance
- Returns top 5 storyline-based movie recommendations
- User-friendly Streamlit interface

---

### 🧠 Use Case:
Type in a short movie plot (e.g., "A boy discovers his magical powers"), and the app will recommend five similar movies released in 2024 with brief descriptions.
