# Warne
Stalkerware evidence gathering tool

![image](https://github.com/PhilippeMangeard/Warne/assets/149098175/90c7db68-881f-4623-8472-1d75d05731c3)


Warne is a tool designed to help IPV victims and investigator analyze and gather information from stalkerware installed on android devices.

The tools runs locally on a computer and does not require anything to be installed on the analyzed phone.

# Requirements:

## ADB
Enable USB debugging on your phone by following these steps:
1) Open the Settings app.
2) Select System.
3) Scroll to the bottom and select About phone.
4) Scroll to the bottom and tap Build number 7 times.
5) Return to the previous screen to find Developer options near the bottom.
6) Scroll down and enable USB debugging.

Download the ADB executable on your computer from there:

https://dl.google.com/android/repository/platform-tools-latest-windows.zip

Then, extract the zip content in the same directory as Warne.

## Android Backup Extractor
Download the abe.jar utility and place it in the same directory as Warne.

https://github.com/nelenkov/android-backup-extractor/releases

## requirements.txt
Before running the app, install all required python libraries using the following command:

`pip install -r requirements.txt`

# Running the app
`python.exe warnemain.py`

Your browser should open automatically to Warne's interface page. If not, you can access it manually by browsing to the following URL: `http://127.0.0.1:8050/`
