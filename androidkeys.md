# How to add android keys

Add keys to settings in your github projects. 

<img width="806" height="99" alt="image (4)" src="https://github.com/user-attachments/assets/ddb63978-1f47-4d3a-9046-97f69d5b2577" />

Just make sure you do NOT get any extra lines in the keyes.




## GOOGLE_PLAY_CREDENTIALS
Go to Google Cloud Console and create a new service account:

<img width="687" height="90" alt="image" src="https://github.com/user-attachments/assets/fbdf5f8a-3f1b-4c54-a359-2afed590df7d" />

Go to keys - add new key - json type - download.
Add the json text to the GOOGLE_PLAY_CREDENTIALS variable.
On Google Play Console you need to invite the new account you've created with the unique email. Add the app you want to connect to it, and give permission to publish in test channels and/or production channels. 



## KEYSTOREBASE64
Go to the terminal and write "base64 -i /path/to/key/upload-keystore.jks | pbcopy" - copies the text to your clipboard.



## KEYSTOREPASSWORD
Password you set up for you project in Android Studio

<img width="300" height="35" alt="image" src="https://github.com/user-attachments/assets/60c18575-52f5-4d8f-a3b1-2199de881855" />



## KEY_ALIAS
Alias you set up for you project in Android Studio

<img width="314" height="43" alt="image" src="https://github.com/user-attachments/assets/5cee8ff5-d10a-4cc5-9864-a0fbb34b9d40" />



## KEY_PASSWORD
Password you set up for you project in Android Studio

<img width="334" height="50" alt="image" src="https://github.com/user-attachments/assets/99cd8b45-ff8d-4043-ae7b-ff84c7346dec" />
