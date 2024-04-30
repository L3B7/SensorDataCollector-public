# Please record measurements with the Trigger method:
0. Grant the permissions
1. Set the timer value (~1-5min)
2. Enable the trigger switch
3. Lock the screen, lay the phone down on the table (or in your pocket), the countdown will start.
4.   When you receive the notification:
     - Pick up the phone
     - Open the screenlock
     - Close the screen and put the phone back into a resting position
To finish the measurement session, turn off the trigger switch.


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
Grant the required permissions based on the Demo video:

https://github.com/L3B7/SensorDataCollector-public/blob/main/.gh_assets/InstallDemo.mp4


If for some reason, the notification listener permission cannot be granted on your device, You can still proceed with the Trigger method.
