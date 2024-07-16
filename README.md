# PWA Text Editor
<img width="720" alt="Screenshot 2024-07-16 at 12 41 17 PM" src="https://github.com/user-attachments/assets/d361656d-5a5a-49ef-b9b3-0745dac5a9d2">

## Description

This project is a Progressive Web Application (PWA) text editor that runs in the browser. It features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also functions offline.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Installation

To install this application, follow these steps:

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/yourusername/pwa-text-editor.git
   ```

2. Navigate to the project directory:
   ```
   cd pwa-text-editor
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Build the application:
   ```
   npm run build
   ```

5. Start the server:
   ```
   npm run start
   ```

The application should now be running on `http://localhost:3000`.

## Usage

1. Open the application in your web browser.
2. Start typing in the text editor.
3. Your content will automatically be saved as you type.
4. To install the application as a PWA, click the "Install!" button in the header.

## Features

- Create notes or code snippets with or without an internet connection
- Reliably retrieve them for later use
- Automatic saving of content in the text editor
- Offline functionality
- Ability to install as a PWA

## Technologies Used

- HTML/CSS/JavaScript
- IndexedDB for client-side storage
- Webpack for bundling JavaScript files
- Workbox for service worker and PWA functionality
- Babel for backwards compatibility
- CodeMirror for the text editor interface

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License.

---

For any additional questions or comments, please contact Patrick Riedinger at [patried7@gmail.com]. Github: [https://github.com/pattyboyy]
