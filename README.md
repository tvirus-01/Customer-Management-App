# Customer Management App

**Customer Management App** is a custom CRM (Customer Relationship Management) application built using Django. This app provides businesses with the tools to manage customer data, track interactions, and enhance customer relationships effectively.

## Features

- **Customer Data Management:** Easily add, edit, and delete customer records with essential information like name, contact details, and company information.
- **Interaction Tracking:** Log and track interactions with customers, including calls, meetings, emails, and notes.
- **Dashboard Overview:** A comprehensive dashboard providing quick insights into customer interactions and status updates.
- **Customizable Fields:** Flexibility to customize customer fields according to business requirements.
- **Search and Filter:** Powerful search and filtering capabilities to quickly find customer records.
- **User Authentication:** Secure user authentication with customizable access levels for different roles.
- **Reporting and Analytics:** Generate reports on customer interactions, sales pipeline, and other metrics.

## Getting Started

### Prerequisites

- Python 3.x
- Django 3.x or later
- PostgreSQL or SQLite (depending on your preference)
- Additional Python libraries specified in `requirements.txt`

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/CustomerManagementApp.git
   cd CustomerManagementApp
    ```

2. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Set Up Database: Configure your database settings in settings.py. For example, for SQLite:**
    ```python
    DATABASES = {
        'default': {
            'ENGINE': 'django.db.backends.sqlite3',
            'NAME': BASE_DIR / "db.sqlite3",
        }
    }
    ```
    For PostgreSQL, set the ENGINE to 'django.db.backends.postgresql' and provide the necessary database credentials.


4. **Run Migrations**
    ```bash
    python manage.py migrate
    ```

5. **Create Superuser**
    ```bash
    python manage.py createsuperuser
    ```

6. **Run server**
    ```bash
    python manage.py runserver
    ```
    Visit http://127.0.0.1:8000 in your browser to access the app.

### Usage

- **Admin Panel**: Access the Django admin panel at /admin to manage users and other administrative tasks.
- **Customer Management**: Use the main interface to manage customer data and interactions.
- **Customizations**: Modify templates, views, and models as needed to fit your specific requirements.

### Contributing
Contributions are welcome! Please fork this repository and submit pull requests with your enhancements or bug fixes.

### Lisence
This project is licensed under the MIT [License](https://opensource.org/license/mit) - see the LICENSE file for details.

