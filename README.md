
# Calorie-finder

This project is a simple Django web application that allows users to search for foods and see their calorie content. The project integrates with the [NinjaAPI Nutrition API](), which provides detailed nutritional information. 

## Requirements

Before running the project, make sure to install the necessary dependencies listed in the `requirements.txt` file.

### Installation

1. Clone this repository to your local machine:


2. Create a virtual environment:

   ```bash
   python3 -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### API Key Setup

To access the NinjaAPI Nutrition API, you will need an API key.

1. Go to the [NinjaAPI Nutrition API](https://www.api-ninjas.com/) website and sign up to get your API key.
2. Once you have your API key, add api key to views.py file

### Running the Project

1. Run the migrations to set up the database:

   ```bash
   python manage.py migrate
   ```

2. Start the development server:

   ```bash
   python manage.py runserver
   ```

3. Open your web browser and go to `http://127.0.0.1:8000/` to view the application.

### Usage

- In the application, users can search for different foods and get their calorie content.
- The food data is fetched from the NinjaAPI Nutrition API using the API key that you have set up.
- Simply enter the food item into the search bar, and the app will display the calorie information.


### Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.


