🏃‍♂️ AthleteQ — AI-Powered Sports Performance Analyzer

AthleteQ is a real-time AI tool that helps athletes, coaches, and enthusiasts analyze training videos and improve performance through intelligent feedback and motion insights.

🚀 Run Locally

**Prerequisites**

* Node.js (v18+ recommended)
* npm (comes with Node.js)

**Steps to Run**

1. **Install dependencies**

   ```bash
   npm install
   ```

2. **Set up environment variables**

   * Create a `.env.local` file in the root folder.
   * Add your API key:

     ```bash
     GEMINI_API_KEY=your_api_key_here
     ```

3. **Start the development server**

   ```bash
   npm run dev
   ```

4. **Open the app**

   * Visit [http://localhost:5173](http://localhost:5173) in your browser.

💡 Features

* Upload or record short training videos
* Compare with reference movements
* Get AI-based feedback on posture and motion
* Real-time analysis powered by web-based AI models

🧠 Tech Stack

* **React + TypeScript (Vite)** — Frontend framework
* **MediaPipe** — Pose estimation
* **OpenCV.js** — Video processing
* **Gemini API** — Insight generation

🏁 Project Goal

AthleteQ helps athletes understand their form and technique instantly, promoting **data-driven performance improvement** using accessible browser-based AI.
