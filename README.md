# interview-py

## Developer Setup

Follow the steps below to set up your development environment:

1. **Create a virtual environment**

   Use Python's built-in `venv` module to create a virtual environment. This isolates your project and its dependencies from other projects.

   ```bash
   python3 -m venv env
   ```

2. **Activate the virtual environment**

    On Windows, run:
    ```bash
    .\env\Scripts\activate
    ```
    On Unix or MacOS, run:

    ```bash
    source env/bin/activate
    ```
3. **Install the dependencies**

    Use pip, a package manager for Python, to install the project's dependencies. These are listed in the requirements.txt file.
    ```bash
    pip install -r requirements.txt
    ```
4. **Run the tasks.py file**
  
    You can now run the tasks.py file with Python:
    ```bash
    python tasks.py
    ```