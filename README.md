## Snak_Android_Wrapper
A simple Android app which stores a web view rendering the react web app (localhost: 3000).

## Snak
Snak_Android_Wrapper has been created to store the original Snak application:
https://github.com/argykay/Snak

This App was created throughout the course "Technical Interaction Design" at the Masters Programme in Software Development (Design) at the IT University of Copenhagen.

## Creators
Katrine Iversen (kati@itu.dk)
Konstantina Argyropoulou (koar@itu.dk)
Kristin Kallevik (kkal@itu.dk)
Ida Marie Borberg (idbo@itu.dk)

## Run Snak on Snak_Android_Wrapper
If the React App runs on a different than the default localhost: 3000 port, 
do not forget to update line 25 in MainActivity.java file:
--> myWebView.loadUrl("http://10.0.2.2:3000");

## Firebase
Firebase has been added to Snak_Android_Wrapper so that notification messages (Daily Hints) can be sent through the Firebase Cloud Messaging service.
