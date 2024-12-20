# Amazon Product Browser

## Setup Instructions

1. **Clone the Repository** 

2. **Set Up Virtual Environment**
   # Create virtual environment
   python -m venv venv

   # Activate virtual environment
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate

3. **Install Dependencies**
   pip install -r requirements.txt

4. **Database Setup**
   python manage.py migrate

5. **Run Development Server** 
   python manage.py runserver

6. **Access the Application**
   - Open your web browser
   - Visit `http://127.0.0.1:8000/`

