# Flutter Form Validation App
This Flutter application demonstrates how to create a form with multiple input fields, including validation for each field. The form includes fields like Name, Email, CNIC, Contact Number, Address, and Password with appropriate validation checks.

# Features
A form with the following fields:
Name (Only alphabet characters allowed)
Email (Valid email format check)
CNIC (13 digits required)
Contact Number (10-12 digits allowed)
Address (Text input)
Password (Minimum 8 characters, with letters, numbers, and symbols)
Real-time validation with error messages when fields do not meet requirements.
A submit button that displays a success message once the form is correctly filled.
# Getting Started
Follow these instructions to set up and run the project on your local machine.

# Prerequisites
Flutter SDK
Installation
Clone or download the project:
Download the project as a zip file and extract it.
Or, clone the repository (if hosted on GitHub) using:
# bash
Copy code
git clone https://github.com/your-username/repository-name.git
Navigate to the project folder:
# bash
Copy code
cd your-project-folder
Install dependencies: Run the following command in the terminal to get all required packages:
# bash
Copy code
"flutter pub get"
Running the App
To run the app on an emulator or connected device, use the following command:

# bash
Copy code
flutter run
# File Structure
main.dart: The main entry point of the app, which launches the ValidationForm.
ValidationForm: Contains the UI and logic for the form, including text field controllers and validation rules.
# Dependencies
No external dependencies are required aside from Flutter.
# Additional Notes
This app demonstrates basic form validation techniques in Flutter.
All validation checks are performed when the user submits the form.
