# BroadcastReceiversAndServicesApp

Created an application to use 5 systems broadcasts 
Create a foreground service with notification. Clicking on the notification will stop the foreground music.
      https://androidwave.com/foreground-service-android-example/
Create an IntentService to create a list of random objects (The objects should have atleast 4 fields including an image). 
Populate the recyclerView in the same activity which starts the intent service.
Pass the data using a broadcast receiver.
Use the AlarmManager to send a notification after 5 secs on clicking each list item. 
The notification should have the object that was clicked on
