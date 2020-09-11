**Encrypted Mailing Service:**
A Web Based Application to send encrypted mail upto 50 counts to multiple users at a same time.
**_Note:_**

    	———————————————————————————————————————————————————————————————————————

     ***!!!This application is build by me for basic understanding of HTML,CSS,JS!!!***

     ***!!!There may occur some bugs try mentioning in the Issues section!!!***

    	———————————————————————————————————————————————————————————————————————



**Technologies Used:**

_HTML_ - To build the web page (front end)
_CSS_ - Styling the Web Pages
_NodeJs_ - Backend

**Steps to Run the Project:**

_Thanks to https://github.com/VijayasaiVS for his contribution on Front-end and the Encryption Work on this Project!!_

_Server Side_

1. Clone the repository to your computer
2. Make use of a powerful editor (I used Visual Studio Code)
3. Install nodejs in your computer
4. Open the "Encrypted_Mailer" folder through visual studio code
5. Open terminal and type
   "npm install"
   wait for the packages from the "package.json" to install (The process takes place automatically)
6. Enter your own email id and password in _.env_ file to access the email sending API
   _-If you have trouble sending the mail from your account, go to https://myaccount.google.com/security and Turn On "Less Secure App Access"_
7. Type npm start/npm server start to start the application.
8. Visit http://localhost:portno/email.html
9. Woalaaa..! Now you can send your encrypted mails to anyone on the internet.

_Client Side_

1. Open the "Client Side" folder in receiver's side computer.
2. Do the step 2,3,4(here open Client Side folder instead),5.
3. After Successful installation of the modules there are some steps to be done,
   - Go to "https://developers.google.com/gmail/api/quickstart/nodejs"
   - Enable Gmail API for the account to be used in Client side
   - Download 'credentials.json' file (Every account has different configuration file)
   - Your good to go with credentials.json file.
   - After installing required packages type 'node index' in terminal
   - When you run the program for the first time, a link will appear in the terminal! Open it and login to the account from which you want to read the Encrypted mail
   - After successful login you will be given a token to access the account via this program. Paste that in the terminal and your all set to go. Lets encrypt some Mails.
