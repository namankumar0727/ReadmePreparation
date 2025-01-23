# NGO-Helper Documentation

## Directory Structure

The **frontend** folder contains all the necessary files and directories for the React frontend of the project. Below is the directory structure:

### frontend/


```
 ├── public/

    Contains static assets like the main HTML file

 ├── src/

    Main source code directory for the React application

 ├── .gitignore

    Specifies files and directories to ignore in Git

 ├── eslint.config.js

    ESLint configuration file for code quality

 ├── index.html

    Entry point HTML file for the app

 ├── package-lock.json

    Dependency lock file for consistent installations
 
 ├── package.json

    Project metadata and dependency list

 ├── postcss.config.js

    PostCSS configuration for CSS processing

 ├── README.md

    Documentation file for the project

 ├── tailwind.config.js

    Tailwind CSS configuration for customizing styles

 └── vite.config.js

    Vite configuration for development and build

```
### Folder and File Descriptions

- **/public/**  
  Contains publicly accessible files like `index.html` and static assets. These files are not processed by Webpack or Vite.  

- **/src/**  
  The main directory for developing the application, including React components, pages, and styles.

- **.gitignore**  
  Specifies files and directories (e.g., `node_modules`, `.env`) that Git should ignore.

- **eslint.config.js**  
  Configuration file for ESLint, used to maintain code quality and consistency.

- **index.html**  
  Entry point HTML file that serves as the template for the app.

- **package-lock.json**  
  Automatically generated file to ensure consistent dependency versions across environments.

- **package.json**  
  Contains project details like its name, version, scripts, and dependencies.

- **postcss.config.js**  
  Configuration file for PostCSS, used alongside Tailwind CSS to process styles.

- **README.md**  
  A markdown file providing an overview of the project, installation steps, and other helpful information.

- **tailwind.config.js**  
  Custom configuration for Tailwind CSS to define themes, colors, and plugins.

- **vite.config.js**  
  Configuration file for Vite, handling build and development server settings.
  
## Dependencies and Libraries


Below is the list of dependencies and libraries used in the project:


### Dependencies
- **React** - A JavaScript library for building user interfaces.
React Router DOM - Handles routing and navigation in the React application.
Tailwind CSS - A utility-first CSS framework for styling.
PostCSS - A tool to transform styles with JavaScript plugins.
Vite - A build tool that is fast and optimized for modern web development.
Development Dependencies
ESLint - For maintaining code quality and consistency.
Prettier - A code formatter to ensure consistent style.
Autoprefixer - Adds vendor prefixes to CSS rules automatically for compatibility.
System Requirements
To run this project, ensure your system meets the following requirements:

Software
Node.js: Version 16.0.0 or higher.
npm: Version 7.0.0 or higher (comes with Node.js).
Hardware
Operating System: Windows, macOS, or Linux.
Memory: At least 4GB of RAM (8GB recommended).
Storage: At least 500MB of free space for dependencies and build files.
