
<h1 align="center">Capture It!</h1>

[![](https://img.shields.io/badge/Made_with-Nodejs-red?style=for-the-badge&logo=node.js)](https://nodejs.org/en/)
[![](https://img.shields.io/badge/IDE-Visual_Studio_Code-purple?style=for-the-badge&logo=visual-studio-code)](https://code.visualstudio.com/  "Visual Studio Code")
[![](https://img.shields.io/badge/Database-MongoDB-green?style=for-the-badge&logo=mongodb)](mongodb.com "MongoDB")
[![](https://img.shields.io/badge/Made_with-Python-blue?style=for-the-badge&logo=python)](https://www.python.org/)



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#features">Features</a></li>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

We have developed a cutting-edge attendance recorder which records attendance of the students using our face recognition model which has an accuracy of about 97%.  Using face recognition, you can easily record attendance and have access to in-depth analysis and a wide range of functionalities. Because of the covid-19 pandemic, stringent guidelines have been established, and precautions must be made to minimise unnecessary physical encounters. As a result, our method has shown to be effective in eliminating the requirement for any type of physical interaction while collecting and analysing attendance.

Detailed explanation of the project is given below.


## Features
1. **Face-recognisation** : By one click teachers can take the attendence of whole classes.
1. **Registration** : Option is provided for the new registration of students and teachers.
2. **Login** : Option is provided for both teacher and students to Login
3. **Dashboard for students** : Option is provided for students so that they can watch all their classes , total lectures he/she attended , and total atttendence of his/her.
4. **Dashboard for teachers** : Option is provided for teachers where they can monitor total classrooms , total students enrolled in his/her class , total lecture he/she taken , total attendence of students , and total mass bunk.
5. **Join classroom** : Option is provided for Students to join their respective classroom.  
6. **Create classroom** : There is an Option is provided to teachers for create new classrooms according to their respective subject.
7. **Add students** :  Option is provided to teachers for add new students in their classrooms.
8. **Attendence list** : Option is provided to teachers for downloading the attendence list of their classroom.
9. **Short attendence** : Option is provided to students for monitoring their short attendence percentage.
10. **Mass bunk** : Option is provided to teachers for monitoring total classes bunked by students.


### Built With

* [NodeJS](https://nodejs.org/en/)
* [ExpressJS](https://expressjs.com/en/starter/generator.html)
* [Python](https://www.python.org/)
* [OpenCV](https://opencv.org/)

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Update to the latest version of npm
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/staticshreyas/Attendance-Portal.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Install Python packages
   
   ```sh
   cd ./Py-Scrpits 
   pip install requirements.txt
   ```

### Running the project
1. Start the express server from the root directory
   ```sh
   npm start
   ```
2. Start the flask server
    ```sh
    cd ./Py-Scripts
      python app.py
   ```
3. Start the mongo server
    ```sh
    mongod --dbpath YOUR_PATH
   ```

## Credits:
- Mentors - Ms. Soumya Tiwari
- Developer - [Sanskriti Sonekar](https://github.com/Sanskriti2308)
