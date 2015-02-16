# Find Free Stuff

Find Free Stuff is an Android application in development by Team 1 for CS121: Software Development being taught in the Spring of 2015 at Harvey Mudd College by Jessica Wu. The goal of this application is to provide a platform for to connect people who are looking to get rid of things they own but do not wish to without incurring waste or expense with people who are looking to acquire new things for free.

# Requirements
This project relies on the [Google Play Services SDK](https://developer.android.com/google/play-services/setup.html), and the [Parse SDK](https://parse.com/apps/quickstart#parse_data/mobile/android/native/existing). This also relies on the Google Maps API to be properly set up for this app with your computer. First, navigate to [this](https://developers.google.com/maps/documentation/android/start#display_your_apps_certificate_information) page and go through the section "Displaying the debug certificate fingerprint". From this, copy down the "SHA1" portion of the output. Go to the [Google Developers Console](https://console.developers.google.com/project) and sign in (with the project email, the project Find Free Stuff should already exist). Select the Find Free Stuff project, and under the left menu bar select "APIs & auth/Credentials". From this page, you will see a button to "Create new Key". Press this button and when prompted, select the "Android Key" button. Then, in the space provided, enter the "SHA1" output you copied earlier followed by ";edu.hmc.sp15.cs121.findfreestuff" and press the "Create" button. Then, on the page the "API KEY" should be displayed along with additional information. Place the "API KEY" as described in the [Google Maps API description](https://developers.google.com/maps/documentation/android/start).