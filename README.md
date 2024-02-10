**1. Introduction**

**1.1 Purpose**
The Calorie Tracker Web App is designed to help users track their daily caloric intake by providing detailed nutritional information about various foods. It utilizes external APIs to fetch accurate and up-to-date data.

**1.2 Features**
Food search functionality
Detailed nutritional information (Carbohydrates, Chlosterol, Fat, Protein, etc.) 
Daily caloric intake tracking (In progress) 

<img width="1395" alt="image" src="https://github.com/andrewz4184/Calorie_Tracker/assets/69803093/974a38fb-72b2-4af9-87d9-ee1093a538bc">

<img width="792" alt="image" src="https://github.com/andrewz4184/Calorie_Tracker/assets/69803093/d8d8a1d9-95e1-4efb-9a06-c7a82c9d7f3e">

**1.3 Technologies Used**
Django (Backend)
HTML, CSS, JavaScript (Frontend)
External APIs for food data

**2. Setup and Installation**
      
**2.1 Prerequisites**
Python installed (version 3.x)
Django framework installed
Web browser (Chrome, Firefox, Safari, etc.)

**2.2 Installation Steps**
Clone the repository: git clone https://github.com/your-username/calorie-tracker.git
Navigate to the project directory: cd calorie-tracker
Activate virtual environment: python3 -m venv env -> source env/bin/activate (macOS) 
Install dependencies: pip install -r requirements.txt
Apply migrations: python manage.py migrate
Run the development server: python manage.py runserver
The web app should now be accessible at http://localhost:8000.

**3. Architecture**
**3.1 Frontend**
The frontend is built using HTML, CSS, and JavaScript. It communicates with the Django backend to fetch and display data.

**3.2 Backend**
The backend is powered by Django, handling user authentication, data storage, and communication with external APIs.

**3.3 APIs Used**
Food Search API: Used to search for food items and retrieve basic information.
Nutrition Information API: Fetches detailed nutritional information based on the selected food.
Sourced from API Ninjas https://api-ninjas.com/api 

**4. Usage**
**4.1 Searching for Food**
Users can search for food items using the search bar on the homepage.
**4.2 Viewing Nutritional Information**
After selecting a food item from the search results, detailed nutritional information is displayed.
**4.3 Tracking Daily Caloric Intake**
Users can track their daily caloric intake by adding selected food items to their daily log. (In Progress) 

**5. Future Enhancements
5.1 Planned Features**
More accurate calorie tracking - calculate based off user inputted height/weight/bmi 
TDEE (Total Daily Energy Expenditure) Calculator 

