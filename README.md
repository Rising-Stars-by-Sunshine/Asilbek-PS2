# PS
# Predicting Depression Risk to Enhance Academic Success

## Overview
This repository contains the code and resources for the research study **"Predicting Depression Risk to Enhance Academic Success"**. The project explores the use of machine learning models to assess depression risk among students by integrating mental health indicators with academic performance metrics and analyzing correlations between depression status and exam scores.

## System Configuration Instructions

### 1. Local Environment Setup
To run the analysis locally, follow these steps:

#### Prerequisites
Ensure your system has the following installed:
- Python (>= 3.8)
- Git
- Virtual Environment (optional but recommended)
- Jupyter Notebook (if running interactive analysis)

#### Step 1: Clone the Repository
```sh
git clone https://github.com/your-username/repository-name.git
cd repository-name
```

#### Step 2: Create and Activate Virtual Environment (Optional)
```sh
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```

#### Step 3: Install Dependencies
```sh
pip install -r requirements.txt
```

#### Step 4: Set Up Environment Variables
Create a `.env` file in the root directory and add the necessary configurations:
```sh
DATA_PATH="./data/"
MODEL_PATH="./models/"
```

#### Step 5: Run the Jupyter Notebook (if applicable)
```sh
jupyter notebook
```

#### Step 6: Execute the Analysis
Run the main script to preprocess the data and train models:
```sh
python main.py
```

### 2. Cloud Environment Setup (Google Colab & AWS EC2)
#### **Google Colab**
1. Open Google Colab: [Google Colab](https://colab.research.google.com/)
2. Clone the repository within the Colab notebook:
   ```python
   !git clone https://github.com/your-username/repository-name.git
   %cd repository-name
   ```
3. Install dependencies:
   ```python
   !pip install -r requirements.txt
   ```
4. Upload datasets to Google Drive and mount it:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
5. Run the analysis by executing the notebook cells.

#### **AWS EC2 Setup**
1. Launch an EC2 instance (Ubuntu 20.04 recommended).
2. Connect via SSH:
   ```sh
   ssh -i your-key.pem ubuntu@your-instance-ip
   ```
3. Install Python and required packages:
   ```sh
   sudo apt update && sudo apt install -y python3-pip
   ```
4. Clone the repository:
   ```sh
   git clone https://github.com/your-username/repository-name.git
   cd repository-name
   ```
5. Install dependencies:
   ```sh
   pip3 install -r requirements.txt
   ```
6. Run the main script:
   ```sh
   python3 main.py
   ```

## Directory Structure
```
repository-name/
│── data/               # Dataset files
│── models/             # Trained models
│── notebooks/          # Jupyter notebooks for analysis
│── src/                # Source code files
│── requirements.txt    # Python dependencies
│── main.py             # Main execution script
│── README.md           # System setup instructions
```

## Dependencies
See `requirements.txt` for a complete list of dependencies.

## Contact
For questions, contact **your-email@example.com** or open an issue in this repository.
