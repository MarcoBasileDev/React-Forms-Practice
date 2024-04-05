# React-Forms-Practice

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

## Overview

The React Registration and Login Forms project is a simple web application built using React. It includes both registration and login forms, and serves as a comprehensive exploration of different approaches to handling form data and user input in React.

This project consists of three versions, each utilizing a different approach for managing form data:

- Version using Component State
- Version using Refs
- Version using Browser APIs (FormData)

# Features

## Version using Component State

- Utilizes React component state to manage form data and user input.
- Demonstrates basic form handling techniques using useState hook.
- Implements form validation logic directly within component functions.

## Version using Refs

- Utilizes React refs to access form elements and manage user input.
- Demonstrates an alternative approach to form handling without relying on component state.
- Utilizes useRef hook for maintaining mutable references to form elements.

## Version using Browser APIs (FormData)

- Utilizes browser APIs, specifically FormData, for handling form data.
- Provides a low-level approach to form handling, interacting directly with browser features.
- Demonstrates how to create and manage FormData objects for form submission.

## Setup and Installation

- clone the repository: git clone
- Navigate to the project directory.
- Install dependencies: npm install
- Run the development server using: npm run dev

Change the component displayed inside the app.jsx to test all the different approaches.

## Technologies Used

**Frontend**: React, JavaScript, HTML, CSS.

## Why Three Versions?

The decision to create three versions of the React Registration and Login Forms project was driven by the desire to explore various approaches to form handling in React:

- **Component State:** This version demonstrates the basic approach of using component state to manage form data, providing a straightforward solution for small-scale applications.

- **Refs:** By utilizing React refs, this version showcases an alternative method of form handling that doesn't rely on component state, offering flexibility in managing form inputs.

- **Browser APIs (FormData):** This version takes advantage of browser APIs, specifically FormData, for handling form data, providing a more direct interaction with browser features and allowing for more granular control over form submission.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.
