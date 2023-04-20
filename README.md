# Analytics_Dashboard
Python, Spark and API Based project to show Analytics performed on an E-Commerce platform

1. Data Collection: The first step is to collect the data from the e-commerce platform. This data can include customer data, transaction data, product data, and other relevant information. The data can be stored in a data warehouse or a Spark cluster for further processing.

2. Data Processing: Once the data is collected, it needs to be processed to extract insights and generate reports. Spark can be used to process large volumes of data quickly and efficiently. Python can be used to build data processing pipelines using Spark APIs like PySpark.

3. Data Visualisation: The processed data can be visualised using a React-based dashboard. The dashboard can display various charts, tables, and graphs to give insights into the data. React charting libraries like s, Victory, or D3 can be used to build charts and graphs.

4. Rest API: A Rest API can be built using Python Flask to serve the processed data to the React dashboard. The API can fetch the data from the Spark cluster and serve it in a format that can be consumed by the dashboard.

5. Dashboard Design: Finally, the dashboard can be designed using React components. The dashboard can be designed to be interactive, allowing users to explore the data and filter it based on various criteria.

Deployment: The final step is to deploy the dashboard and API to a server. Platforms like AWS or Heroku can be used to deploy the dashboard and API.


------ Django -------
To integrate Django according to your database schema, you'll need to follow these steps:

Define the database schema: Define your database schema by creating a data model using Django's model system. A model is a Python class that represents a database table, and each attribute of the class represents a field in the table.

> Create a Django app: Create a new Django app by running the following command in your terminal: python manage.py startapp myappname. Replace myappname with the name of your app.

> Define the model: In the models.py file of your app, define the model by creating a new class that inherits from the django.db.models.Model class. Define the fields of your model by creating attributes for each field.

> Create a migration: After defining the model, you need to create a migration to apply the changes to the database. Run the following command in your terminal: python manage.py makemigrations. This command will create a migration file in the migrations directory of your app.

> Apply the migration: Apply the migration to the database by running the following command in your terminal: python manage.py migrate. This command will create the database table based on your model.

> Register the model: To access the model in the Django admin interface, you need to register it. In the admin.py file of your app, import the model and register it using the admin.site.register() method.

> Use the model: You can use the model in your views to retrieve data from the database, create new records, or update existing ones. Use Django's QuerySet API to interact with the database.

That's it! By following these steps, you can integrate Django according to your database schema and start building your application. Remember to run python manage.py runserver to start the development server and test your app.












