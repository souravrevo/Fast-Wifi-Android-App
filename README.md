Fast-Wifi-Android-App
=====================

Description:

Fast-Wifi application skips the process of traditional wifi scanning and connection.
It first footprints a location and then connects to the best wifi AP based on the
footprint at that location. We can footprit multiple locations and connect to wifi
in time and energy efficient way.

Features:

1. Footprinting of location
2. Motion sensor support
3. Our own wifi manager implementation
4. Energy and time saving.

<br>
Code Installation guide:

Pre-requisites: Android Development Toolkit (ADT) with Eclipse IDE, JDK, Android 4.0 or higher.

Steps: <br>
1. Create an Android peoject in Eclipse IDE <br>
2. Import the code by importing existing project into your project <br>
3. Clean and Build the project <br>
4. Deploy the application on the Android phone directly by selecting the Android phone while deploying to a target <br>

<br>
Code Running guide:

The application will be installed on your mobile by the name of Fast-Wifi.
Following are the steps for using the application:

1. On the main screen press Connect
2. If you are in new location it will start footprinting and it will take approx 1 minute to footprint
3. Once footprint is saved you can again select connect. Remember it will take 3-4 footprints before the
   application actually saves the current location properly before it connets without scan
4. Once a location is properly footprinted you can connect to wifi without scanning for that location.
