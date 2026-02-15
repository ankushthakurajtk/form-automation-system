# SETUP GUIDE

## 1. Introduction
This guide provides comprehensive installation and setup instructions for the **Form Automation System** project.

## 2. Python Environment Setup
1. **Install Python**: Ensure Python 3.6 or higher is installed. You can download it from [python.org](https://www.python.org/downloads/).
2. **Verify Installation**: Run the following command in your terminal:
   ```bash
   python --version
   ```

## 3. Dependency Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ankushthakurajtk/form-automation-system.git
   cd form-automation-system
   ```
2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   ```
3. **Activate the Virtual Environment**:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
4. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## 4. Environment Configuration
1. **Create a `.env` File**:
   Copy the `.env.example` file to a new file named `.env`.
   ```bash
   cp .env.example .env
   ```
2. **Configure Environment Variables**: Update the variables in the `.env` file according to your setup.

## 5. Running the Application
1. **Start the Application**:
   ```bash
   python app.py
   ```
2. **Access the Application**: Open a web browser and navigate to `http://localhost:5000`.

## 6. Testing
- To run the tests, execute:
  ```bash
  python -m unittest discover
  ```

## 7. Project Structure Overview
```
form-automation-system/
├── app.py                # Main application file
├── requirements.txt      # Dependency list
├── .env                  # Environment variables
├── tests/                # Test files
└── venv/                 # Virtual environment (generated)
```

## 8. Troubleshooting Guide
- If you encounter issues, please check:
  - Whether all dependencies are installed correctly.
  - Your Python version matches the requirements.
  - Any error messages in the terminal for clues.

## 9. Next Steps for Developers
- Explore the codebase and familiarize yourself with the project structure.
- To contribute, create a new branch, make your changes, and submit a pull request.

## 10. Conclusion
You are now ready to use the Form Automation System. Happy coding!