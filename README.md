# Project: Interactive Prompt Engineering Playground

## 🚀 About The Project

This project is an interactive **Prompt Engineering Playground** built within a Jupyter Notebook using `ipywidgets`. It serves as a powerful tool for experimenting with and comparing responses from different Large Language Models (LLMs).

The main notebook, `04_prompt_engineering_pro.ipynb`, provides a control panel with interactive widgets to dynamically change:
* The AI Model (supporting Google Gemini models like `gemini-1.5-pro` and `gemini-1.5-flash`)
* Generation Parameters like `temperature`, `top_p`, `top_k`, and `max_output_tokens`
* The `System Prompt` and `User Prompt`

It features real-time **streaming** of the AI's response and advanced output formatting, which renders Markdown, highlights code blocks, and adds a **"Copy Code" button** to each block for an enhanced user experience.

---

## ⚙️ Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

* Python 3.8+
* Git

### Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/devtraldi/project_prompt_engineering.git
    ```

2.  **Navigate to the project directory:**
    ```sh
    cd project_prompt_engineering
    ```

3.  **Create and activate a virtual environment:**
    ```sh
    # Create the venv
    python -m venv venv

    # Activate on Windows
    venv\Scripts\activate
    ```

4.  **Install the required libraries:**
    ```sh
    pip install -r requirements.txt
    ```

5.  **Set up your API Keys in `.env`:**
    * Make a copy of the `.env.example` file and name it `.env`.
    * Open `.env` and add your **Google API Key**. You can get a free key at [aistudio.google.com](https://aistudio.google.com).

    Your `.env` file should look like this:
    ```
    # Required for the main features
    GOOGLE_API_KEY="AIzaSy..."
    ```

---

## 💻 Usage

1.  Ensure your virtual environment is active.
2.  Start JupyterLab from your terminal:
    ```sh
    jupyter lab
    ```
3.  In the JupyterLab interface, navigate to the `notebooks` folder and open **`04_prompt_engineering_pro.ipynb`**.
4.  Run all the cells. The interactive control panel will appear.
5.  Modify the parameters using the widgets and click "Generate Response" to experiment.