Flutter Firebase Authentication App
This project is a Flutter application that implements a complete authentication system using Firebase Authentication. The app includes three main screens:

Login Screen: Allows users to log in with their email and password.
Signup Screen: Allows new users to register.
Home Screen: Displays a welcome message with the user's email and a logout button.
Features
Login with email and password
Sign up with email and password
Password reset functionality
Firebase backend integration
Gradient UI design
Form validation
Logout functionality
Prerequisites
Before running the project, ensure you have the following:

3. Setup Firebase for the Project
Go to the Firebase Console:

Navigate to Firebase Console.
Create a new project or select an existing one.
Add the Flutter App:

Click on Add App and choose the Android option.
Register your app by providing your app's package name (e.g., com.example.firebaseauthapp).
Download the google-services.json file provided by Firebase.
Place the google-services.json file inside the android/app directory of your project.
Enable Firebase Authentication:

In the Firebase Console, go to Build > Authentication > Sign-in Method.
Enable the Email/Password sign-in provider.
Configure android/build.gradle: Add the following to the dependencies section:

gradle
Copy code
classpath 'com.google.gms:google-services:4.3.15'
Configure android/app/build.gradle: Add this at the bottom of the file:

gradle
Copy code
apply plugin: 'com.google.gms.google-services'



Screens
Login Screen
Email and password input fields with validation.
"Forgot Password?" link for resetting the password.
"Login" button for authentication.
Link to the signup screen.
Signup Screen
Input fields for name, email, password, and confirm password.
Validation for strong password and matching passwords.
"Signup" button to register a new user.
Link to navigate back to the login screen.
Home Screen
Displays a welcome message with the user's email.
"Logout" button to sign out and return to the login screen.


