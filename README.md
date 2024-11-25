# **Customer Churn Prediction Using ANN**

![Project Banner](https://via.placeholder.com/800x200?text=Customer+Churn+Prediction)

This project leverages an Artificial Neural Network (ANN) to predict customer churn based on historical data. The system is built using Python and Streamlit for an interactive web application and TensorFlow for the ANN model.

---

## **Overview**

Customer churn is a critical metric for businesses as it directly impacts revenue and growth. This project aims to predict which customers are likely to churn using machine learning. By identifying such customers, businesses can proactively engage them and reduce churn rates.

This repository includes:
- **Data preprocessing pipeline**
- **ANN model training and evaluation**
- **Interactive Streamlit app for predictions**

---

## **Features**

- **Interactive Web App**: A user-friendly interface to upload data, visualize trends, and get predictions.
- **Accurate Predictions**: Uses an optimized ANN model for high accuracy.
- **Extensible Codebase**: Easily adaptable for different datasets or domains.
- **Streamlit Deployment**: Runs seamlessly on both local systems and cloud platforms.

---

## **Technologies Used**

- **Python**: Core programming language.
- **TensorFlow**: For building and training the ANN model.
- **Streamlit**: For creating the interactive user interface.
- **Pandas & NumPy**: For data preprocessing and manipulation.
- **Matplotlib & Seaborn**: For data visualization.

---

## **Installation**

### Prerequisites
- Python 3.10 or later
- pip (Python package manager)
  ![Screenshot 2024-11-25 213153](https://github.com/user-attachments/assets/cd5ca50f-9535-4d24-94ca-80dbbb7ccf8a)
  ![Screenshot 2024-11-25 213207](https://github.com/user-attachments/assets/43a10207-4e85-4aeb-b0a8-0731e10b40b5)



### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/ayushi-mahariye/Customer-Churn-Prediction-using-ANN.git
   cd Customer-Churn-Prediction-using-ANN
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   streamlit run app.py
   ```

---

## **Usage**

1. **Prepare Your Data**:
   - Upload a CSV file with the required features.
   - Ensure columns align with the model’s input schema.

2. **Explore the App**:
   - Use the interactive dashboard to visualize data insights.
   - Get predictions on customer churn probabilities.

---

## **Project Structure**

```
Customer-Churn-Prediction-using-ANN/
├── app.py                  # Main Streamlit application
├── requirements.txt        # Dependencies for the project
├── models/                 # Saved model files
├── data/                   # Sample datasets for testing
├── utils/                  # Utility scripts for data preprocessing and visualization
├── README.md               # Project documentation (this file)
```

---

## **Model Overview**

The ANN model comprises:
- Input Layer: Takes in preprocessed customer features.
- Hidden Layers: Two dense layers with ReLU activation.
- Output Layer: Single neuron with sigmoid activation for binary classification.

---

## **Dataset**

The model is trained on a customer dataset with features like:
- **Customer Demographics**: Age, Gender, etc.
- **Subscription Details**: Tenure, Monthly Charges, Contract Type.
- **Engagement Metrics**: Internet Service, Payment Method, etc.


## **Future Enhancements**

- Integrate advanced models like Gradient Boosting or Random Forest for comparison.
- Add functionality for batch processing of predictions.
- Implement a feedback loop to fine-tune the model with real-world data.
  

---
## **Deployment**
 Deployment Link -- https://customer-churn-prediction-using-ann-jutfjdm8gsmypbwyp83h3g.streamlit.app/



## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## **Contact**

**Ayushi Mahariye**  
