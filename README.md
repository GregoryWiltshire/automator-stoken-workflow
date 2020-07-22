# automator-stoken-workflow
Example workflow to use stoken and automator, never pick up your phone again!!!


Dependencies:  
`brew install stoken`  


1. Click on the RSA link in your email and copy the 'ctfData' string value  from the address bar and use it with the command below:  
If you're using an iphone, you may have received your ctfData in your email already..
`stoken import --token='com.rsa.securid://ctf?ctfData=YOUR-CTF-DATA-HERE'`  

2. Enter your PIN as your password

3. Download and install this workflow  

4. Open the worflow in Automator and edit the value for 'YOURPIN' to be your actual PIN (two places in the workflow); CMD+S to save

5. System Preferences > Extensions > Touch Bar > Customize Control Strip; drop quick actions into the default set  

6. You shoud now have a 'RSA-TOKEN' quick action button, try the button in your app of choice, it should come up with a prompt warning for permissions for a 'SERVICESUIAGENT'...  
Enable the checkbox for this, and any other app that pops up when you try to use the quick action button.

To use the button just click any field you want to enter your current RSA token into and hit the button!
Enjoy
