
Dynamic Form Builder and Data Collection Web Application
This web application is built using ReactJS and Redux to allow users to dynamically add fields for data collection based on their selection. The application consists of two main pages: one for adding fields dynamically and another for displaying the added fields for data collection.

Table of Contents
Getting Started
Adding Fields Dynamically
Displaying Fields for Data Collection
Redux Storage
How to Use
Sample Screenshots
Getting Started
To get started with the application, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/dynamic-form-builder.git
Navigate to the project directory:

bash
Copy code
cd dynamic-form-builder
Install dependencies:

bash
Copy code
npm install
Run the application:

bash
Copy code
npm start
Open your browser and visit http://localhost:3000.

Adding Fields Dynamically
Select the user type from the dropdown: "Student," "Self-Employee," or "Business."
Click the "Add Field" button to dynamically add fields.
For each field, select the field type from the dropdown: "Text Box," "Drop-Down," or "Date Picker."
Enter the field properties, including Field Name, Field Type, Field Validation, and Field Data (if applicable).
You can add a maximum of 4 fields.
Displaying Fields for Data Collection
Navigate to the "Data Collection" page.
The dynamically added fields will be displayed based on the user's previous selections.
Collect data based on the specified field types and validations.
Redux Storage
All the data entered, including the dynamically added fields and their properties, is stored in Redux. This ensures that the data is retained even after a page reload.

How to Use
Adding Fields:

Select user type from the dropdown.
Click "Add Field" to dynamically add up to 4 fields.
Select field type and enter field properties.
Data Collection:

Navigate to the "Data Collection" page.
Fields added dynamically will be displayed.
Collect data based on the specified field types and validations.
