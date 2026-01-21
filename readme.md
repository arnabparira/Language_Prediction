🌍 Language Detection Using Recurrent Neural Network (RNN)

📌 Project Description

This project implements a **Recurrent Neural Network (RNN)** model to detect the **language of a given text input**.
The model is trained on the **Language Detection.csv** dataset and later deployed using **Streamlit** to provide an interactive and user-friendly web interface for language prediction.

The complete system is divided into three main parts:

• Model Training  
• Model Prediction  
• Visualization & Deployment using Streamlit  

---

🎯 Objective

The main objective of this project is to:
- Automatically identify the language of user-provided text
- Apply deep learning (RNN) techniques for natural language processing
- Provide real-time language prediction through a web-based interface

---

🧩 Project Components

🔹 Part 1: Model Training

- Used **Language Detection.csv** dataset containing multilingual text samples
- Performed:
  - Text cleaning and preprocessing
  - Tokenization and padding
  - Label encoding
  - Train-test split
- Designed and trained an **RNN-based deep learning model**
- Evaluated model performance
- Saved the trained model for later prediction use

---

🔹 Part 2: Model Prediction

- Loaded the trained RNN model
- Accepted custom text input from the user
- Applied the same preprocessing steps used during training
- Predicted the **language of the given input text**

---

🔹 Part 3: Streamlit Visualization & Deployment

- Built an interactive **Streamlit web application**
- Provided a text input area for users
- Displayed the predicted language in real time
- Enabled easy usage without requiring technical knowledge

---

🛠️ Tech Stack

💻 Programming Language  
- Python  

📚 Libraries & Frameworks  
- NumPy  
- Pandas  
- Scikit-learn  
- TensorFlow  
- Keras  
- Streamlit  

🤖 Deep Learning  
- Recurrent Neural Network (RNN)  
- Multiclass Text Classification  

🚀 Deployment & Visualization  
- Streamlit  

---

▶️ How to Run the Project

Clone the repository:


git clone <repository-url>
Install required dependencies:

pip install -r requirements.txt
Run the Streamlit application:

streamlit run app.py
📈 Output

Detects the language of the input text

Displays prediction clearly through the Streamlit interface

Works for multiple languages present in the dataset

👤 Author

Arnab Parira
|Python | SQL | AI & ML Enthusiast

⭐ Acknowledgement

Thanks to open-source datasets and libraries that made this project possible.

🚀 Connect With Me

📧 Email: arnabparira4@gmail.com
🐙 GitHub: https://github.com/Amitdas-2023

Thanks for checking out this project!
If this project helped you, feel free to ⭐ star the repository and share it with others learning Machine Learning and NLP.