Deepfake Face Detection using Deep Learning
📌 Project Overview

This project detects whether a face image is Real or Fake (Deepfake) using a deep learning model built with TensorFlow.
The application provides a simple web interface where users can upload an image and instantly receive a prediction.

The model was trained using transfer learning with MobileNetV2 for efficient and fast image classification.

🚀 Features

Upload an image and detect Real vs Fake faces

Deep learning model trained on deepfake dataset

Fast predictions using a lightweight CNN architecture

Interactive web interface built with Streamlit

Confidence score displayed for predictions

🧠 Technologies Used

Python

TensorFlow / Keras

Streamlit

NumPy

Pillow

OpenCV

▶️ Run the Application
streamlit run main.py

Then open your browser and go to:

http://localhost:8501
🧪 How It Works

User uploads an image through the web interface.

The image is resized and preprocessed.

The trained deep learning model analyzes the image.

The system predicts whether the face is Real or Fake.

The result and confidence score are displayed.

📊 Model Details

Model: MobileNetV2 (Transfer Learning)

Image size: 160 × 160

Loss function: Binary Crossentropy

Output: Real Face or Fake Face

📷 Example Output
Prediction: Real Face
Confidence: 92%
🔮 Future Improvements

Add face detection before prediction

Improve accuracy using larger datasets

Deploy the model on cloud platforms

Support video deepfake detection

📜 License

This project is for educational and research purposes only.