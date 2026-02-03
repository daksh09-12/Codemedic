# CodeMedic AI - Intelligent Debugger

CodeMedic AI is a smart code debugging tool powered by Google's Gemini AI. It identifies errors, explains bugs, and provides fixed code snippets in seconds.

## 🚀 Getting Started

Follow these steps to run the project locally.

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher) installed.
- A free [Google Gemini API Key](https://aistudio.google.com/app/apikey).

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/YOUR_USERNAME/codemedic.git
    cd codemedic
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    # or
    npm i
    ```

### Configuration

2.  **Add your API Key:**
    Open `.env.local` and replace the placeholder with your actual key:
    ```env
    VITE_GEMINI_API_KEY=AIzaSy...YourKeyHere
    ```

### Running the App

Start the development server:

```bash
npm run dev
```

Open your browser to `http://localhost:3000`.
