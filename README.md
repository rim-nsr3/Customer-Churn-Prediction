# Customer Churn Prediction AI Support

An AI support software that predicts customer churn based on machine learning models and provides personalized explanations and email recommendations to prevent churn.

## Features

- 🔮 Predict customer churn based on machine learning models
- 💡 Generate personalized explanations for churn predictions
- 📧 Send personalized email recommendations to customers
- 📊 Multiple ML models support (XGBoost, Random Forest, etc.)
- 🎯 Real-time prediction capabilities

## Tech Stack

- **Frontend Framework**: Streamlit
- **AI/ML**:
  - OpenAI LLMs for explanations and recommendations
  - XGBoost, Naive Bayes, Random Forest
  - Decision Tree, SVM, KNN
- **Data Processing**:
  - Pandas for data manipulation
  - NumPy for numerical computations
  - Scikit-learn for ML operations

## Prerequisites

Ensure you have Python 3.8+ installed. Install the required dependencies:

```bash
pip install -r requirements.txt
pip install streamlit
```

### Required Libraries
- pandas
- numpy
- scikit-learn
- xgboost
- joblib
- streamlit
- openai

## Configuration

### API Keys
Create a `.env` file in the root directory and add your API key:

```env
GROQ_API_KEY=your_api_key_here
```

Replace `your_api_key_here` with your actual Groq API key.

## Running the Application

### Development Server

Start the Streamlit development server:

```bash
streamlit run main.py
```

The application will automatically open in your default web browser at `http://localhost:8501`

### Production Build

To create and run a deployable build:

```bash
npm install
npm run build
npm start
```

The production build will be created in the `build` directory.

## Roadmap

### Upcoming Features
- [ ] Enhanced ML model training and predictions
- [ ] Real-time customer data integration
- [ ] Improved UI/UX features
- [ ] Extended API capabilities
- [ ] Additional model support

## Contributing

We welcome contributions! Please feel free to submit a Pull Request 😄!
