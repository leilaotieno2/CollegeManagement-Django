The College Management System is a web application that is developed using Python and the Django web framework. This project is meant to aid in managing student, staff, and course records of an educational institution.
It provides a way for users whereby administrators, teachers, and students may access and manipulate important data regarding college activities, such as student registration, student attendance tracking, leave management, and notification sending.

 # Setup Instructions
1. Clone the repository:
git clone https://github.com/leilaotieno2/CollegeManagement-Django

2. Navigate to the project directory: cd CollegeManagementSystem

3. Create a virtual environment: python -m venv venv

4. Activate the virtual environment:

On Windows: venv\Scripts\activate
On Linux/Mac: source venv/bin/activate


5. Install the required packages: pip install -r requirements.txt

6. Make database migrations:

python manage.py makemigrations
python manage.py migrate

7. Create a superuser for admin access:
python manage.py createsuperuser

8. Run the development server: python manage.py runserver

9. Access the application:
Open your web browser and go to `http://127.0.0.1:8000/`
