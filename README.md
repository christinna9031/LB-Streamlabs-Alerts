# LB Streamlabs Alerts
 LioranBoard extension for Streamlabs alerts not originally covered in LioranBoard. The follower alert in this extension is instant compared to the preinstalled one in LB (which needs to send constant requests to Twitch api).        

The extension comes with premade buttons to make it easier to understand how it works.    

**Streamlabs Alerts INIT** - fill out all the values and refresh your transmitter (or close and reopen LB). The button will be automatically initiated every time you connect to Transmitter. You can retrieve your socket API token at https://streamlabs.com/dashboard#/settings/api-settings  in API Tokens. You can enable/disable alerts you wish to receive.

**Follower Alert** - this button can replace your default Follower button. As it is connected to Streamlabs websocket, the follower alerts are instantaneous.     
Trigger: `SLFollowerAlert`

**Donation Alert** - triggers with any donations coming through StreamLabs.     
Trigger: `SLDonationAlert`  

**Streamlabs Loyalty Points Redeem** - triggers whenever your viewers redeem StreamLabs loyalty points (not to be confused with Twitch channel points). It only retrieves the username and reward name.      
The trigger is `SLPoints <rewardname>`. For example, if your reward name is Test, the trigger name will be `SLPoints Test` (case sensitive).

**Merchandise** - triggers with any product purchased from the Merch Store.      
Trigger: `SLMerch`

**YouTube Subscriber Alert** - triggers with any new YouTube subscribers. Your StreamLabs account needs to be merged with your YouTube account for this to work.       
Trigger: `SLYTSubAlert`


**How to install an extension:**
1. Download the .lbe extension file from **Releases** section (please do not right click and save) 
2. Click on Install Extension in your LioranBoard Receiver
3. Select the extension file you downloaded 
4. Select your default Transmitter you are using. Make 100% sure it is the correct one. 
5. Refresh your Transmitter or close and reopen Lioranboard Receiver. 
6. Most extensions include a premade deck with buttons. If you do not see one, create a new button, add "Send to Extensions" command and select the extension you just installed. If you can only see the extension name with no input fields, it means it was not installed correctly. Repeat steps above.    

[![](https://github.com/christinna9031/LioranBoard-Files/blob/main/img/paypal.png?raw=true)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3YWXYQE3HKWHQ)
