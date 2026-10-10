# 🎯 AI Sentiment Analyzer

A Python tool that reads customer reviews, cleans the data, and uses a real AI model to classify each review as **Positive** or **Negative**. It then generates a summary report and saves the results to a new file.

This project was built as a capstone project to apply real-world skills in data cleaning, AI models, and reporting, all in one complete pipeline.

---

## 📌 What This Project Does

1. Loads a CSV file of customer reviews
2. Cleans the data (removes missing reviews, trims extra spaces)
3. Runs each review through a Hugging Face AI sentiment model
4. Adds `sentiment` and `confidence` columns to the data
5. Prints a summary report (total reviews, % positive/negative, most confident positive review) 
6. Saves the final results to a new CSV file

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** (for data handling)
- **Hugging Face Transformers** (for AI sentiment analysis)
- **Google Colab** (for running the notebook)

---

## 📂 Files in This Repository

| File | Description |
|------|-------------|
| `My_Capstone_Project.ipynb` | The main notebook with all the code |
| `reviews.csv` | The raw input data (customer reviews) |
| `reviews_with_sentiment.csv` | The final output with sentiment results |

---

## 📊 Example Output
==== Sentiment Analysis Report ====
Total reviews analyzed: 5

Positive: 2 (40%)
Negative: 3 (60%)

Most confident positive review:
I loved the food and the service was great

---

## 🚀 How to Run This Project

1. Open the notebook `My_Capstone_Project.ipynb` in Google Colab
2. Upload `reviews.csv` to the Colab environment
3. Run each cell from top to bottom
4. Check the final report printed in the output
5. Download the new file `reviews_with_sentiment.csv` with your results

---

## 💡 What I Learned

- How to clean and prepare real-world data using Pandas
- How to use a pre-trained AI model (Hugging Face Transformers) for sentiment analysis
- How to build a complete data pipeline: Load → Clean → Analyze → Summarize → Save
- How to turn raw data into a clear, readable report

---

## 👩‍💻 About Me

Built by **Zimal Yousuf**, BSCS student.
GitHub: [ZimalYousuf3](https://github.com/ZimalYousuf3)
