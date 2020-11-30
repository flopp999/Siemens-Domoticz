You need to have some information to be able to use this plugin:  
[Identifier](https://github.com/flopp999/NIBEUplink-Domoticz/blob/main/README.md#Identifier,-Secret-and-URL)  
[Secret](https://github.com/flopp999/NIBEUplink-Domoticz/blob/main/README.md#Identifier,-Secret-and-URL)  
[URL](https://github.com/flopp999/NIBEUplink-Domoticz/blob/main/README.md#Identifier,-Secret-and-URL)  
[System ID](https://github.com/flopp999/NIBEUplink-Domoticz/blob/main/README.md#System-ID)  
[Charge from your electricity company](https://github.com/flopp999/NIBEUplink-Domoticz/blob/main/README.md#Charge-from-electricity-company)  
[Access code](https://github.com/flopp999/NIBEUplink-Domoticz/blob/main/README.md#Access-code)

# Identifier, Secret and URL
Login to [NIBE Uplink API](https://api.nibeuplink.com/)  
Create an application under My Applications  
For Callback URL use "https://api.nibeuplink.com/"  
Copy Identifier, Secret and Callback URL, paste to NIBEUplink hardware in Domoticz  

# System ID
Login to [NIBE Uplink](https://nibeuplink.com/)  
When logged in, look at the address bar, "h<span>ttps://w<i></i>ww.<span>nibeuplink.com/System/xxxxxx/Status/Overview", xxxxxx is your System ID  
Copy your System ID and paste to NIBEUplink hardware in Domoticz  

# Charge from electricity company
You need to add the total extra charge your electricity company have, without taxes

# Access code
You need to create an Access code before first use  
https://api.nibeuplink.com/oauth/authorize?client_id=[IDENTIFIER]&scope=READSYSTEM&state=x&redirect_uri=https://api.nibeuplink.com/&response_type=code
