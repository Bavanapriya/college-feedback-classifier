# 🎓 College Feedback Classifier

This project uses **IBM watsonx.ai** to automatically classify student feedback into relevant **categories** such as **Academics**, **Facilities**, and **Administration**. It does **not perform sentiment analysis** — the focus is purely on identifying the topic area of the feedback.

---

## 🧠 Project Objective

To streamline and automate the classification of student feedback to help institutions route concerns or suggestions to the right department (e.g., academics, admin, or infrastructure).

---

## ⚙️ How It Works

1. **Input**: A CSV file with raw student feedback.
2. **Model**: IBM watsonx.ai analyzes each entry and predicts the category it belongs to.
3. **Output**: The original CSV file is updated with a new column called `Predicted Category`.

---

## 🧪 Sample Output

| Feedback                                          | Sentiment | Category       | Predicted Category |
|--------------------------------------------------|-----------|----------------|---------------------|
| The professors explain concepts very clearly.    | positive  | Academics      | Academics           |
| The canteen food is not hygienic.                | negative  | Facilities      | Facilities          |
| The admin staff is friendly and helpful.         | positive  | Administration | Administration      |
| The online learning platform is easy to use.     | positive  | Academics      | Academics           |

> ✅ Note: `Sentiment` is not predicted — it is just part of the input data. The model only classifies **category**.

---

## 🛠 Tools Used

- **IBM watsonx.ai** – for zero-shot text classification
- **Jupyter Notebook / CSV** – for data formatting and result export
- **GitHub** – version control and collaboration

---

## 📂 Files

- `college_feedback_classified.csv` – Final file with the `Predicted Category` column
- `README.md` – This project description

---

## 🗃️ Use Cases

- Routing feedback to correct departments
- Categorizing large-scale survey responses
- Automating manual classification of text

---

## 📬 Contact

Developed by: **Bavanapriya**

Project Repo: [GitHub - college-feedback-classifier](https://github.com/Bavanapriya/college-feedback-classifier)

---
