🧠 Handwritten Digit Recognition using Deep Learning

This project is a Handwritten Digit Recognition web application built using TensorFlow (Keras) and Streamlit. Users can upload an image of a handwritten digit (0–9), and the trained deep learning model predicts the digit.

🚀 Features

- Upload handwritten digit images (.png)
- Automatic image preprocessing
- Real-time digit prediction
- Simple and interactive Streamlit UI
- CNN-based trained model

🛠️ Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Pillow (PIL)
- Streamlit

📂 Project Structure

handwritten-digit-recognition/
├── app.py
├── handwritten_digit_rec.h5
├── README.md
└── requirements.txt

🧪 Model Details

- Input Size: 28 × 28
- Image Type: Grayscale
- Model: Convolutional Neural Network (CNN)
- Dataset: MNIST or similar handwritten digit dataset

⚙️ Image Preprocessing Steps
1. Convert image to grayscale
2. Invert image colors
3. Resize image to 28×28
4. Normalize pixel values (0–1)
5. Reshape image for CNN input

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/your-username/handwritten-digit-recognition.git
cd handwritten-digit-recognition

Install dependencies:

pip install -r requirements.txt
Run the Streamlit app:
streamlit run app.py

📷 Input Format
- Image type: PNG
- Content: Single handwritten digit (0–9)
- Best results with dark digit on light background

📊 Output
The application displays the predicted digit.
Example:
Predicted Class: 5

📦 requirements.txt

streamlit
tensorflow
numpy
pillow

🔮 Future Enhancements

- Add drawing canvas for digit input
- Show prediction confidence score
- Support additional image formats
- Improve accuracy for noisy images
- Deploy the application on cloud platforms

## 👨‍💻 Author

Priyanshu Pandey

⭐ Acknowledgements

- MNIST Dataset
- TensorFlow & Keras
- Streamlit Community
