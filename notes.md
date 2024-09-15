
Auth:
Michael
djangoWebDevelopment56023496


For some crap reason need to select default interpreter when relaunching
/Users/mroust/miniforge3/bin/python

Stopped following yt video at 18:00 in order to understand what is going on.


Video Notes:
- Making The Registration View
  - Make api/serializer.py to transmit user data
  - In api/views.py create a CreateUserView that allows anyone to create a new user
- Connecting Our Auth Routes
  - In urls.py configure different urls.
  - Now save files and go to cli:
    - `python manage.py makemigrations`
    - `python manage.py migrate`
- Creating Custom Models (notes, models, ticket!, some "dataclass")
  - Writing models and serialisation for creating notes assigned to users.
- Frontend Setup
  - `npm create vite@latest frontend -- --template react`
  - `cd frontend`
  - `npm install axios react-router-dom jwt-decode`
  - In `frontend/src`
    - Delete css files
    -


