# install pip mac

curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python3 get-pip.py

# install pip win

python get-pip.py

# install playwright

pip install --upgrade pip
python3 -m pip install playwright
playwright install
python3 -m pip install pytest
python3 -m pip install pytest-play playwright

# command

pytest --headed -base-url https://www.saucedemo.com --browser chromium -- browser firefox
