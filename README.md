# AzureDataSender_SC20260

This App runs on a GHI SC20260D Dev Board, for the GHI SC20100 Dev board the GPIO Pins have to be adapted
This App shows how to write Sensor Data (4 analog Sensors) and up to 4 OnOffSensors to Azure Storage Tables
If 'UseTestValues' is activated automatically created 'SensorValues' are uploaded every 45 sec which will form sinus curves
when viewed with the App Charts4Azure (iOS, Android, Microsoft UWP). The Microsoft UWP Version of Charts4Azure is free of charge.
When the Button 'App' on the board is pressed (hold it some 10 seconds) and released this results in a state change in the On/Off Graph in 'Charts4Azure' 
 
First go to 'Settings to be changed by user' and enter your credentials for your Azure Storage Account 
and your WiFi Credentials
The Credentials can either be entered directly in the Code or can better be located in  .txt files in the folder 'ResourcesSecret'

You can view the data in table form with 'Microsoft Azure Storage Explorer' or the iOS-App 'AzureTabStorClient'
You can view the data graphically with the App 'Charts4Azure'


![gallery](https://github.com/RoSchmi/AzureDataSender_SC20260/blob/master/Pictures/Charts4Azure01.png)
