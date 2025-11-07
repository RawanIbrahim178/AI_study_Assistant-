# AI_study_Assistant-
A smart AI-powered assistant to summarize lessons and answer questions

## 🖼️ Project Preview

![App Screenshot](images/app_preview.png)

---

## 💡 Features
- Summarizes long lessons into clear notes
- Answers students' questions using AI
- Generates quiz questions for practice
- Simple web interface built with Streamlit

---

## 🧑‍💻 Example Code
```python
def summarize_text(text):
    # Example summarization function
    summary = model.summarize(text)
    return summary

user_input = "The human brain controls all body functions."
print(summarize_text(user_input))
