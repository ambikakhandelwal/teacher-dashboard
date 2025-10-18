# 🧑‍🏫 Teacher Dashboard — STEMUp Portal

The **Teacher Dashboard (STEMUp Portal)** is an interactive web application that allows teachers to visualize student performance, analyze progress by subject, and generate AI-powered feedback and learning plans using **Google Gemini API**.  
It combines data visualization, responsive design, and AI integration for an engaging and insightful teacher experience.

---

## 📂 Project Structure

```
Teacher-Dashboard/
│
├── index.html      # Main HTML structure and layout
├── style.css       # Custom styling (fonts, spinner animation)
└── script.js       # Core functionality and Gemini API integration
```

---

## ⚙️ Features

✅ **Responsive Dashboard UI**
- Built using **Tailwind CSS** and **Lucide Icons**.  
- Displays student cards with avatars, grades, and progress bars.  
- Light/dark theme compatible.

✅ **Dynamic Student Details View**
- View each student's performance by subject.  
- Displays a progress chart using **Chart.js**.  
- Lists all educational games played and their scores.

✅ **AI-Powered Assistant**
- Generates **personalized feedback** for students.  
- Suggests **custom learning plans** using **Google Gemini API**.

✅ **Smooth Navigation**
- Single-page layout with interactive transitions.  
- Quick toggle between dashboard and detail view.

---

## 🧠 Tech Stack

| Technology | Purpose |
|-------------|----------|
| **HTML5** | Structure and layout |
| **Tailwind CSS** | Responsive styling |
| **Lucide Icons** | Clean iconography |
| **Chart.js** | Data visualization |
| **JavaScript (Vanilla)** | Logic and interactivity |
| **Google Gemini API** | AI-generated insights |

---

## 🚀 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/teacher-dashboard.git
cd teacher-dashboard
```

### 2. Open the Project
You can open the folder in **VS Code** or any code editor.

### 3. Add Your Google Gemini API Key
- Visit [Google AI Studio](https://aistudio.google.com/).  
- Click **“Get API Key”** to create a key.  
- Open `script.js` and replace the placeholder with your key:
  ```js
  const API_KEY = "YOUR_API_KEY_HERE";
  ```

### 4. Run the Project
Simply open `index.html` in your browser.  
> 💡 You don’t need a server — it works locally!

---

## 🧩 How It Works

1. **Dashboard View**  
   Displays a grid of students with avatars and progress bars.  
   Click on any student card to view details.

2. **Detail View**  
   Shows:
   - Subject mastery chart (via Chart.js)
   - Key stats (top subject, needs improvement)
   - Game performance summaries
   - AI feedback and learning plan sections

3. **AI Assistant**  
   When you click **Generate Feedback** or **Suggest Learning Plan**,  
   the app sends student data to Gemini API and displays a natural-language response.

---

## 🧵 File Overview

### 📘 `index.html`
- Sets up the dashboard and detail views.  
- Loads Tailwind, Lucide, Chart.js, and `script.js`.

### 🎨 `style.css`
- Imports the **Inter** font.  
- Defines a minimal loading spinner animation.  

### ⚡ `script.js`
- Manages all logic:
  - Renders dashboard and student detail view dynamically.  
  - Fetches AI responses using **Gemini API**.  
  - Handles navigation and chart updates.

---

## 🔐 Environment Variables
| Variable | Description |
|-----------|--------------|
| `API_KEY` | Your Gemini API key from Google AI Studio |

> **⚠️ Important:** Never commit your API key to public repositories.  
  Consider using environment variables if you deploy this project.

---

## 🌈 Customization
You can easily:
- Add more students in the `students` array.  
- Update mock data in `studentProgress`.  
- Modify the styling through Tailwind classes or `style.css`.  

---

## 🪄 Example Use Case
A teacher logs in to the STEMUp Portal → selects a student → views detailed subject-wise performance → clicks **Generate Feedback** to receive AI-written feedback for the student → downloads or shares it with parents.

---

## 📸 Preview
![Dashboard Preview](https://placehold.co/800x400/EEE/333?text=Teacher+Dashboard+Preview)

---

## 🧾 License
This project is open-source under the **MIT License**.
