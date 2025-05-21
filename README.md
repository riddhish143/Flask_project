# Lab Flask Project

This project is a simple Flask application that serves as a basic example of a web application built with Python and Flask.

## File Structure and Purpose

*   `.vscode/`: This directory contains Visual Studio Code editor settings and configurations.
    *   `extensions.json`: Recommended VS Code extensions for this project.
    *   `settings.json`: Workspace-specific settings for VS Code.
    *   `tasks.json`: Task configurations for VS Code, potentially for building or running the project.
*   `README.md`: This file, providing documentation for the project.
*   `app.py`: This is the main Flask application file. It contains the Python code that defines the web server, routes, and application logic.
*   `requirements.txt`: This file lists the Python dependencies required to run the project. You can install them using `pip install -r requirements.txt`.
*   `test_app.py`: This file contains unit tests for the Flask application.

## Running the Application

1.  **Install Dependencies:**
    Open your terminal and navigate to the project's root directory. Then, install the required Python packages using pip:
    ```bash
    pip install -r requirements.txt
    ```

2.  **Run the Flask Development Server:**
    Once the dependencies are installed, you can run the application with the following command:
    ```bash
    python app.py
    ```

3.  **Access the Application:**
    Open your web browser and navigate to the following URL:
    ```
    http://127.0.0.1:5000/
    ```
    If you are running this in a cloud environment, the URL might be different. For example:
    ```
    https://{your_url}.file_name.app:5000/
    ```

## Running Tests

To run the automated tests for this application, navigate to the project's root directory in your terminal and execute the following command:

```bash
python -m unittest test_app.py
```

This will discover and run the tests defined in the `test_app.py` file.

## Technologies Used

*   **Python:** The primary programming language used for the application logic.
*   **Flask:** A lightweight WSGI web application framework in Python used to build the web server and handle requests.
*   **HTML:** (Implicitly) Used for rendering the web pages, though not explicitly listed as a file, Flask routes often return HTML.
*   **unittest:** Python's built-in unit testing framework, used in `test_app.py`.

## Contributing

Feel free to fork this repository, make changes, and submit pull requests. If you find any issues or have suggestions for improvements, please open an issue in the repository.
