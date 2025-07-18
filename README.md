# 🧠 Quiz Application

An interactive, category-based quiz app built with **HTML**, **CSS**, **JavaScript**, and **Bootstrap 5**.  
Users can select a trivia category and answer randomized multiple-choice questions powered by the [Open Trivia Database](https://opentdb.com/). It features animated UI feedback, score tracking, and seamless question navigation.

📺 **Live Demo:** _Coming Soon_  
🎮 **API Source:** [OpenTDB](https://opentdb.com/)

---

## 📌 Features

- 🎯 **Category Selection** – Choose from various trivia topics
- 🔄 **Dynamic Questions** – Fetched live via API
- ✅ **Answer Validation** – Immediate feedback on selection
- 💡 **Correct Answer Reveal** – When incorrect, correct answer is shown
- 🔢 **Score Calculation** – Final score shown at quiz end
- 🔁 **Restart Option** – Start over anytime
- 🎨 **Responsive UI** – Mobile-friendly, built with Bootstrap

---

## 📸 Screenshots

| Start Page                    | Quiz Interface                    | End Screen                    |
|------------------------------|------------------------------------|-------------------------------|
| ![Select-topic](https://github.com/user-attachments/assets/fd451bd8-3626-45b7-8fd2-8d6c5da089a2) | ![Pick Correct Answer](https://github.com/user-attachments/assets/c0940efe-a570-4c0f-8504-94e915324176) | ![Result](https://github.com/user-attachments/assets/c4779b27-a6e6-4781-93df-908412fb09fd) |

> _You can add your screenshots in an `assets/` folder._

---

## 🧰 Technologies Used

| Technology   | Purpose                              |
|--------------|---------------------------------------|
| HTML5        | Page structure                        |
| CSS3         | Custom styling and animations         |
| Bootstrap 5  | Layout and component styling          |
| JavaScript   | Core logic, interactivity, API calls  |
| OpenTDB API  | Quiz questions by category            |

---

## 🗂️ Folder Structure

```
quiz-app/
├── index.html           # Main HTML file
├── style.css            # Custom styles
├── script.js            # Quiz logic & API integration
├── Ej Logo.png          # Favicon
├── assets/              # Screenshots (optional)
└── README.md            # This file
```

---

## 🚀 Getting Started

### 🖥️ Clone & Run Locally

```bash
git clone https://github.com/Owais41111/Quiz-Appliction
cd quiz-app
open index.html   # Or just double-click it
```

> No build tools or frameworks needed — this is a static frontend project!

---

## 🧠 How It Works

### 1. Category Loading

- Categories are fetched from the OpenTDB API.
- User selects a category from a dropdown list.

### 2. Fetching Quiz Data

```javascript
let url = `https://opentdb.com/api.php?amount=10&category=${category_id}&type=multiple`;
```

- 10 multiple-choice questions per session
- HTML-encoded questions are decoded in the browser

### 3. Gameplay

- Displays question and 4 randomized options
- On selection, validates answer and shows feedback
- Prevents skipping questions
- Navigation with "Next" and "Previous" buttons
- Final score shown at the end

---

## 🎮 Controls

| Action           | Input                        |
|------------------|------------------------------|
| Start Quiz       | Click **Begin**              |
| Next Question    | Click **Next**               |
| Previous Question| Click **Previous**           |
| Restart Quiz     | Click **Try Again!**         |

---

## ⚠️ Limitations

- No timer functionality (yet!)
- No difficulty selection
- Questions are fetched once per session only

---

## 📈 Possible Improvements

- ⏱️ Timer per question
- 🧩 Difficulty selection (easy/medium/hard)
- 🌐 Offline question fallback
- 💾 LocalStorage to save scores
- 🔊 Add sound effects and transitions

---

## 👨‍💻 Author

**Ejaz Ahmed**  
📧 Email: [owais41111@gmail.com](mailto:owais41111@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/ejaz-ahmed-602a02321)  
💻 [GitHub](https://github.com/Owais41111)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

> Made with ❤️ using vanilla JavaScript and the Open Trivia API
```
