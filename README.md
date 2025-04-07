# # AI-powered performance Analyzer for OS Processes
This project is an AI-powered tool designed to monitor and analyze OS processes in real-time, detecting anomalies using machine learning.

# 📁 Installation and Setup

Follow these steps to set up the project:

# 1. Clone the Repository

    git clone https://github.com/SA9572/AI-powered-performance-Analyzer-for-OS-Processes.git
    cd AI-Powered-Performance-Analyzer-for-OS-Processes

# 2. Create a Virtual Environment

Create a new virtual environment for the project (recommended).

    python3 -m venv env     # For Linux/Mac
    python -m venv env       # For Windows

# 3. Activate the Virtual Environment
    source env/bin/activate    # For Linux/Mac
    .\env\Scripts\activate      # For Windows

# 4. Install Required Packages

Install all necessary packages using the requirements.txt file.

    pip install -r requirements.txt

# 5. Train the Model

Run the training script to create the anomaly detection model.

    python train_model.py

# 6. Run the Web Interface

Launch the Streamlit app to start monitoring processes.

    streamlit run visualization.py

# 7. Team Member's
    Abhishek Gupta(12323073)
    Saurabh Kumar(12303432)
    Sudhanshu Kumar Suman (12319001)


# 📌 Note
    Ensure you have Python 3.x installed.
    Install additional packages if prompted by any error messages.