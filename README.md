# 🌿 Plant Disease Detection Project

An AI-powered web application that uses deep learning to detect and diagnose plant diseases from leaf images. This system helps farmers, agricultural experts, and gardening enthusiasts identify plant diseases early and take timely action to protect their crops.

![Plant Disease Detection](https://img.shields.io/badge/AI-Plant%20Disease%20Detection-green)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red)

🔗 **Live Demo:** [https://deep-learning-project-5vkxrfs9ouffalnpzefqtm.streamlit.app/](https://deep-learning-project-5vkxrfs9ouffalnpzefqtm.streamlit.app/)

---

## 🚀 Features

- 🌱 **Image Upload**: Upload plant leaf images for instant disease detection
- 🤖 **Deep Learning Model**: Custom CNN architecture built from scratch using TensorFlow/Keras
- 📊 **Disease Diagnosis**: Accurate identification of various plant diseases
- 💡 **Treatment Recommendations**: Provides disease details and suggested treatments
- 💻 **User-Friendly Interface**: Built with Streamlit for seamless user experience
- ☁️ **Cloud Deployment**: Deployed on AWS EC2 for global accessibility
- 🔒 **Secure & Scalable**: Production-ready deployment architecture

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| **Frontend** | Streamlit |
| **Backend** | Python 3.8+ |
| **ML Framework** | TensorFlow/Keras |
| **Model Architecture** | Custom Convolutional Neural Network (CNN) |
| **Deployment** | AWS EC2, Vercel |
| **Data Processing** | NumPy, OpenCV |

---

## 📂 Project Structure

```
plant_disease_project/
│
├── . devcontainer/                  # Dev container configuration
├── Plant_disease_detection_project/
│   ├── model/
│   │   └── plant_disease_model.keras   # Trained ML model
│   ├── utils/
│   │   └── preprocessing.py            # Image preprocessing functions
│   ├── app.py                          # Streamlit application
│   ├── requirements. txt                # Python dependencies
│   └── README.md                       # Detailed project documentation
└── README.md                           # Main repository documentation
```

---

## 🎯 How It Works

1. **Upload Image**: User uploads a plant leaf image through the web interface
2. **Preprocessing**: Image is preprocessed (resized, normalized) for model input
3. **Prediction**:  CNN model analyzes the image and predicts the disease
4. **Results**: System displays the detected disease with confidence score and treatment recommendations

---

## 🔧 Installation & Setup

### Prerequisites
- Python 3.8 or higher
- pip package manager
- (Optional) Virtual environment tool

### Local Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Himanshu0508Raturi/plant_disease_project.git
   cd plant_disease_project
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   cd Plant_disease_detection_project
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   streamlit run app.py
   ```

5. **Access the app**
   Open your browser and navigate to `http://localhost:8501`

---

## 🧠 Model Details

- **Architecture**: Custom Convolutional Neural Network (CNN)
- **Input**:  RGB plant leaf images
- **Output**: Disease classification with confidence scores
- **Training**: Trained on comprehensive plant disease datasets
- **Performance**: High accuracy in detecting common plant diseases

---

## 📊 Supported Plant Diseases

The model can detect various plant diseases including:
- Bacterial infections
- Fungal diseases
- Viral infections
- Nutrient deficiencies
- Healthy plant classification

*(Specific disease list depends on the training dataset)*

---

## 🌐 Deployment

### AWS EC2 Deployment
The application is deployed on AWS EC2 for scalable and reliable hosting. 

### Vercel Deployment
Frontend interface available at: [https://deep-learning-project-brown.vercel. app](https://deep-learning-project-brown.vercel.app)

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 Future Enhancements

- [ ] Mobile application development
- [ ] Support for more plant species and diseases
- [ ] Multi-language support
- [ ] Real-time disease monitoring dashboard
- [ ] Integration with IoT sensors
- [ ] API for third-party integration

---

## 📜 License

This project is licensed under the MIT License - feel free to use and modify as needed.

---

## 👨‍💻 Author

**Himanshu Raturi**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/himanshu-raturi/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github)](https://github.com/Himanshu0508Raturi)

---

## 🌟 Acknowledgments

- Thanks to the open-source community for various plant disease datasets
- TensorFlow and Keras teams for excellent deep learning frameworks
- Streamlit for the amazing web app framework

---

## 📞 Support

If you encounter any issues or have questions:
- Open an [issue](https://github.com/Himanshu0508Raturi/plant_disease_project/issues)
- Contact via email:  raturihimanshu077@gmail.com

---

⭐ **If you find this project helpful, please consider giving it a star!**

---
