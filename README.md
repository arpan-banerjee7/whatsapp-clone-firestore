This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

![](app_image.JPG)
![](app_image1.JPG)
## Follow these simple steps to have your own whatsapp clone

#### 1: Clone this repo using this command 
`git clone https://github.com/alii13/whatsapp-clone.git`

#### 2: Enter 
`cd whatsapp-clone`

#### 3: Next
`npm install`

#### 4: Goto `src/components` & Find file named `firebase.js` => Replace the config data to your project config data.

![](https://i.ibb.co/DLS72Py/final.png)
Firebase config data you have to replace it with yours & save.

#### 5: Now, Goto `src` directory again and find file named `.firebasesrc`
![](https://i.ibb.co/zhPvYpc/firebasesrc.png)

Replace the line `"default": "your_project__name"` & save.

#### 6: Hit `npm start` in terminal & Boom you have your own whatsapp clone!!  open at port 3000.




## Set Up Hosting in Firebase
####  Hit command : `firebase login `
After logging in you will see this pop up-
![](firebase_login_success.JPG)

####    If error -- 'firebase' is not recognized as an internal or external command, operable program or batch file 
        then run **npm install -g firebase-tools**
#### 1: Hit command `firebase init`

#### 2: Enter Yes

#### 3: Goto the 4th option says - "Configure and Deploy firebase Hosting sites", Use Arrow key to go down & Hit spacebar to select the option and then hit Enter key

#### 4: Enter `build` for directory && select `Yes` for all other options. If you see the prompt given below then hit command `firebase deploy <your project name>`
  Error: No project active, but project aliases are available.

  `Run firebase use <alias> with one of these options:` **firebase use whatsapp-clone-aec86**

  `default (whatsapp-clone-aec86)`
  `whatsappB (whatsapp-clone-aec86)`
  

#### 5: After initialization Completed. Enter 
`npm run build`

#### 6: Now the last command
Enter `firebase deploy`

#### PS : After any new changes in the code : Run the following commands in order- `npm run build` , `firebase deploy`

#### Boom! You have succesfully hosted your firebase app. Click on the link and Enjoy!. Don't forget to rate the repository.
