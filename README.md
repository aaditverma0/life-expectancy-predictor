# Life Expectancy Predictor

## Project Overview
The Life Expectancy Predictor is a project designed to analyze health, economic, and demographic factors to predict human life expectancy globally using World Health Organization (WHO) data.

##  Team & Roles
| Name | Entry number | Role | GitHub Handle |
| --- | --- | --- | --- |
| Aadit Verma | 2026ESB1472 | Execution Lead | @aaditverma0 |
| Garima Gautam | 2026AIB1036 | Documentation Lead | @garima-2708 |
| Mishika | 2026EEB1379 | PPT Lead | @Mishika1379 |
| Jayant Kumar Nanda | 2024MCB1297 | Video Lead | @jayantkunanda |

## Contributions in code
All four members contributed code (see commit history)

## Project Structure

```text
life-expectancy-predictor/
├── Data/
│   └── Life Expectancy Data.csv
├── notebooks/
│   ├── data_exploration_and_pre-processing.ipynb
│   ├── main.ipynb
│   ├── splitting_and_model_building.ipynb
│   └── validation_evaluation_ppt.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```


## Setup 
  
Requires **Python 3.12 or newer**. Developed with Python 3.13.14.  
  
```bash  
git clone https://github.com/aaditverma0/life-expectancy-predictor.git  
cd life-expectancy-predictor  
```  
  
Create and activate a virtual environment, then install the requirements.  
  
**macOS / Linux**  
```bash  
python3 -m venv venv  
source venv/bin/activate  
python -m pip install -r requirements.txt  
```  
  
**Windows (PowerShell)**  
```powershell  
python -m venv venv        # or: py -3 -m venv venv  
venv\Scripts\Activate.ps1  
python -m pip install -r requirements.txt  
```  
If PowerShell says running scripts is disabled, run `Set-ExecutionPolicy -Scope CurrentUser RemoteSigned` once, or use Command Prompt and run `venv\Scripts\activate.bat` instead. On Debian/Ubuntu, if creating the venv fails, run `sudo apt install python3-venv`.  
  
## How to run  
  
With the virtual environment activated, from the project root:  
  
```bash  
jupyter notebook  
```  
  
Open `notebooks/main.ipynb` and choose **Kernel > Restart & Run All**. If Jupyter asks for a kernel, choose "Python 3 (ipykernel)". The notebooks find the dataset through the relative path `Data/Life Expectancy Data.csv`, so they work whether Jupyter starts in the project root or in the `notebooks` folder. 

## Links 
1. PPT Link : https://drive.google.com/file/d/1EdDB_S_RVq5ClF8U8vujg0DtIKMd5Yct/view?usp=sharing

## Summary of Results
- Used data modeling techniques to predict life expectancy.
- Evaluated model accuracy based on health and economic factors.

## 🤖 AI Use Disclosure
AI tools were used to assist in structuring documentation, code generation, and error troubleshooting during the development of this project.
