# SensorDataCollector
## Data Collection App for Gesture based User Authentication
The goal of this app is to record measurements of people picking up the phone from the table or a pocket.
These measurements collected by the different on-board sensors will be used to test the theory on a larger scale that the the pickup motion can be used to uniquely identify and authenticate smartphone users.

## Snooping method
This app uses a permission that lets it detect (and read the content) of every notification received. This permission is neccessary to let the app detect incoming notifications to trigger a measurement.
By no means does the app access or save the content of the notifications, it only uses meta information about the notification (~channel, importance) to filter out silent ones.
This method is used for the non-superwised measurement called "Snooping".
## Trigger method
The secondary measurement method is the "Trigger" option.
You can set up a timer, activate the Trigger option and when you close the screen, a countdown will start. After the countdown, if the device screen is off, a notification will prompt you to pick up the phone and unlock it. This concludes a single measurement.
Closing the screen now will automatically restart the timer.

(You should not reset the counters, unless otherwise instructed to do so.)
## Install the app with the provided apk.
You should be greeted with the following screen:  

  
<img src="https://github.com/L3B7/SensorDataCollector/assets/64687912/e6cf8efa-3db3-4ed9-87db-002f766f9383" alt="Main View" style="width:30%">

## Grant permissions
Open the settings and click on each 3 permission buttons in the menu.  
The battery and storage permissions should be straight forward.  
<img src="https://github.com/L3B7/SensorDataCollector/assets/64687912/7862ea13-56ce-49a3-b656-436dd2065773" alt="Settings" style="width:30%">
<img src="https://github.com/L3B7/SensorDataCollector/assets/64687912/d37daf34-5ba0-4850-907c-cc34221fadad" alt="Image 2" style="width:30%">


If the permission is restricted, please navigate to your application list, find SensorDataCollector, and chose the option from the top right corner to allow restricted permissions.


<img src="https://github.com/L3B7/SensorDataCollector/assets/64687912/735e346c-c0d1-4ce9-8219-13121065db09" alt="Image 3" style="width:30%">
<img src="https://github.com/L3B7/SensorDataCollector/assets/64687912/973128d9-0396-40ec-a49f-a8f6c11850da" alt="Image 4" style="width:30%">



