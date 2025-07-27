\# Project: Prompt Engineering for Improved Performance



\## About The Project



This project provides a hands-on demonstration of prompt engineering techniques used to improve the quality, structure, and relevance of responses from Large Language Models (LLMs) like OpenAI's GPT series.



It contrasts a simple, vague prompt with a well-structured, "engineered" prompt to showcase the significant difference in output performance. This serves as a foundational example for anyone looking to get more predictable and useful results from generative AI.



\## Getting Started



Follow these steps to set up and run the project locally.



\### Prerequisites



\* Python 3.8+

\* Git



\### Installation



1\.  \*\*Clone the repository:\*\*

&nbsp;   ```sh

&nbsp;   git clone \[https://github.com/YOUR\_USERNAME/project\_openai\_prompt\_engineering.git](https://github.com/YOUR\_USERNAME/project\_openai\_prompt\_engineering.git)

&nbsp;   ```

&nbsp;   \*(Note: You will replace `YOUR\_USERNAME` with your actual GitHub username later).\*



2\.  \*\*Navigate to the project directory:\*\*

&nbsp;   ```sh

&nbsp;   cd project\_openai\_prompt\_engineering

&nbsp;   ```



3\.  \*\*Create and activate a virtual environment:\*\*

&nbsp;   ```sh

&nbsp;   # Create the venv

&nbsp;   python -m venv venv



&nbsp;   # Activate on Windows

&nbsp;   venv\\Scripts\\activate

&nbsp;   

&nbsp;   # Activate on macOS/Linux

&nbsp;   # source venv/bin/activate

&nbsp;   ```



4\.  \*\*Install the required libraries:\*\*

&nbsp;   ```sh

&nbsp;   pip install -r requirements.txt

&nbsp;   ```



5\.  \*\*Set up your environment variables:\*\*

&nbsp;   \* Make a copy of the `.env.example` file and name it `.env`.

&nbsp;   \* Open the `.env` file and add your personal OpenAI API key. This file is git-ignored for your security.

&nbsp;   ```

&nbsp;   OPENAI\_API\_KEY="sk-..."

&nbsp;   ```



\## Usage



1\.  Ensure your virtual environment is active.

2\.  Start JupyterLab from your terminal:

&nbsp;   ```sh

&nbsp;   jupyter lab

&nbsp;   ```

3\.  In the JupyterLab interface, navigate to the `notebooks` folder and open the `01\_prompt\_engineering\_basics.ipynb` notebook to view and run the code.

