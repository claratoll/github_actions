# How to set up the IOS keys

Add keys to settings in your github projects.
<img width="806" height="99" alt="image" src="https://github.com/user-attachments/assets/94dc18c0-6c64-404b-bab7-e7945214f968" />
Just make sure you do NOT get any extra lines in the keys.



## APPLE_CERTIFICATE
1. Go to https://developer.apple.com/account/resources/certificates/list
and create new certificate - IOS Distribution (App Store Connect)
2. You need a CSR: 
Meny: Keychain Access → Certificate Assistant → Request a Certificate From a Certificate Authority
Upload - and download apple certificate. 
3. Upload certificate to keychain.
4. Export as .p12 and choose a password WHICH YOU NEED TO COPY AND SAVE (scroll down a lil bit)
5. In your terminal: base64 -i MyCert.p12 | pbcopy


## APPLE_CERT_PASSWORD
The password from above



## APPLE_PROVISIONING_PROFILE
https://developer.apple.com/account/resources/profiles/list
Create new profile - Choose: "App Store Connect - Create a distribution provisioning profile to submit your app to App Store Connect."
Generate and download.
In terminal: base64 -i MyProfile.mobileprovision | pbcopy


## APP_STORE_API_KEY
https://appstoreconnect.apple.com/access/integrations/api
Create new key - I've chosen App Manager. 
Download key.
Open in text editor and copy paste to github secrets.


## APP_STORE_API_ISSUER_ID
It's the issuer id that you can see where you find the keys.


## APP_STORE_API_KEY_ID
Is the key id that you can see where you find the keys.
