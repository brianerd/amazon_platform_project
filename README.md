# Amazon Product Browser

## Setup Instructions

1. **Clone the Repository** 

2. **Set Up Virtual Environment**   ```bash
   # Create virtual environment
   python -m venv venv

   # Activate virtual environment
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate   ```

3. **Install Dependencies**   ```bash
   pip install -r requirements.txt   ```

4. **Database Setup**   ```bash
   python manage.py migrate   ```

5. **Run Development Server**   ```bash
   python manage.py runserver   ```

6. **Access the Application**
   - Open your web browser
   - Visit `http://127.0.0.1:8000/`

## Project Structure
