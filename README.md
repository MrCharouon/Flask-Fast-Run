# Flask-structure



virtualenv env
source env/bin/activate.fish

pip freeze
pip install Flask
touch requirements.txt
pip freeze > requirements.txt

python app.py
