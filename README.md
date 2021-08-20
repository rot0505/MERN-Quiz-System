<div align="center">
    <h1>Alharamain Games</h1>
</div>

## 🎓Overview

QUIZ is a web application for all kinds of users. Students can play quiz without anything and teachers can add quizzes.

## 💡Live Preview

Take a look at the live <a href="https://localhost:8000/" target="_blank">Preview of the app.</a>.

![Quiz Demo](https://user-images.githubusercontent.com/46846821/113098567-12f45080-9212-11eb-84f4-a4e9092453e1.gif)


## ✨Functional Requirements

- ### Teacher

  - The teacher should be able to create quizzes.
  - The teacher should be able to control the access to quizzes.
  - The teacher should be able to copy and share the quiz - code.
  - The teacher should be able to view/ delete the responses.

- ### Student

  - The student should be able to attempt a quiz by using the quiz code.
  - The student should be able to attempt the quiz using voice recognition.
  - The student should be able to see their scores in the attempted quizzes.

## Blind Quiz Commands

- The Blind Quiz Module works with the limited Speech Commands to interact with the App.
- Press `space` to turn the microphone on.
- Voice Commands:
  - `Instructions`: To listen to all the possible commands.
  - `start Quiz` or `title`: To listen the Quiz title and first Question.
  - `Select Option [Number]` or `Choose Option [Number]`: To mark the option of the current Question.
  - `next question`: to increment the question index and move to the next question and listen it.
  - `previous question`: to decrement the question index and move to the previous question and listen it
  - `Repeat Question [Number]`: To listen a specific Question.
  - `Repeat Current Question`: To repeat the current Question.
  - `submit quiz`: to submit the quiz.

## 🚀 Configuration Guidelines

- Create an account on firebase.google.com and add the API key in the src/firebase/firebase.js file.
- Add the MongoDB API key (either local server key or from the Atlas MongoDB remote server) in backend/src/server.js.
- Install MongoDB Server if you want to use the database locally.
  Install Node.js to use npm and node services.
- Open a terminal with the path set to the root directory of the project and run `npm install` command to install the required packages.
- Open a new terminal with the path set to the backend directory of the project and run `npm install` command to install the required packages.
- After successful installation of all packages, run command `npm start` in the terminal with the path set to the root directory and wait for the project to initiate.

## Supported Environments

- Windows/ macOS/ Linux operating systems are supported for the development of the respective project.
