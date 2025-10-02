# 🧠 Stress Level Predictor

An AI-powered stress management companion that predicts and helps optimize stress levels based on various psychological and lifestyle factors.

## 🎯 Features

- Real-time stress level prediction
- Personalized recommendations
- Scenario testing and optimization
- Easy-to-use interface
- Dark/Light mode toggle

## 🚀 Quick Start

1. Clone the repository:
```bash
git clone https://github.com/yourusername/AURA_Stress-Level-Predictor.git
cd AURA_Stress-Level-Predictor
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
streamlit run app.py
```

## 📊 Input Features

The model considers various factors including:
- Psychological factors (anxiety, self-esteem, depression)
- Physical health indicators (headache, blood pressure, sleep quality)
- Environmental factors (noise level, living conditions, safety)
- Academic factors (performance, study load, teacher-student relationship)
- Social factors (social support, peer pressure, bullying)

## 🛠️ Technical Details

- Built with Streamlit
- Uses Random Forest model for predictions
- Includes optimization algorithm for stress reduction suggestions
- Supports both dark and light themes

## 📁 Project Structure

```
AURA_Stress-Level-Predictor/
├── app.py                 # Main application file
├── model_rf.joblib        # Trained model
├── feature_order.json     # Feature configuration
├── requirements.txt       # Project dependencies
├── README.md             # Documentation
└── .gitignore            # Git ignore file
```

## 💡 Usage

1. Input your current psychological and lifestyle factors using the sliders
2. Click "Predict" to see your stress level prediction
3. Use the "Optimize Stress" feature to get personalized recommendations
4. Apply suggested changes and track improvements

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Authors

- Your Name (@yourusername)

## 🙏 Acknowledgments

- Special thanks to contributors and supporters
- Built using Streamlit and scikit-learn
