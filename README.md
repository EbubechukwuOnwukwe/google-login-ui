# Google Login UI with Animation

This project is a simple, animated Google Login UI built using HTML, CSS, and JavaScript. It incorporates a Google Sign-In button for OAuth login and includes custom animations for a visually appealing user interface.

## Features

- **Google OAuth Integration**: Allows users to log in using Google OAuth 2.0.
- **Responsive Design**: The UI is responsive and works on different screen sizes.
- **Custom Animation**: Background spans animate with a gradient effect, adding a dynamic touch to the login page.
- **Clean UI**: Modern and minimalist design with smooth transitions.
  
## Technologies Used

- HTML5
- CSS3 (including keyframe animations)
- JavaScript
- Google OAuth 2.0
- [Google Fonts - Quicksand](https://fonts.google.com/specimen/Quicksand)

## How to Run

### Prerequisites

Before you begin, ensure you have the following:

- A Google Cloud project with OAuth credentials set up. You’ll need the client ID to replace the placeholder in the `meta` tag for Google Sign-In.
  
### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/EbubechukwuOnwukwe/google-login-ui.git
   ```

2. Navigate to the project directory:
   ```bash
   cd google-login-ui
   ```

3. Replace the `YOUR_CLIENT_ID` in the `meta` tag in the `index.html` file with your actual Google OAuth client ID:
   ```html
   <meta name="google-signin-client_id" content="YOUR_CLIENT_ID.apps.googleusercontent.com">
   ```

4. Open `index.html` in your browser to see the animated login page.

## Google OAuth Setup

To integrate Google OAuth, follow these steps:

1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project or use an existing one.
3. Navigate to the **Credentials** section and click on **Create Credentials**.
4. Choose **OAuth 2.0 Client IDs** and configure the consent screen.
5. Add your redirect URIs (or leave it blank for now).
6. Copy the generated **Client ID** and replace it in the `index.html` file.

## Demo

![Google Login Demo](https://link-to-gif-or-image-of-demo)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to open a pull request or an issue if you have suggestions or improvements.

## Contact

For any questions or feedback, contact [Ebubechukwu Onwukwe](mailto:ebube5298@gmail.com).
