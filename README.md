# iceQubeMonitor
This code allows for a user to input the IP address assigned to their IceQube AC box to monitor its temperature in PRTG. The threshold can be modify to fit the user's liking.


This can be used for personal monitoring use on your own server, if need be.


# iceQubeMonitor v2
This version will do the same as before plus the following new features:

* added an indefinite loop to constantly check the temperature with giving it a 2 second interval to allow time for temperature to change and update within the code.
* when asking for the IP, it follow up with asking "What is the MAX temperature you want to allow:" so the user can set a value for that. And said value is now an argument in the if-statement.
