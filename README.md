# Handwritten-Digit-Recognition

# 🧠 Handwritten Digit Recognition using CNN

This project is a deep learning-based web application that recognizes handwritten digits (0–9) using a trained **Convolutional Neural Network (CNN)**. It utilizes the **MNIST dataset** and is built with **Python**, **TensorFlow/Keras**, and **Flask** for the web interface.

---

## 🔍 Demo

You can draw a digit in the browser canvas, and the app will predict what digit it is using a trained CNN model.

---

## 📦 Features

- Trained CNN model using the MNIST dataset
- Web interface for drawing digits
- Real-time digit prediction
- Clean UI using Flask templates
- Model accuracy stored and tracked

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy, Pandas
- OpenCV
- Flask (for web app)
- HTML / CSS / JavaScript (for frontend)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Mohammed-Sharuk/Handwritten-Digit-Recognition.git
cd Handwritten-Digit-Recognition

2. Create Virtual Environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate

3. Install Dependencies
pip install -r requirements.txt

4. Run the App
python app.py

Then open your browser and go to http://127.0.0.1:5000.

📁 Project Structure
Handwritten-Digit-Recognition/
├── app.py                  # Main Flask application
├── Balanced-Model.h5       # Trained CNN model
├── mapping.csv             # Label mapping (if needed)
├── requirements.txt        # Python dependencies
├── templates/
│   └── index.html          # HTML frontend
├── static/
│   └── (CSS/JS files)      # Frontend assets
└── model/
    └── (Model training code)

📊 Model Architecture
Input: 28x28 grayscale image

Conv2D → ReLU → MaxPooling

Conv2D → ReLU → MaxPooling

Flatten → Dense → Dropout → Dense (Output: 10 classes with Softmax)

📈 Accuracy
Model trained with 99%+ accuracy on MNIST dataset.

Accuracy details stored in Accuracy.txt (optional).

🧹 Cleanup Notes
Unnecessary files like .vscode/, __pycache__/, .ipynb_checkpoints/ are ignored via .gitignore.

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

📜 License
This project is open-source and available under the MIT License.

🙋‍♂️ Author
Mohammed Sharuk
🔗 GitHub: @Mohammed-Sharuk

