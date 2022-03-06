```
python -m venv venv 
source venv/bin/activate
mkdir ./outputs
jupyter nbconvert --to pdf xyz.ipynb --output-dir='./pdf'
rsync -aP --exclude=/venv . "/mnt/c/Users/masob/Desktop/STUDIA/MODELOWANIE JĘZYKA/rozwiazania"
```