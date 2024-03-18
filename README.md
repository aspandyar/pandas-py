# Pandas Library

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Installation

1. Clone the repository.

    ```git
    git clone git@github.com:aspandyar/pandas-py
    ```

2. Install the required dependencies using the following command:

    ```shell
    pip install -r requirements.txt
    ```

3. Download the Stack Overflow Survey data for 2019 from the following URL: [Stack Overflow Survey Data 2019](https://insights.stackoverflow.com/survey). This data is used in the project.

### Setting up Virtual Environment

#### For Windows:

1. First, ensure you have Python installed on your system. If not, download and install Python from [here](https://www.python.org/downloads/).

2. Open PowerShell as an administrator.

3. Run the following command to set the execution policy for the current session:

    ```cmd
    Set-ExecutionPolicy Unrestricted -Scope Process
    ```

4. Create a virtual environment by executing:

    ```cmd
    python -m venv .venv
    ```

5. Activate the virtual environment by running:

    ```cmd
    .\.venv\Scripts\activate
    ```

#### For Linux:

1. First, ensure you have Python installed on your system. Most Linux distributions come with Python pre-installed. If not, you can install it using your package manager. For example, on Ubuntu, you can install Python with:

    ```bash
    sudo apt update
    sudo apt install python3 python3-venv
    ```

2. Navigate to your project directory in the terminal.

3. Create a virtual environment by executing:

    ```bash
    python3 -m venv .venv
    ```

4. Activate the virtual environment by running:

    ```bash
    source .venv/bin/activate
    ```

## Usage

1. Launch Jupyter Notebook by running the following command:

    ```shell
    jupyter notebook
    ```

2. Open the `[file].ipynb` file in Jupyter Notebook.
3. Follow the instructions in the notebook to run the code and explore the project. All code examples in this project are based on lessons from a YouTube playlist. You can find the playlist [here](https://youtube.com/playlist?list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS&si=c3h9purXLSW6ohC_).

4. To run in VS Code, set up a password using the following command:

    ```shell
    jupyter notebook password
    ```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.