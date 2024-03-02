# QuestionTime
**A Quora-like Single Page Application built with Django, Django REST Framework and Vue JS**

### How to run the project on your local machine?

#### Clone the repo and move inside it:
```
git clone 
cd QuestionTime
```

#### Create a new Python Virtual Environment:
```
python3 -m venv venv
```

#### Activate the venv and install Django dependencies:
```
source ./venv/bin/activate
pip install -m ./requirements.txt
```

#### Apply Django migrations:
```
python manage.py migrate
```

#### Install Node dependencies:
```
cd QuestionTime/vite-frontend
npm install
```

#### Run Vite's Development Server:
```
npm run dev
```

#### Run Django's development server:
```
python manage.py runserver
```
