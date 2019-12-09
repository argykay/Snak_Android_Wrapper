# Snak_Android_Wrapper
A simple Android app which stores a web view rendering the react web app (localhost: 3000).

Snak_Android_Wrapper has been created to store the original Snak application:
https://github.com/argykay/Snak

If the React App runs on a different than the default localhost: 3000 port, 
do not forget to update line 25 in MainActivity.java file:
--> myWebView.loadUrl("http://10.0.2.2:3000");
