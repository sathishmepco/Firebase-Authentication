# Firebase-Authentication
Demo project for showing different methods of Firebase Authentication
- Email Password Authentication
- Phone Number Authenticationeasy way to integrate google signin into your project. 
- Google Sign in with Firebase
- Passwordless Authentication

# How to run this project?
- Check out this source code
- Create project in Firebase (with package name and certificate fingerprint)
- Place "google-services.json" file in the path /Poject Dir/app
- Build the project
- In this githup repo google-services,json is not uploaded, so please don't forget to add google-services.json.

# Download the Apk
<a target="_blank" download="CommonNotes.apk" href="/app/release/Firebase%20Authentication.apk?raw=true"> Click here to download the apk file </a>

# Email Password Authentication
    In this method, user can register with his email id and password. If this user is already have a account then he can login with the same credential. Firebase provides password reset mechanism also.
    
# Phone Number Authentication
    Firebase sends OTP to the phone number which user enters to login. Phone number should be mentioned with the proper country code like this +919500834848
    
# Google Sign In
    Firebase provides easy way to integrate google signin into your project. Also it provides way to manage google signin accounts in firebase Console. 
# Passwordless Authentication
    This method will be very helpful where the user don't want to remember their username and password. This authentication sends a authenction link to user's email id. When the user clicks on the link, then user redirected to the corresponding app.
    
<img src="/Firebase Authentication.png"/>
<img src="Email Password Authentication.png" />
<img src="Phone Number Authentication.png" />
<img src="Phone Number SignedIn.png" />
<img src="Google Signin.png" />
<img src="Passwordless Login.png" />
