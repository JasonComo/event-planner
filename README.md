### A Django event planner with CRUD capabilities. Users can signup and create, edit, and delete events, as well as maintain a friend list.


## Description
This project was created in Python's Django framework. It allows users to plan and keep track of their own/friends' events. The application has CRUD capabilities, and supports user registration/login, as well as friend list functionality.

Key features:
- Signup/Login/Logout: Allows users to register for an account with a username, first and last name, and password. 
- Event Creation/Deletion: Users can create an event with a title, location, date, time, and description. They can also invite guests from their friend list. In addition, they can delete their own event.
- Event Editing/: Users can completely modify their own event, including the list of invitees and attending guests.
- Friend List Management: Users can add and remove friends, as well as cancel pending friend requests.
  
## Installation
You should use a virtual environment to prevent conflicts. Make sure it is installed on your machine.
```
pip install virtualenv
```

Clone the the repository.
```
git clone JasonComo/event-planner
```

Navigate to the repository.
```
cd event-planner
```

Open your terminal, and create a virutal environment.
```
virtualenv env
```

Activate the virtual environment on Windows:
```
source env/bin/activate
```

Activate the virtual environment on Mac/Linux:
```
virtualenv env
```
Install the project dependencies.
```
pip install -r requirements.txt
```

## Usage
After installation, run the server.
```
python manage.py runserver
```
### Register
Selecting the signup button in the bottom right will take users to a signup screen, where they can create an account.

### Login
After creating an account, users can login by entering their username and password.

### Create Workout
Users can create a workout by clicking the "Create Workouts" button. From there, they can add up to eight exercises, with names, sets, and reps, to the workout.

### View Workouts
Users can view existing workouts by clicking the "View Workouts" button.

### Edit Workouts
Users can edit or delete existing workouts by clicking the "Edit Workouts" button. From there, they can modify or remove exercises and their names, sets, and/or reps, as well as delete a workout entirely.

### Logout
Users can logout by clicking the "Logout" button on the bottom left corner of the window.
