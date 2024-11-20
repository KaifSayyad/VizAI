# VizAI

**Introduction**

This project allows users to upload datasets and automatically generate visualizations through natural language queries. It uses the Google Gemini API and Streamlit for an interactive interface, enabling real-time insights and data exploration without requiring programming knowledge.

**Demo**
![](https://github.com/KaifSayyad/ADV_lab/blob/main/Project/demo/demo.gif)

**Prerequisites**

  * Python (version 3.13 or later) - [Download Link](https://www.google.com/url?sa=E&source=gmail&q=https://www.python.org/downloads/)
  * Git (version git version 2.39.5 (Apple Git-154) or later) - [Download Link](https://www.google.com/url?sa=E&source=gmail&q=https://www.google.com/url?sa=E%26source=gmail%26q=https://git-scm.com/downloads)

**Installation**

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/KaifSayyad/VizAI.git
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd VizAI
    ```

3.  **Create a Python virtual environment (recommended):**

      - **Using `python -m venv`:**

        ```bash
        python -m venv .venv
        ```

      - **Using `python3 -m venv` (for Python 3):**

        ```bash
        python3 -m venv .venv
        ```

    This creates a virtual environment named `.venv` in your project directory. Activate it:

    ```bash
    source .venv/bin/activate  # Linux/macOS
    .venv\Scripts\activate.bat  # Windows
    ```

4.  **Install project dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

**Running the Project**

1.  **Activate the virtual environment (if you created one):**

    (Follow steps 3c or 3d from the Installation section, depending on your operating system.)

2.  **Start the Streamlit app:**

    ```bash
    streamlit run app.py
    ```

    This will launch your Streamlit app in your web browser, typically at http://localhost:8501.

**Additional Notes**

  * This README assumes you have a basic understanding of Git, Python virtual environments, and Streamlit.
  * Feel free to customize the instructions based on your project's specific requirements.
  * For more advanced usage, refer to the Streamlit documentation: [https://docs.streamlit.io/en/stable/](https://www.google.com/url?sa=E&source=gmail&q=https://www.google.com/url?sa=E%26source=gmail%26q=https://docs.streamlit.io/en/stable/)
