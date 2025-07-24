pkg update -y 
pkg install git python -y 
git clone https://github.com/Agostinhomucunda/David.git 
cd David
pip install requests bs4 rich 
python David.py
