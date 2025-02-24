
![White and Blue Modern College Academic Research Poster](https://github.com/user-attachments/assets/37b9eec8-4190-4534-90ba-d0af212ac8f5)

Predicting Depression Risk to Enhance Academic Success
Overview
This repository contains the code and resources for the research study "Predicting Depression Risk to Enhance Academic Success". The project explores the use of machine learning models to assess depression risk among students by integrating mental health indicators with academic performance metrics and analyzing correlations between depression status and exam scores.

System Configuration Instructions
1. Local Environment Setup
Follow these steps to run the analysis on your local machine:

Prerequisites
Ensure your system has the following installed:

Python (>= 3.8)
Git
Virtual Environment tools (optional but recommended)
Jupyter Notebook (if running interactive analysis)
Step 1: Clone the Repository
sh
Copy
Edit
git clone https://github.com/your-username/repository-name.git
cd repository-name
Step 2: Create and Activate a Virtual Environment (Optional)
sh
Copy
Edit
python -m venv venv
# On macOS/Linux:
source venv/bin/activate
# On Windows:
venv\Scripts\activate
Step 3: Install Dependencies
sh
Copy
Edit
pip install -r requirements.txt
Step 4: Set Up Environment Variables
Create a .env file in the root directory with the following configuration:

sh
Copy
Edit
DATA_PATH="./data/"
MODEL_PATH="./models/"
Step 5: Run the Jupyter Notebook (if applicable)
Launch Jupyter Notebook to work interactively:

sh
Copy
Edit
jupyter notebook
Step 6: Execute the Analysis
Run the main script to preprocess the data and train the models:

sh
Copy
Edit
python main.py
2. Cloud Environment Setup (Google Colab & AWS EC2)
Google Colab
Open Google Colab.
Clone the repository within a Colab notebook:
python
Copy
Edit
!git clone https://github.com/your-username/repository-name.git
%cd repository-name
Install dependencies:
python
Copy
Edit
!pip install -r requirements.txt
Upload your datasets to Google Drive and mount it:
python
Copy
Edit
from google.colab import drive
drive.mount('/content/drive')
Run the analysis by executing the notebook cells.
AWS EC2 Setup
Launch an EC2 instance (Ubuntu 20.04 is recommended).
Connect via SSH:
sh
Copy
Edit
ssh -i your-key.pem ubuntu@your-instance-ip
Update packages and install Python:
sh
Copy
Edit
sudo apt update && sudo apt install -y python3-pip
Clone the repository:
sh
Copy
Edit
git clone https://github.com/your-username/repository-name.git
cd repository-name
Install dependencies:
sh
Copy
Edit
pip3 install -r requirements.txt
Run the main script:
sh
Copy
Edit
python3 main.py
Directory Structure
bash
Copy
Edit
repository-name/
│── data/               # Dataset files
│── models/             # Trained models
│── notebooks/          # Jupyter notebooks for interactive analysis
│── src/                # Source code files (scripts, utility functions, etc.)
│── requirements.txt    # Python dependencies
│── main.py             # Main execution script
│── README.md           # System setup instructions and project overview
Dependencies
Refer to the requirements.txt file for a complete list of project dependencies, which include libraries such as:

pandas, numpy
rapidfuzz (for fuzzy matching)
matplotlib, seaborn
scikit-learn
xgboost
transformers (Hugging Face)
statsmodels
Contact
For questions or support, please contact aa789@duke.edu or open an issue in this repository.
