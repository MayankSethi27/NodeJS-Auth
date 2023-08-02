# NodeJS-Auth App

Welcome to the NodeJS-Auth app! This application allows users to sign up, sign in, sign out, reset passwords, and even use Google login/signup for social authentication. All passwords are stored securely in an encrypted format to ensure maximum data protection. Additionally, there is a bonus feature to handle forgotten passwords.

## Features

1. **Sign Up with Email**
   - Users can register for an account using their email address.

2. **Sign In**
   - Registered users can sign in with their email and password.
   - After successful sign-in, users will be redirected to a blank home page where they can find a sign-out button and a reset password button.

3. **Sign Out**
   - Users can sign out of their accounts to ensure secure access to their data.

4. **Reset Password after Sign In**
   - Users who have signed in can reset their passwords for enhanced security.

5. **Password Encryption**
   - All user passwords are stored in an encrypted format to protect sensitive information.

6. **Google Login/Signup (Social Authentication)**
   - Users can use their Google accounts for easy login and registration.

7. **Bonus Feature - Forgot Password**
   - Users who forget their passwords can initiate a password reset process.
   - They can choose to receive either a random password via email or a password reset link, which expires after a specified time (preferred).

## Notifications

The application provides notifications for the following scenarios:

1. **Sign Up**
   - If the passwords provided during sign up do not match, a notification will be displayed.

2. **Sign In**
   - If an incorrect password is entered during sign-in, a notification will inform the user.

## Extra Points

To ensure an added layer of security, re-captcha has been enabled for both sign up and log in processes.

Thank you for using the NodeJS-Auth app! If you have any feedback or encounter any issues, feel free to reach out to us. Happy authentication!
