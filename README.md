REQUIREMENTS
-pyttsx3
-speech recognition
-wikipedia
-webbrowser
-os
-requests
-datetime
-cal_setup
-psutil
-datefinder

IMPORTANT NOTE
- The Google calendar API token has to be refreshed on a weekly basis unless you've signed up your project as one of Google's Co-creators.
- Hence if an error occurs stating that the json file is not found:
    1.Go to consoledevelopers.com and request for a new json Oath file and copy it into the directory
    2.Delete the old token.pkl file and the json file
    3.Run Cal_Setup.py
    4.Run the main program and the Calendar API should work.
