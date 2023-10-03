# JATE text Editor

A comprehensive text editor built using JavaScript and Node.js, designed to provide users with a rich text editing experience. A live deployed version of this application can be found by clicking the following link: https://text-editor-bc-cd7e867be109.herokuapp.com/

## Features

- **Rich Text Editing**: Harness the capabilities of the built-in editor to craft and format your text with precision.
- **Database Integration**: Effortlessly save and retrieve your documents with the integrated database system.
- **Offline Capabilities**: Install the text editor on your device and use it without an internet connection.
- **Code Quality**: Integrated with ESLint to ensure consistent code quality throughout the project.

## Getting Started

### Prerequisites

- Node.js
- npm

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Youngobz/Text-Editor.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Text-Editor
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. Start the server:

   ```bash
   npm start
   ```

5. Open your browser and visit `http://localhost:3000` to access the text editor.

## Directory Structure

- `client`: Contains the frontend code for the text editor.
  - `src`: Source files for the client.
    - `css`: Stylesheets for the editor.
    - `js`: JavaScript files handling various functionalities like database integration, editor operations, and more.
  - `.eslintrc`: Configuration file for ESLint.
  - `webpack.config.js`: Webpack configuration file.
- `server`: Contains the backend code.
  - `routes`: Defines the routes for serving HTML files.
  - `server.js`: Entry point for the server.

## Contributing

Feel free to fork the repository, make changes, and submit pull requests. Any contributions are highly appreciated!

## License

This project is open-source. Please refer to the repository's license file for more details.
