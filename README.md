# **Image Classification with MobileNetV2 and CIFAR-10**

Welcome to the Image Classification App! This Streamlit application integrates the power of deep learning models like MobileNetV2 (trained on ImageNet) and a custom-trained CIFAR-10 model to provide real-time image classification with a sleek and intuitive interface.

---

## 🌟 **Highlights of Key Features**  

### 🧠 **Dual Model Support**  
- **MobileNetV2 (ImageNet)**: A robust model trained on the ImageNet dataset to identify 1,000+ classes like objects, animals, and vehicles.  
- **Custom CIFAR-10 Classifier**: Specialized to categorize images into 10 familiar categories, including airplanes, automobiles, and birds, using the CIFAR-10 dataset.

---

### 🎛️ **Intuitive & User-Friendly Interface**  
- **Dynamic Model Switching**: Effortlessly toggle between models using the interactive sidebar.  
- **Real-Time Results**: Upload your image and get instant predictions, complete with confidence scores!

---

### 🎓 **Learn & Apply**  
- **Deep Learning Insights**: Discover the inner workings and capabilities of state-of-the-art neural networks.  
- **Practical Applications**: Explore use cases for image classification across diverse industries.

---

## 🚀 **Let's Get Started**  
### **Pre-requisites**
- Python 3.7 or later
- A web browser

### **How to Run the App**
- **1. Clone this repository:**  
   ```bash  
   git clone https://github.com/Chaithra3-6/Project1-ML_model_for_image_classification.git
   cd Project1-ML_model_for_image_classification
   ```
- **2. Create and activate a virtual environment:**(optional)
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```
- **3. Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```
- **4. Start the Streamlit app:**
   ```bash
   streamlit run app.py
   ```
- **5. Open the app:** The app will open in your default web browser. If not, navigate to http://localhost:8501/
  
---

## **File Structure**
- **cifar10-train.py:** Script for training and saving the CIFAR-10 model.
- **model111.h5:** Pre-trained CIFAR-10 model file used for making predictions in the app.
- **my-app.py:** Main Streamlit application file for interactive image classification.
- **requirements.txt:** List of required Python packages.

---

## **Usage**

### MobileNetV2 (ImageNet)

-  Upload an image (JPG/PNG).

-  View the top 3 predictions with confidence scores.

-  Ideal for recognizing everyday objects, animals, and vehicles.

### CIFAR-10 Model

-  Upload an image (JPG/PNG) resized to 32x32 pixels.

-  Receive a single class prediction with a confidence score.

-  Categories include: {Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship,Truck}

---

## **Contributing**
 Feel free to fork the repository, open issues, or submit pull requests.

 ---

## **Acknowledgements**

- **Streamlit:** For the amazing web app framework.

- **TensorFlow:** For powering the deep learning models.

- **Pillow**: For image handling.

- **Numpy and Matplotlib:** For numerical and data visualization support.


   



