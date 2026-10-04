# MindMate

MindMate is an AI study and mental wellness assistant designed for students. It helps users build personalized study plans, track mood, maintain focus, and manage overall well-being in one place.

**Live Demo:** [MindMate](https://imaakarsh.github.io/MindMate/)

## Features

- **Smart Planner:** Generate a personalized study timetable based on subjects, exam dates, and available hours.
- **Mood Tracker:** Log daily feelings and dynamically adjust study schedules based on current mood.
- **AI Mental Health Chat:** Interact with an AI companion for stress management, motivation, and study tips (powered by the Google Gemini API).
- **Progress Bar:** Monitor overall study progress at a glance.
- **Focus Timer:** Utilize a Pomodoro-style timer featuring 25-minute focus and 5-minute break modes.

## Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Backend:** Node.js, Express.js
- **AI Integration:** Google Gemini API (`@google/generative-ai`)

## Installation & Setup

To run MindMate locally and enable the AI Chat backend, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/imaakarsh/MindMate.git
   cd MindMate
   ```

2. **Install backend dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add a Google Gemini API key (available from Google AI Studio):
   ```env
   GEMINI_API_KEY=your_gemini_api_key_here
   PORT=3000
   ```

4. **Start the backend server:**
   ```bash
   npm start
   ```
   The server will start processing AI chat requests on the configured port.

5. **Open the frontend:**
   Open `index.html` directly in a web browser, or serve it using a tool such as the Live Server extension in VS Code.

## Builders

- **[imaakarsh](https://github.com/imaakarsh)** – Full Stack Developer
- **[iamsiddharthhh](https://github.com/iamsiddharthhh)** – Frontend Developer

---

> "For Students, By Students. Study Smarter, Stay Stress-Free."