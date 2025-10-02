# FitnessForge AI

FitnessForge AI is a web-based, AI-powered fitness and nutrition coach designed to create highly personalized workout and diet plans. Built from the ground up, this project demonstrates a modern, conversational approach to fitness planning.

**Live Demo:** [https://sabaloberoi9.github.io/FitnessForge/](https://sabaloberoi9.github.io/FitnessForge/)

---

### Core Features

* **Dual-Path Entry:** Users can choose between a quick, general AI chat or a comprehensive, personalized plan generation flow.
* **Detailed User Onboarding:** Collects crucial data points including:
    * Personal stats (age, gender, height, weight) with Metric/Imperial support.
    * Fitness goals (Build Muscle, Lose Weight, Strength, etc.) with a custom goal option.
    * Training experience level (Beginner to Elite).
    * Workout availability and session duration.
    * Available equipment, from full gyms to bodyweight-only.
    * Complex dietary preferences, restrictions, allergies, and cuisine choices.
* **Conversational AI Plan Forging:** After providing their profile, users engage in a chat with the AI to refine their goals before the final plan is generated.
* **Image Recognition:** The "Quick Chat" feature allows users to upload a photo of their food, and the AI will identify it and provide an estimated calorie count.
* **Post-Generation Modification:** Users can re-engage with the AI to ask for adjustments to their generated plan.

### Technology Stack

This project was built from scratch as a single, self-contained `index.html` file to demonstrate portability and foundational web development skills.

* **Frontend:** **React** (via UMD scripts) for building the dynamic, component-based user interface.
* **Styling:** **Tailwind CSS** for a modern, responsive, and utility-first design.
* **AI Integration:** **Google Gemini API** (`gemini-2.5-flash-preview-05-20`) is used for both the conversational chat and the personalized plan generation, including multi-modal (image and text) analysis.
* **Transpilation:** **Babel** is used in the browser to compile JSX into plain JavaScript.

### How to Run

Since this is a self-contained `index.html` file, you can simply open it in any modern web browser to run the application locally.
