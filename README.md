# German Language Learning App (Desktop)

A simple and interactive **German learning desktop application** built with **Python** and **Tkinter**. This app allows users to practice vocabulary and sentence translation between **Turkish and German**, with support for audio pronunciation, hints, and Excel-based data storage.

## 🎯 Features

- 🔁 **Bidirectional Translation**  
  - German → Turkish  
  - Turkish → German

- 📚 **Vocabulary or Sentence Modes**  
  Choose whether to study single words or full sentences.

- ➕ **Add New Words or Sentences**  
  Easily add new entries through the interface. Data is automatically saved into a local **Excel file**.

- 🎲 **Randomized Questions**  
  App selects questions randomly from the Excel file based on the selected mode and language direction.

- ❌ **Answer Checking with Feedback**  
  If your answer is incorrect, the correct answer is shown.

- 💡 **Hint System**  
  You can request up to 3 hints per question.

- 🔊 **Text-to-Speech Integration**  
  Hear how the word or sentence is pronounced (uses system TTS or Python's `pyttsx3`).

## 🛠 Tech Stack

- **Language:** Python  
- **GUI Library:** Tkinter  
- **Data Storage:** Local Excel files (`.xlsx`) using `openpyxl`  
- **Text-to-Speech:** `pyttsx3` (offline speech module)

## 📦 Installation

1. **Clone the repository**
```bash
git clone https://github.com/your-username/german-learning-app.git
cd german-learning-app

Install required packages
pip install openpyxl pyttsx3

Run the application
python app.py

🧾 How It Works
On startup, the app reads vocabulary from a local Excel file.

You can choose the mode:

Translate from German to Turkish or vice versa

Study words or sentences

The app shows a random question based on your choice.

You type your answer, get immediate feedback, and can request hints or listen to the pronunciation.

📁 Folder Structure
bash
Kodu kopyala
/german-learning-app
│
├── app.py                   # Main application script
├── data/
│   └── vocabulary.xlsx      # Local database (editable)
├── assets/                  # (Optional) Icons or images
└── README.md
✅ To-Do / Future Plans
 Score tracking & progress saving

 Advanced grammar quiz mode

 User interface improvements with custom themes

 Multi-language support

📬 Contact
If you have suggestions, feature requests, or want to contribute:

GitHub: github.com/yunusemrekonar

Email: konaryunusemre@outlook.com


