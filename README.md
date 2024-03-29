# React_login_auth0
# Auth0 React Login Page

This React application demonstrates a simple login page integrated with Auth0 authentication using the `@auth0/auth0-react` library. The login page is built with optional chaining, allowing for concise and readable code. I have made the social media connection **(google, microsoft)** for better user access in login.

**NOTE:** The node modules files are exempted from uploading because of large size of files.

![Screenshot 2024-01-17 115225](https://github.com/isanthosh2004/React_login_auth0/assets/112749784/cb01bdd7-95dc-4e6b-b298-5f44b09a70a4)

## Features

- **Authentication Buttons**: The app provides a seamless user experience with buttons for both logging in and logging out.

- **Profile Display**: Upon successful authentication, the user's profile information is displayed, including their name, picture, and additional details.

- **Error Handling**: The application gracefully handles authentication errors, providing informative messages to users.
  
![Screenshot 2024-01-17 113949](https://github.com/isanthosh2004/React_login_auth0/assets/112749784/503ef02d-e3af-4d0b-8281-b72c05c19c02)

## Usage

1. **Install Dependencies**: Ensure that the necessary dependencies are installed by running `npm install`.

2. **Set Up Auth0**: Obtain your Auth0 domain and client ID and set them in your environment variables or directly in the code.

3. **Run the App**: Execute `npm start` to launch the development server and view the application in your web browser.

## Optional Chaining

The usage of optional chaining in the code simplifies the handling of potential `null` or `undefined` values, making the code more concise and less error-prone. For instance, the `Profile` component utilizes optional chaining when accessing user properties, ensuring a smooth user experience even if certain information is not available.


