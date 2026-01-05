# 🌱 Soil Type Detection Web App

This is a **Streamlit-based web application** for predicting soil types from images using a trained **ResNet50 deep learning model**. Users can upload a soil image from their local system or provide a Google Drive / Dropbox link to an image, and the app will predict the soil type along with confidence.

---

## **Features**

- **Secure login system** with username/password.
- Upload soil images **from local system** or via **external links** (Google Drive / Dropbox).
- **ResNet50-based CNN model** for accurate soil classification.
- Displays **predicted soil type** and **confidence score**.
- Built using **Streamlit**, easy to deploy on **Streamlit Cloud**.

---


## **Getting Started**

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/soil-detection-app.git
cd soil-detection-app
```


### **2. Install Dependencies**
Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```
Install required packages:
```
pip install -r requirements.txt

```
### **3. Add Model & Labels**
Make sure the following files are present in the project folder:
soil_resnet50_model.keras → Trained ResNet50 model
class_labels.json → Mapping of class indices to soil type labels


### **4. Run the App Locally**
```bash
streamlit run soil_detection_app.py
```
Open the URL displayed in your terminal (usually http://localhost:8501)
Login with:
```bash
Username: admin
Password: 1234
```
## Credits
Developed by Shubham Srivastava
Model trained using TensorFlow & Keras
Built with Streamlit for rapid deployment

