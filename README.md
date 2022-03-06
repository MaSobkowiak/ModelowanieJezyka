python -m venv venv 
source venv/bin/activate
mkdir ./outputs
jupyter nbconvert --to pdf xyz.ipynb --output-dir='./pdf'