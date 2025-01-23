
# 🍽️ Restaurant Review Sentiment Analysis 🍽️

## 📜 Project Overview

This project uses Natural Language Processing (NLP) to analyze restaurant reviews and determine whether they are **Positive** or **Negative**. It leverages machine learning to classify the sentiment and provides an interactive interface for users to submit their own reviews. The project also calculates the percentage of positive and negative reviews based on the data collected.

### ✨ Features:
- **Sentiment Classification**: Classifies reviews as **Positive** or **Negative** 🟢🔴.
- **User Interaction**: Users can submit their reviews, and the sentiment is predicted instantly 💬🔍.
- **Data Storage**: Reviews and their sentiments are stored for future analysis 📊💾.
- **Sentiment Percentages**: Displays the percentage of positive and negative reviews based on collected data 📈.

---

## 🔧 Technologies Used

- **Programming Language**: Python 🐍
- **Libraries**:
  - `pandas`: For data handling 📊
  - `sklearn`: For machine learning and sentiment analysis 🧠
  - `matplotlib` & `seaborn`: For visualizing results 📉
  - `wordcloud`: For generating word clouds 🌈
  - `gradio`: For creating the interactive web interface 🌐
  - `ipywidgets`: For interactive widgets 🎛️

---

## ⚙️ How It Works

1. **Data Input**: Users can input restaurant reviews manually or choose from sample reviews 🍴📝.
2. **Sentiment Analysis**: The review is processed using a pre-trained model that classifies it as either Positive or Negative 💡.
3. **Output**: The sentiment prediction is displayed, and the review is stored for future reference 💾.
4. **Percentage Calculation**: After multiple reviews are submitted, the project calculates and displays the percentage of Positive vs Negative reviews 📊.
5. **Interactive Interface**: The project uses Gradio and ipywidgets to provide a seamless user experience 🖥️.

---

## 🛠️ Installation Instructions

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <project_folder>
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the project:
   ```bash
   python sentiment_analysis.py
   ```

---

## 🧑‍💻 Usage

### Example Reviews:
- **Review**: "The food was delicious and the service was excellent!"
  - **Predicted Sentiment**: Positive ✨
  
- **Review**: "Terrible experience, food was cold and service was slow."
  - **Predicted Sentiment**: Negative 💔

### Features:
- **Submit your review**: Type your review in the input box and see the sentiment prediction 🔍.
- **Sample Reviews**: Click on sample review buttons to quickly load reviews and see the predictions 🍽️.
- **Sentiment Breakdown**: The interface shows the percentage of positive and negative reviews 📈.
- **Review History**: Your submitted reviews and their sentiment classification are displayed for easy reference 📝.

---

## 💻 Gradio Interface

The project includes an intuitive interface created with **Gradio**. Here’s how it’s structured:

1. **Restaurant Details**: Information about the restaurant and cuisine 🍕🍔🍣.
2. **User Reviews**: Input a review, select from sample reviews, or see sentiment analysis results 🌟.
3. **Review History**: See a history of your submitted reviews and the sentiment breakdown 📜.
4. **Sentiment Percentages**: Displays the percentage of Positive vs Negative reviews based on the submitted data 📊.

---

## 📊 Sample Output

- **Predicted Sentiment**: Positive or Negative 🟢🔴
- **Sentiment Percentages**:
  - **Positive Reviews**: 60.00% 👍
  - **Negative Reviews**: 40.00% 👎

---

## 🛠️ Functions & Modules

- **`predict_sentiment(review)`**: Processes the input review and predicts whether it’s Positive or Negative.
- **`save_review(review, sentiment)`**: Saves the review and its sentiment, and updates the sentiment percentages.
- **`calculate_percentages()`**: Calculates the percentage of Positive and Negative reviews based on the stored reviews.

---

## 📈 Example Usage

1. Input a review into the text box or choose a sample review using the provided buttons.
2. The system will classify the sentiment as **Positive** or **Negative**.
3. Your review will be saved, and the sentiment percentages will be updated.

---

## 📝 Contributing

Feel free to fork the repository and contribute! Here’s how you can get started:

1. Fork the repository.
2. Create your branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a pull request to merge your changes.

---

## 🛡️ License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 💡 Future Enhancements
- **Multilingual Support**: Add sentiment analysis support for multiple languages 🌍.
- **Sentiment Visualization**: Improve sentiment visualization with word clouds and more charts 🧑‍🎨.
- **Model Improvement**: Experiment with different models for better accuracy 🧠.

---

## 🌟 Demo
---
![Image](https://github.com/user-attachments/assets/70741939-f50d-480f-af7c-f35b052d2710)


![Image](https://github.com/user-attachments/assets/facff9cb-56a7-414e-bce1-182e341d3a9a)
