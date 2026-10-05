# 🗣️ AI-Based Pronunciation & Fluency Assessment System

## 📌 Project Overview

The **AI-Based Pronunciation & Fluency Assessment System** is a Text and Speech Analysis application designed to evaluate a user's spoken English performance.

The system compares a user's **expected sentence** with their **spoken sentence** and calculates:

* Speech recognition result
* Word accuracy
* Speaking speed
* Fluency score
* Overall score
* Word differences
* Improvement suggestions

The project runs in **Google Colab** using Python and Gradio.

---

## 🎯 Objectives

* Evaluate spoken sentence accuracy.
* Compare expected and recognized speech.
* Calculate word-level accuracy.
* Analyze speaking speed.
* Evaluate fluency.
* Identify missing or incorrect words.
* Provide useful practice suggestions.

---

## ✨ Features

### 📝 Expected Sentence

The user enters a sentence that they want to practice.

### 🎙️ Voice Recording

The user records or uploads their spoken sentence.

### 🤖 Speech Recognition

The audio is converted into text using Faster-Whisper.

### 📊 Word Accuracy

The recognized sentence is compared with the expected sentence.

### ⏱️ Fluency Analysis

Speaking speed is calculated using WPM.

### 💡 Improvement Suggestions

The system identifies areas where the user needs additional practice.

---

## 🔄 System Workflow

```text
Expected Sentence
        +
    Voice Input
        ↓
Speech Recognition
        ↓
Recognized Text
        ↓
Text Comparison
        ↓
 ┌─────────────────┐
 │ Word Accuracy   │
 │ Speaking Speed  │
 │ Fluency         │
 └─────────────────┘
        ↓
 Overall Score
        ↓
 Improvement Tips
```

---

## 🛠️ Technologies Used

* Python
* Faster-Whisper
* Natural Language Processing
* Speech Recognition
* Sequence Matching
* Gradio
* Google Colab

---

## ▶️ How to Run

1. Open Google Colab.
2. Create a new notebook.
3. Paste the complete project code into one cell.
4. Run the cell.
5. Wait for installation and model loading.
6. Open the generated Gradio URL.
7. Enter the expected sentence.
8. Upload or record your speech.
9. Click the analysis button.
10. View the results.

---

## 📊 Example

### Expected Sentence

```text
Artificial intelligence is changing the world.
```

### Recognized Speech

```text
Artificial intelligence is changing our world.
```

### Output

```text
Word Accuracy: 83%
Speaking Speed: 125 WPM
Fluency Score: 95%

Overall Score: 89%

Level:
Good

Improvement:
Practice the sentence again and focus on the
words that were incorrectly recognized.
```

---

## 🎓 TSA Concepts Used

* Speech Recognition
* Speech-to-Text
* NLP
* Tokenization
* Text Comparison
* Sequence Matching
* Word Accuracy
* Speech Rate Analysis
* Fluency Evaluation

---

## 📁 Project Structure

```text
Pronunciation-Fluency-Assessment/
│
├── pronunciation_assessment.ipynb
└── README.md
```

---

## 🚀 Future Enhancements

* Phoneme-level pronunciation analysis
* Accent detection
* Real-time pronunciation feedback
* Sentence difficulty levels
* English learning dashboard
* Student progress tracking
* Multiple language support
* AI pronunciation coach
* PDF assessment report

---

## ⚠️ Limitations

The current system evaluates pronunciation indirectly through speech recognition and word matching. It does not perform detailed phoneme-level acoustic pronunciation analysis.

Therefore, the score is an educational approximation.

---

## 🏁 Conclusion

The **AI-Based Pronunciation & Fluency Assessment System** combines speech recognition and NLP to help users practice spoken English.

It provides immediate feedback about word accuracy, fluency, and speaking speed, making it suitable for students and language-learning applications.
