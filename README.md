# Gold_forecasting
 
## Gold Forecasting Project Setup

### 1. Python Installation

Ensure Python is installed on your system. You can download it from the [official Python website](https://www.python.org/downloads/).


### 2. VS Code Setup

- **Install Visual Studio Code**: Download and install it from the [official website](https://code.visualstudio.com/).

- **Install Required Extensions**:
  - **Python Extension**: Search for "Python" in the Extensions view and install the extension by Microsoft.
  - **Jupyter Extension**: Search for "Jupyter" in the Extensions view and install the extension by Microsoft.

### 3. Python Requirements Installation

- **Create and Activate a Virtual Environment** (optional but recommended):
  - Navigate to your project directory:
    ```sh
    cd path/to/your/project
    ```
  - Create a virtual environment:
    ```sh
    python -m venv venv
    ```
  - Activate the virtual environment:
    - On Windows:
      ```sh
      venv\Scripts\activate
      ```
    - On macOS/Linux:
      ```sh
      source venv/bin/activate
      ```

- **Install Dependencies**:
  - Ensure you have a `requirements.txt` file in your project directory.
  - Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

### 4. Running Jupyter Notebook

- **Open VS Code**.

- **Open the Jupyter Notebook**:
  - Navigate to the directory containing your Jupyter notebook file (`.ipynb`).
  - Open the file in VS Code.

- **Select the Kernel**:
  - Click on the kernel name in the top-right corner of the notebook interface.
  - Select the Python interpreter from your virtual environment if necessary.

- **Run the Notebook Cells**:
  - Use the play button next to each cell or `Shift+Enter` to run individual cells.
  - You can also click "Run All" to execute all cells.
