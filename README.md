# Create the README.md file for the user to download
readme_content = """# 📚 Wordgenius — Expand Your Vocabulary with ChatGPT

**Wordgenius** is a powerful vocabulary-building companion designed to help learners master new words efficiently and enjoyably — directly inside ChatGPT. Whether you're studying for exams, learning a new language, or simply want to enrich your communication skills, Wordgenius gives you a smarter way to grow your vocabulary.

---

## 🚀 Features

✨ **Daily Word Learning**  
Receive clear word definitions, examples, synonyms, antonyms, and pronunciation.

📝 **Interactive Quizzes**  
Test your retention through smart, adaptive challenges.

🎯 **Personalized Learning**  
Words are tailored to your level and interests — track progress as you grow.

🔁 **Spaced Repetition Practice**  
Review past words right when you're most likely to forget them.

⚡ **Instant Clarifications**  
Ask about any word and get simplified explanations instantly.

📈 **Progress Insights**  
View your learning streaks, mastered words, and improvement over time.

---

## 🧠 How It Works

1. **Tell Wordgenius your goal** — exam prep, casual learning, business vocabulary, etc.
2. **Receive curated words daily** with examples that fit real conversation.
3. **Practice with quick quizzes** to reinforce memory.
4. **Track your mastery** and continue leveling up your vocabulary.

---

## 🏁 Getting Started

1. Open **ChatGPT** (with Apps enabled)  
2. Search for **Wordgenius** in the Apps catalog  
3. Tap **Add to ChatGPT**  
4. Start by saying:  
   > "Help me learn 5 new advanced English words!"  
   or  
   > "I want to improve my vocabulary for business meetings."

---

## 🔒 Privacy First

Wordgenius processes only the information needed to personalize your vocabulary experience. No personal data is shared externally.

---

## 💡 Example Commands

Try asking:

- "Teach me 10 intermediate English verbs"
- "Quiz me on the words I learned yesterday"
- "Give me synonyms for ‘innovative’"
- "Explain this word like I'm 10 years old: ‘perplexed’"

---

## 🌟 Why Wordgenius?

Because learning new words should feel exciting — not overwhelming.  
Wordgenius makes vocabulary growth:

✔ Engaging  
✔ Efficient  
✔ Personalized  
✔ Always available inside ChatGPT

---

📬 *Questions or feedback?*  
We’re continuously improving Wordgenius — let us know what features you’d love next!

"""

file_path = "/mnt/data/README.md"
with open(file_path, "w", encoding="utf-8") as f:
    f.write(readme_content)

file_path

