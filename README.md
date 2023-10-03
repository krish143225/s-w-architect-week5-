My Django Hello World App

Welcome to my simple Django Hello World app! This app provides a JSON response with a "Hello World!" message.

**Prerequisites**

Before you get started, make sure you have the following prerequisites installed on your system:

- Python (https://www.python.org/downloads/)
- Django (https://www.djangoproject.com/download/)

**Getting Started**

Follow these steps to run the app locally on your system:

**1. Clone the Repository:**

         git clone <https://github.com/krish143225/s-w-architect-week5-.git>
   
**2. Navigate to the Project Directory:**

         cd mydjangoproj

**3. Create a Virtual Environment (Optional but recommended):**

         python -m venv week5project

**4. Activate the Virtual Environment:**

   **On Windows:**

         week5project\Scripts\activate

**On macOS and Linux:**

         source week5project/bin/activate

**5. Install Dependencies:**

         pip install -r requirements.txt

**6. Migrate the Database:**

         python manage.py migrate

**7. Start the Development Server:**

         python manage.py runserver

**To access the Hello World JSON response in your web browser, follow these steps:**

**Open your web browser**.

**9. Navigate to the following URL:**

         http://127.0.0.1:8000/hello/

You will see a JSON response with the message "Hello World!" displayed in your browser.

