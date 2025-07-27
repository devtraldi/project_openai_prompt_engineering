# Project: Prompt Engineering Fundamentals with LLMs

This project provides a hands-on demonstration of prompt engineering techniques to improve the quality, structure, and relevance of responses from Large Language Models (LLMs).

The main notebook (`01_prompt_engineering_basics.ipynb`) uses the **Google Gemini API** to showcase how a well-structured prompt yields superior results compared to a vague one. This serves as a foundational example for anyone looking to get more predictable and useful results from generative AI.

---

## 🚀 Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

* Python 3.8+
* Git

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/YOUR_USERNAME/project_openai_prompt_engineering.git](https://github.com/YOUR_USERNAME/project_openai_prompt_engineering.git)
    ```
    *(Note: Replace `YOUR_USERNAME` with your actual GitHub username).*

2.  **Navigate to the project directory:**
    ```sh
    cd project_openai_prompt_engineering
    ```

3.  **Create and activate a virtual environment:**
    ```sh
    # Create the venv
    python -m venv venv

    # Activate on Windows
    venv\Scripts\activate
    
    # Activate on macOS/Linux
    # source venv/bin/activate
    ```

4.  **Install the required libraries:**
    The `requirements.txt` file includes all necessary libraries for both Google Gemini and OpenAI.
    ```sh
    pip install -r requirements.txt
    ```

5.  **Set up your API Keys:**
    This project requires a Google API Key to run.
    * Make a copy of the `.env.example` file and name it `.env`.
    * Open the `.env` file and add your personal **Google API Key**. You can get one for free at [aistudio.google.com](https://aistudio.google.com).
    * The file is git-ignored for your security.

    Your `.env` file should look like this:
    ```
    # Required for the project to run
    GOOGLE_API_KEY="AIzaSy..." 

    # Optional, for secondary experimentation
    OPENAI_API_KEY="sk-..."
    ```

---

## 💻 Usage

1.  Ensure your virtual environment is active.
2.  Start JupyterLab from your terminal:
    ```sh
    jupyter lab
    ```
3.  In the JupyterLab interface, navigate to the `notebooks` folder and open the `01_prompt_engineering_basics.ipynb` notebook to view and run the code. The notebook is pre-configured to use the Google Gemini API.