## Getting Started

### Prerequisites

Ensure you have Python installed. It is recommended to use `miniconda` or `conda` for environment management.

### Installation

1.  **Install Miniconda (if not already installed)**

    Download and install Miniconda from the official website: <mcurl name="Miniconda Installer" url="https://docs.conda.io/en/latest/miniconda.html"></mcurl>

2.  **Create a Conda Environment**

    Open your terminal or Anaconda Prompt and create a new environment:

    ```bash
    conda create -n uxlaws python=3.11
    conda activate uxlaws
    ```

3.  **Install Requirements**

    Navigate to the project directory and install the necessary packages:

    ```bash
    cd /path/to/your/uxlaws
    pip install -r requirements.txt
    ```

4.  **Run the Streamlit Application**

    ```bash
    streamlit run streamlit_app.py

    The application will open in your web browser.


