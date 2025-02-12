In this project, we:

● Utilized Python and popular machine learning libraries such as scikit-learn and TensorFlow to build and evaluate machine learning models for predicting the quality of transmission of optical network channels. 

● Performed data preprocessing, including normalization and standardization, to prepare the data for model training. 

● Developed and optimized multiple machine learning models, including Random Forest, Support Vector Machines (SVM), Multi-Layer Perceptron (MLP), Convolutional Neural Networks (CNN), Long Short-Term Memory (LSTM), and Gated Recurrent Unit (GRU). 

● Utilized hyperparameter optimization techniques, such as Randomized Search, to improve model performance. 

● Evaluated model performance using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE). 

● Performed data augmentation to increase the size and diversity of the training dataset, improving model accuracy. 

● Visualized data and model results using Matplotlib and Seaborn to gain insights and communicate findings.

Installing Dependencies from requirements.txt
Follow these steps to install the required Python dependencies on your system.
✅ Prerequisites:
•	Ensure Python (>=3.x) and pip (>=21.x) are installed.
•	Check Python and pip versions:
sh
CopyEdit
python --version
pip --version
📌 Installation Instructions
🖥️ Windows:
1.	Open Command Prompt or PowerShell.
2.	Navigate to the project directory:
sh
CopyEdit
cd path\to\your\project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🍏 macOS & 🐧 Linux:
1.	Open Terminal.
2.	Navigate to the project directory:
sh
CopyEdit
cd /path/to/your/project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🔍 Additional Tips:
•	If using a virtual environment, activate it before running the installation:
sh
CopyEdit
# Windows (CMD)
venv\Scripts\activate

# Windows (PowerShell)
venv\Scripts\Activate.ps1

# macOS/Linux
source venv/bin/activate
•	If you face permission issues, try:
sh
CopyEdit
pip install --user -r requirements.txt
•	For system-wide installation, use:
sh
CopyEdit
sudo pip install -r requirements.txt
🛠️ Verifying Installation:
Run:
sh
CopyEdit
pip list
to check if all packages are installed.
