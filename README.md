# Video and image people counter
A simple people detector and counter. Detection is performed using Histogram of Oriented Gradients (HOG) as features and Support Vector Machines (SVM) as the classifier.

The solution is not perfect and would require a better learning set to achieve better results.

## QuickStart
1. Create virtual environment: `python -m venv counter-env`
1. Activate virtual environment:
    - on Linux: `source counter-env/bin/activate`
    - on Windows: `.\counter-env\Scripts\activate.bat` or `.\counter-env\Scripts\activate.ps1`
    - with Git Bash: `. counter-env/Scripts/activate`
1. Install dependencies: ```pip install -r requirements.txt```
1. Run application: ```python ./app/app.py```