
# MinBot - Mining Chatbot

**MinBot** was developed as part of the **Smart India Hackathon** to address challenges in mining operations. The project aims to streamline communication, data retrieval, and problem-solving in the mining industry by offering an interactive, AI-powered chatbot. MinBot is designed to provide real-time, automated solutions to common issues faced by workers and stakeholders, including equipment status, safety protocols, and operational inquiries. By utilizing artificial intelligence, it enhances efficiency, reduces operational downtime, and improves decision-making processes in the mining sector.

---

## 🛠️ Features
- **Natural Language Processing**: Understands and responds to user queries effectively.
- **Mining-specific Functions**: Provides real-time information, guidance, and problem-solving capabilities tailored to mining operations.
- **User-friendly Interface**: Designed for ease of use with minimal training.
- **Scalable and Flexible**: Easily adaptable to new mining scenarios and queries.

---

## 📂 Project Structure
```
MinBot/
│
├── botinterface.html    # HTML file for the chatbot interface
├── logo.png             # Logo image file
├── mainpage.html        # Main page HTML file
├── script.js            # JavaScript for the chatbot and main page functionality
├── styles.css           # CSS for styling the chatbot and main page
└── README.md            # Project documentation

```

---

## 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SheriSnehith31/MinBot.git
   cd MinBot
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. (Optional) Update dataset or model files if required.

---

## 🚀 Usage

### Running the Chatbot
Start the chatbot application:
```bash
python src/chatbot.py
```

### Adding New Intents
Modify the `intents.json` file in the `dataset/` directory to add new queries and responses.

### Training the Model
If new data is added, retrain the chatbot:
```bash
python src/train_model.py
```

---

## 📊 Results and Applications
- Successfully deployed a chatbot capable of handling **XX+ mining-related queries**.
- Reduced manual effort in addressing repetitive queries by **XX%**.
- Applicable in various industries beyond mining with slight modifications.

---

## 📚 Technologies Used
- **Python**: Core programming language
- **NLTK/Spacy**: Natural Language Processing libraries
- **Flask**: Backend framework for hosting the chatbot
- **TensorFlow/Keras**: For intent recognition and response generation

---

## 🏆 Achievements
- **Smart India Hackathon Finalist**: Recognized for solving real-world problems.
- Enhanced the safety and efficiency of mining operations with an intelligent solution.

---

## 🤝 Contributions
Contributions are welcome! Please fork the repository and submit a pull request.


---

## 📧 Contact
For any inquiries or support, reach out to **Sheri Snehith** at:
- **GitHub**: [SheriSnehith31](https://github.com/SheriSnehith31)
- **Email**: [Your Email Address]
