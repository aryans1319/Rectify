# Microsoft Engage Mentorship program'22 project 

## Rectify - Automated Exam Proctoring tool for Online Exams using Face Recognition
### 🚩 Overview 
During COVID 19 pandemic, online education has become a common norm in schools and colleges, and students themselves are adapted to this online environment of education, as classes are being held in online mode, exams are also conducted online and students tend to cheat in those exams due to lack of security and no physical guarding by professors/teachers, so here is my solution to the problem!

**Rectify** - An automated online proctoring tool that uses **facial recognition** to detect activities of examinees live during the exam and report live analysis to the professor
This is solely built during the period of **Microsoft Engage Mentorship program'22** conducted by Microsoft provide mentorship and to enrich freshmen with various software development techniques.

#### Problem statement (as given)
To build a fully functional prototype to demonstrate the application of Face Recognition Technology

## 🚩 General Features and Interfaces:
Feature | Images
------------ | -------------
 **Hompage**  
 It is fast, easy to use, and incredibly convenient with a minimalistic UI! To create an exam, just register as an instructor and login to create the exam! | ![homepage](https://user-images.githubusercontent.com/72180855/169327827-c1900a42-36b9-40b0-aff9-c70fec5f9a12.jpg)
**Registration Page** 
You can register as an instructor or register as a student!|![registrationPage](https://user-images.githubusercontent.com/72180855/169329936-754069ba-d581-43a1-8cf2-2eac8b9d1e11.jpg)
**Register as professor!** |![professor](https://user-images.githubusercontent.com/72180855/169717950-bd48965b-bfbf-4054-a7c2-ad6176e949e8.jpg)
**Register as student** | ![student](https://user-images.githubusercontent.com/72180855/169718036-0480ad8c-332d-4982-96ce-e6d403f44022.jpg)
**Login Page** 
User can login as a student or as a professor, authentication system is implemented by using Passport.js | ![LoginPage](https://user-images.githubusercontent.com/72180855/169330053-aaa107cf-23b9-4d45-ade9-ab9929d1128b.jpg)
**Live Teacher Dashboard**  
Professor can watch live status of the students of the ongoing exam by entering the unique code which was generated when the professor created the exam and can monitor student from his own dashboard| ![logcheck](https://user-images.githubusercontent.com/72180855/169719205-8ae815d0-79b4-4065-b95c-3769de13d640.jpg)
**Exam Creation**
Professors can create exam by filling out the form, time and date, exam duration! You can use google forms, microsoft forms,any other form link for exam | ![examCreation](https://user-images.githubusercontent.com/72180855/169330873-a0399556-54a7-46cb-8f18-1bf3b3e652a7.jpg)
**ExamPage**
This is how the exam page looks, allow access to webcam, it starts and recognises the face to start working | ![exampage](https://user-images.githubusercontent.com/72180855/169332552-58b90afd-6613-4bda-991d-aadce99c6293.jpg) 


## 🚩 Features of Live Face Recognition Model:
Feature | Images
------------ | -------------
**Face Visibility** If you try to hide your face from webcam or moveout of the frame it gives a warning after few seconds,that your face is not visible! | ![facenot](https://user-images.githubusercontent.com/72180855/169716958-4f6a6cdc-9b60-48a4-9acc-a2833a084cbe.jpg)
**Multiple Face Recognition** If more than one face is detected during the exam, the model detects it and action is reported to the professor. |![multiple face detection](https://user-images.githubusercontent.com/72180855/169717137-38d3ee73-56f0-46cb-87d3-a15e201932ab.jpg)
**Cell Phone Detection** If any student tries to cheat via phone the model detects it and immediately reports it to the professor then and there | ![cell phone detection](https://user-images.githubusercontent.com/72180855/169334442-3d799e4e-4536-447f-b9c3-4484af2fe74a.jpg) 
**Disabled Copy/Paste** If any student tries to copy any questions to search on the web it immediately detects and report it to the professor as control keys are disable | ![ctrlkey](https://user-images.githubusercontent.com/72180855/169334801-55e0f168-f7c6-4742-a3e2-812376a6a871.jpg)
**Disabled Tab Change** Tab changing is strictly monitored during the live examination, if any student tries to open any other tab, the model detects and reports it immediately to the professor that student is changing the tab as well as the number of times he changed | ![tabchange](https://user-images.githubusercontent.com/72180855/169334996-10b8debe-92a9-4472-adbc-fc20ff78cf81.jpg)
**Prohibited Object Detection!** Some prohibited objects such as books,any other laptop is also detected if any student tries to choose this way of malpractice | ![booldetect](https://user-images.githubusercontent.com/72180855/169391280-b536cf0a-37cc-4203-8ffc-d477f9a373e1.jpg)



## 🌐 Web flow
![Flowchart](https://user-images.githubusercontent.com/72180855/169703099-fdc87bec-c42d-407c-b6a4-23acc41f4e6b.jpg)

## 🚩 Agile methology and workflow:
Agile methology was followed by implementation of sprint of 6 days in a week , continuous integration and development while hosting the app on Heroku.
Customer view points and Teams as an inspiration was taken in mind to develop this project. Bugs were solved according to priority scale
Priority scale : P5 (maximum) to P1 (Least)

| Week | Task |  Remarks |
|------|:----:|---------|
| 1    | **Design & Setup phase** P4: Basic app built by exploring technologies  , P3: Setup server node.js , express , passport.js, react.js, tensorflow.js  P2: Setting up the authentication system and database  |   Successfull setup implementation, authentication system, mongodb successfully connected            |
| 2    | **Face Recognition Model** P4: Building the face recognition custom model using tensorflow , P3: Integration of Model with React and Node.js, P2: Testing Recognition Features , P5: CocoSSD Model Pixel passing to Node.js(Bug)     |    All bugs resolved & Implemented Successfully            |
| 3    | **Build Phase** P4: List of Participants appearing for the exams, P5: Student logs error , P3: Implementing dynamic logs with sort by name,email functionalities, no of entries per page by unique code P5: Advanced Search Functionalities(Bug) , P4: Video call connection     |     Problem statement tasking completed|
| 4    | **Deployment and Design** P4: UI Fixes, Exam Restart Feature within given time **Testing and review** P3:Hosting on Heroku , P5: Service unavailable error 505 (Bug) , P4: Homepage , P3:Manual Testing of every feature  |    Task completed     |

##  🚩 Technologies used:
![Purple Modern Aries Sun Sign Horoscope YouTube Thumbnail](https://user-images.githubusercontent.com/72180855/170594821-a0ac2c95-b8db-4ac9-b20b-9d6b5425500c.png)

#### Programming Languages : <img alt="NodeJS" src="https://img.shields.io/badge/node.js-%2343853D.svg?style=for-the-badge&logo=node-dot-js&logoColor=white"/><img alt="JavaScript" src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/> <img alt="HTML5" src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"/> <img alt="CSS3" src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"/><img alt="Bootstrap" src="https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white"/><img alt="jQuery" src="https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white"/> 
#### Face Recognition Model : 
#### Version Control : <img alt="Git" src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white"/>  
#### Hosting :<img alt="Heroku" src="https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white"/>
####  Frameworks/Libraries : Express , Passport.js , Tensorflow.js
###### You can also see the list of dependencies in the package.json file.

## 🚩Installation/Environment Setup 

  #### 1. Clone App
  
  * Write the following command and press enter.
  
  ```
    $ git clone https://github.com/aryans1319/Rectify.git
  ```
    
 #### 2. Install node packages
  * Move to the parent/root directory (Rectify) cd Rectify
  * Write the following command and press enter to download all required node modules.
 
   ```
   $ cd Rectify
   $ npm install 
  ```
  
#### 3. Move to Client directory and install Node packages
 * Move to the client folder inside the Rectify folder by cd client
 * Write the following command and press enter to download all required node modules. 
 
 ```
   $ cd client
   $ npm start
 ```

 #### 4. Run Locally
  * Move back to the parent directory by cd..
  * While you are still inside the cloned folder, write the following command to run the website locally.
 
 ```
   $ npm run dev
 ```
 
 
 ###### NOTE: This concurrently runs server and frontend, give a few seconds for frontend to load and the port by default will be ```http://localhost:3000/```
 
 
## 🚩 Future Scopes:-

Feature | Explanation
------------ | -------------
Creating Exam Feature in the application itself| Instead of using a external link(google/microsoft forms),exam creation in the web-application itself would provide more security and better user experience to the product.
Class Management | All class management activities (branch/section wise) separately for every year students, creating assignment in the application itself assigning tasks and keep a record of every student activites individually in different sections.
Video Calling support | Video calling support between students and teacher for quick doubt resolve and better teacher to student interaction

Thank you ! Microsoft Team for such a wonderful mentorship program ❤️
You can also check [My weekly record during this program](https://docs.google.com/document/d/1tiDQlXSs6BUe6wVWzlbyqzxnwrio0emJkBpMfHyfSJo/edit?usp=sharing)
