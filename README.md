# Email Spam Classification 

 A machine learning-based email spam classification system using Logistic Regression. It preprocesses email content with TF-IDF and achieves high accuracy in detecting spam. The model is deployed as a Streamlit app for easy testing and interaction.


### **Project Overview:**
The system uses the **Logistic Regression** model, built and trained on email data. It preprocesses the raw email text using **TF-IDF** to extract meaningful features, making the classifier capable of achieving impressive performance in detecting spam. With an accuracy of **94.32%**, the model is fine-tuned for precision and recall, reducing false positives and negatives.

### **Key Features:**
- **Input**: Raw email text (message content).
- **Output**: Prediction label ("Spam" or "Not Spam").
- **Preprocessing**: The raw email text is transformed into numerical features using **TF-IDF Vectorizer**, making it ready for model input.
- **Model**: **Logistic Regression** optimized for high precision and recall on imbalanced datasets.
- **Performance**: **94.32% accuracy**, with strong precision and recall, ensuring minimized errors.

### **Logistic Regression Model:**
Logistic Regression is a binary classifier that predicts the probability of a particular outcome (spam or not spam). It uses the **sigmoid function** to transform predicted values into a range of 0 to 1, which is then used to classify the email.

#### **Why Logistic Regression?**
- **Efficiency**: It is computationally light and quick to train, making it ideal for real-time classification.
- **Interpretability**: The model's coefficients are easy to interpret, giving insights into which features are most influential in the classification process.
- **Scalability**: Works well with large datasets when combined with efficient feature extraction like **TF-IDF**.

### **Technologies Used:**
- **Python**: Programming language.
- **Scikit-learn**: For building and training the Logistic Regression model.
- **Streamlit**: For creating the web-based interface for deploying the model.
- **Pandas**: For data handling and manipulation.
- **Numpy**: For numerical operations.
- **TF-IDF**: For transforming text data into numerical format suitable for the model.

### **Installation and Setup:**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/email-spam-classification.git
   ```
2. Navigate into the project folder:
   ```bash
   cd email-spam-classification
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Streamlit app:
   ```bash
   streamlit run Streamlit_app.py
   ```


### Deployed App

<br>

![Screenshot 2024-11-26 223746](https://github.com/user-attachments/assets/d398355f-1cd1-4e90-a1cd-7009f72096d1)

![Screenshot 2024-11-26 223803](https://github.com/user-attachments/assets/f828adb0-36ec-430f-9082-faac1dfca888)

![Screenshot 2024-11-26 223812](https://github.com/user-attachments/assets/9c55d6ab-48f1-482a-9cb5-d8a22b012ecd)


![Screenshot 2024-11-26 223825](https://github.com/user-attachments/assets/316c3f5e-f6b9-453a-aedd-724f9b39a1a8)

![Screenshot 2024-11-26 224126](https://github.com/user-attachments/assets/88202802-9ff3-466b-8bc8-420f42c0bc18)



### **Contributing:**
Feel free to fork this project and make contributions. Pull requests are welcome!
