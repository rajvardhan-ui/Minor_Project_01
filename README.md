# Minor_Project_01
# 🚀 Project GroupDNA

> **A Python-based WhatsApp Chat Analytics Engine that transforms raw chat exports into meaningful insights using custom algorithms and terminal-based visualizations.**

![Python](https://img.shields.io/badge/Python-3.x-blue)
![NumPy](https://img.shields.io/badge/NumPy-Enabled-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📖 Overview

**Project GroupDNA** is my **first Python data analytics project**, built to analyze exported WhatsApp chat data and generate detailed insights about group activity, user behavior, communication patterns, and word usage.

Instead of relying on high-level analytics libraries, this project focuses on implementing the core logic manually using Python fundamentals, string processing, algorithms, and NumPy.

The final output is presented as a structured terminal dashboard containing multiple analytical reports.

---

## ✨ Features

### 📊 1. Group Structure Overview

* Total messages
* Total participants
* Individual contribution percentages
* Per-user message distribution
* Terminal bar charts

---

### 📝 2. Per-Person Text Metrics

* Total words spoken
* Average message length
* Individual text statistics

---

### 📅 3. Activity Peak Detection

* Most active day
* Most active hour
* Message activity trends

---

### 🔥 4. Hour-Block Activity Heatmap

Visualizes hourly activity for every participant using a NumPy-based matrix and terminal characters.

---

### 📖 5. Word Frequency Analysis

* Most frequently used words
* Word occurrence counts
* Ranked frequency table

---

### ⚡ 6. Behaviour Metrics

* Average response speed
* Longest silent streak
* Reply activity

---

### 🎭 7. Group Archetype Detection

Automatically assigns user personalities such as:

* Storyteller
* Ghost
* Spammer
* (More archetypes can be added in future updates.)

---

## 🛠️ Tech Stack

* Python
* NumPy
* Datetime
* File Handling
* String Processing
* Custom Algorithms

---

## 🧠 Concepts Used

* Text Parsing
* Data Cleaning
* File Processing
* Matrix Operations
* Frequency Analysis
* Pattern Detection
* Time-Series Analysis
* Data Visualization (Terminal)
* Problem Solving

---

## 📂 Project Structure

```text
Project-GroupDNA/
│
├── GroupDNA.py
├── GroupDNA.ipynb
├── sample_chat.txt
├── requirements.txt
├── README.md
│
└── screenshots/
      └── output.png
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Project-GroupDNA.git
```

### 2. Navigate to the project directory

```bash
cd Project-GroupDNA
```

### 3. Install the required dependency

```bash
pip install -r requirements.txt
```

> If you don't have a `requirements.txt` file, install NumPy manually:
>
> ```bash
> pip install numpy
> ```

### 4. Export a WhatsApp chat

On WhatsApp:
- Open the group chat.
- Tap **⋮ > More > Export Chat**.
- Choose **Without Media**.
- Save the exported `.txt` file.

### 5. Place the exported chat file

Copy the exported `.txt` file into the project folder.

Example:

```
Project-GroupDNA/
│── GroupDNA.py
│── chat.txt
```

*(Replace `chat.txt` with the filename expected by your program, if different.)*

### 6. Run the program

```bash
python GroupDNA.py
```

The program will process the chat file and generate the complete analytics dashboard in the terminal.
## 📷 Sample Output

![GroupDNA Dashboard](screenshots/output.png)

## 📈 Example Insights

✔ Group contribution analysis

✔ User engagement statistics

✔ Word frequency ranking

✔ Hour-wise activity heatmap

✔ Peak communication periods

✔ Behaviour analysis

✔ Chat archetype detection

---

## 🎯 Future Improvements

* Sentiment Analysis
* Emoji Analytics
* Conversation Network Graphs
* AI-powered Chat Summaries
* Topic Detection
* Interactive Dashboard
* Export Reports as PDF
* CSV Report Generation
* Web-based Interface

---

## 📚 What I Learned

This project helped me improve my understanding of:

* Python Programming
* Algorithm Design
* Data Cleaning
* Text Analytics
* NumPy Arrays
* Problem Solving
* Debugging
* Software Design

Most importantly, it taught me how to convert raw, unstructured text into meaningful insights using code.

---

## 🤝 Contributing

Suggestions and improvements are always welcome.

Feel free to fork this repository, open an issue, or submit a pull request.

---

## ⭐ If you found this project interesting

Consider giving the repository a ⭐ on GitHub.

It motivates me to build more projects and continue learning!

---

## 👨‍💻 Author

**Rajvardhan Doiphode**

Python Enthusiast • Data Analytics Learner • Engineering Student

---

## 📄 License

This project is licensed under the MIT License.

