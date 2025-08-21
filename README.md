# Multiple Disease Prediction System

A comprehensive Streamlit web application that uses machine learning models to predict three different diseases: Diabetes, Heart Disease, and Parkinson's Disease.

## 🏥 Features

- **Diabetes Prediction**: Based on 8 health parameters including glucose level, blood pressure, BMI, age, etc.
- **Heart Disease Prediction**: Based on 13 cardiovascular parameters including age, sex, chest pain, blood pressure, cholesterol, etc.
- **Parkinson's Disease Prediction**: Based on 22 voice/acoustic parameters including MDVP features, jitter, shimmer, etc.
- **User-friendly Interface**: Clean, responsive design with input validation and helpful placeholders
- **Real-time Predictions**: Instant results using pre-trained machine learning models

## 🚀 Live Demo

The app is hosted on Streamlit Cloud and can be accessed at:
**[🌐 Live App](https://multiple-disease-prediction-app-app-cahregxftg44s93fd7jfvs.streamlit.app/)**

## 📋 Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Vi1en/multiple-disease-prediction-streamlit-app.git
   cd multiple-disease-prediction-streamlit-app
   ```

2. **Install required packages**
   ```bash
   pip install -r requirements.txt
   ```

## 🎯 Usage

1. **Run the Streamlit app**
   ```bash
   streamlit run app.py
   ```

2. **Open your browser**
   - The app will automatically open at `http://localhost:8501`
   - Navigate between different disease prediction sections using the sidebar

3. **Enter patient data**
   - Fill in the required parameters for the disease you want to predict
   - Click the prediction button to get results
   - All fields accept numeric values only

## 📊 Input Parameters

### Diabetes Prediction
- Number of Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin Level
- BMI
- Diabetes Pedigree Function
- Age

### Heart Disease Prediction
- Age, Sex, Chest Pain types
- Resting Blood Pressure
- Serum Cholesterol
- Fasting Blood Sugar
- Resting ECG results
- Maximum Heart Rate
- Exercise Induced Angina
- ST depression, Slope, Vessels, Thalassemia

### Parkinson's Disease Prediction
- 22 MDVP (Multi-Dimensional Voice Program) parameters
- Jitter and Shimmer measurements
- Various acoustic features

## 🏗️ Project Structure

```
multiple-disease-prediction-streamlit-app/
├── app.py                 # Main Streamlit application
├── requirements.txt       # Python dependencies
├── README.md             # Project documentation
├── .gitignore            # Git ignore file
├── dataset/              # Training datasets
│   ├── diabetes.csv
│   ├── heart.csv
│   └── parkinsons.csv
├── saved_models/         # Pre-trained ML models
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   └── parkinsons_model.sav
└── colab_files_to_train_models/  # Training notebooks
    ├── COLAB_FILE_DIABETES.ipynb
    ├── COLAB_FILE_HEART.ipynb
    └── COLAB_FILE_PARKINSONS.ipynb
```

## 🤖 Machine Learning Models

The application uses pre-trained models saved in pickle format:
- **Diabetes Model**: Logistic Regression classifier
- **Heart Disease Model**: Support Vector Classifier (SVC)
- **Parkinson's Model**: Logistic Regression classifier

## 🚀 Deployment

### Streamlit Cloud (Recommended)
1. Push your code to GitHub
2. Connect your GitHub repository to [Streamlit Cloud](https://streamlit.io/cloud)
3. Deploy automatically

### Local Deployment
```bash
streamlit run app.py --server.port 8501 --server.address 0.0.0.0
```

## 🔧 Customization

- **Add new diseases**: Create new prediction sections following the existing pattern
- **Modify models**: Replace the `.sav` files with your own trained models
- **Update UI**: Modify the Streamlit components in `app.py`

## 📝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Dataset sources: UCI Machine Learning Repository
- Streamlit for the amazing web framework
- Scikit-learn for machine learning capabilities

## 📞 Support

If you have any questions or need help, please open an issue on GitHub.

---

**Note**: This application is for educational and research purposes only. Medical predictions should not replace professional medical advice.
=======
# multiple-disease-prediction-streamlit-app
A comprehensive Streamlit web application for predicting multiple diseases using machine learning
>>>>>>> 1dc8522d6bf2f411185212a1d8acc21d41494a46
