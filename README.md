# MobileNet for Skin Disease Classification

# Steps

## 0. Kaggle API Setup
* Open [Kaggle](https://www.kaggle.com/)
* Signin or SignUp
* Click on Profile on top-right corner
* Go to Settings
* Move to API Section and Click Create New Token
* Download the file in `~/.kaggle/` directory

## 1. Install Python 3.11.4 and Add to PATH

### Windows:
* Download Python 3.11.4 from [python.org](https://www.python.org/downloads/release/python-3114/).
* During installation, check **"Add Python to PATH"**.
* Verify installation using:
```sh
    python --version
    python3 --version
```
### macOS/Linux
* `brew install python@3.11` or `sudo apt update && sudo apt install python3.11`
* Verify installation using:
```sh
python3 --version
```
a
## 2. Clone the GitHub Repository
* `git clone https://github.com/KandimallaAmarnadh/MobileNet.git`
* `cd MobileNet.git`
* Download Dataset from [Here](https://www.kaggle.com/datasets/pritpal2873/multiple-skin-disease-detection-and-classification/data)

## 3. Create a Virtual Environment
* Windows `python -m venv venv`
* macOS/Linux `python3 -m venv venv`

## 4. Activate the Virtual Environment
* Windows CMD `venv\Scripts\activate`
* Windows Powershell `venv\Scripts\Activate.ps1`
* macOS/Linux `source venv/bin/activate`
   
## 5. Install Dependencies from requirements.txt
* In terminal `pip install -r requirements.txt`

## 6. Run the Model
* Select Kernel with venv
* Run `model.ipynb` cell by cell
* After successful execution you should see a file named
    * skin_disease_model.keras

## 7. Run Flask Application
* `streamlit run index.py`
