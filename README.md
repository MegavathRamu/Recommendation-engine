# 🏨 Hotel Recommendation System

This project analyzes hotel booking data and builds a **hybrid recommendation engine** using **Collaborative Filtering**, **TF-IDF**, and **LLMs** (Large Language Models) for personalized suggestions and explanations.



---

## 📌 Project Features

- Descriptive statistics of hotel booking data
- Null value detection and handling
- Exploratory data analysis with Pandas
- Recommendation engine using:
  - 🔁 **Collaborative Filtering** (user-item similarity)
  - 📄 **TF-IDF (Term Frequency-Inverse Document Frequency)** for hotel metadata text
  - 🤖 **LLM-based ranking or explanation generation**

---

## 🔍 How It Works

1. **Data Preprocessing**:
   - Load and clean booking data (missing values, duplicates)
   - Extract relevant features (user ID, hotel description, ratings, etc.)

2. **Collaborative Filtering**:
   - Identify similar users or hotels based on booking/rating history
   - Recommend hotels based on what similar users have booked

3. **TF-IDF Content Analysis**:
   - Convert hotel descriptions into vectors using `TfidfVectorizer`
   - Find content-based similarities (e.g., similar amenities, location keywords)

4. **LLM Integration** (Optional):
   - Use an LLM (like GPT) to:
     - Explain why a hotel is recommended (e.g., “Because you liked beachfront hotels with free breakfast”)
     - Rank or rephrase results for user-friendly interaction

---

5.*****Results*****
![Screenshot 2025-07-06 141427](https://github.com/user-attachments/assets/06c27772-5b9f-47c2-a2e5-bf6849814765)
![Screenshot 2025-07-06 141358](https://github.com/user-attachments/assets/3d33623f-6e4f-4d83-b88d-338bcb7d15af)
![Screenshot 2025-07-06 141332](https://github.com/user-attachments/assets/fb071ad7-d855-4ef7-bb1f-69831d6b8c73)



