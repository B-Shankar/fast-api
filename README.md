mkdir fastApi-omnicopy

cd fastAPi-omnicopy

python3 -m venv .venv

..venv/bin/activate

echo ".venv" > .gitignore


pip install --upgrade pip

pip install "fastapi[standard]"

pip freeze > requirements.txt

touch main.py