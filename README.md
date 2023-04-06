An Android Application with a well designed UI and it has the facility to add,edit or delete the note whichever the user want. 
It shows the randomly different colors on every note whenever the user login or signup for notes application.
This application is built with Firebase with email authentication 
Also has a flash screen for 3 seconds


![image](https://user-images.githubusercontent.com/99835981/230466224-4f988b82-a5b0-4d47-8135-03565e1b5fca.png)


First Screen after the flash screen :


![image](https://user-images.githubusercontent.com/99835981/230467196-0a380a7d-45e9-427e-87fa-2f57b846c535.png)


Enter your Email and password and login if you have already registered. Otherwise click on New User! Want To Sign In? button and then 
enter your working email and set a password of at least length of 7.


![image](https://user-images.githubusercontent.com/99835981/230467533-c06be120-61ad-4fdc-8617-03d054ef4a19.png)


User will get the email on the registered email and then he/she has to verify the email first to use the application. 
After verification, simply login with your email and password. Then, you will get the below screen-


![image](https://user-images.githubusercontent.com/99835981/230471487-7db6e35b-1cfe-42ef-ad50-26d0c4da5bef.png)


User can also recover the password if the user forgot the password by clicking on forgot password? on the login screen. 


![image](https://user-images.githubusercontent.com/99835981/230471578-c70cd8d2-1037-4455-88b7-109452dc4fa0.png)


After clicking, user will be directed to below screen. Here, user can enter the registered mail and easily recover the password using Email-
Here, you can add as many notes as you want by clicking on +(plus) icon and clicking on save icon.


![image](https://user-images.githubusercontent.com/99835981/230471762-c42d600c-5ea4-4050-961d-24271362ac47.png)

![image](https://user-images.githubusercontent.com/99835981/230471862-c60dffd5-eefa-4b3b-a175-f0565d5848e4.png)


You will get the detail of desired note by clicking on that note simply. Here, we can also edit the note if desired.
When the user click on menu icon which is shown by three dots at the right side of every note then you get the two functions(edit and delete)-


![image](https://user-images.githubusercontent.com/99835981/230471932-10728de6-fbab-4c98-9da8-fbd150082860.png)


When you click on delete then the particular note is deleted.
If you click on edit then you will move to other screen for editing of note.
If user want to log out from the application then click on three dot menu on the right corner of Action Bar of the notes application-


![image](https://user-images.githubusercontent.com/99835981/230472234-05568c62-65ce-4724-86e9-33052e9d8c06.png)


After this, you will be logged out and directed to the login screen.
Then, you can again login or sign the application if you want. If user enter wrong credentials anywhere then you will got the appropriate toasts everywhere.
Any User Can Sign Anywhere in Any Phone Just by using email and Passwords
 
For Firebase create acccount then Enable Firebase Authentication: In the Firebase dashboard, navigate to the "Authentication" tab and enable the sign-in
methods you want to use for your app. For example, you can enable email and password authentication 
Set up Firebase Realtime Database: In the Firebase dashboard, navigate to the "Realtime Database" tab and create a new database. 
You can choose between a test mode or a locked mode database. Once you have created a database, you can access its URL, which you will need to connect your NotesApp.
Clone the NotesApp repository: Clone the NotesApp repository from Github to your local machine. The repository contains the code for the NotesApp web application
Connect NotesApp to Firebase: In the NotesApp repository, open the "firebase.js" file and replace the Firebase configuration object with your own 
Firebase configuration object. You can find your Firebase configuration object in the Firebase dashboard under the "Project settings" tab.
Deploy NotesApp to Firebase: In the NotesApp repository, run the command "firebase deploy". This will deploy the NotesApp web application to Firebase hosting.
