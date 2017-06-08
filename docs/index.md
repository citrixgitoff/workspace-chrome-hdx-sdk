# HDX SDK for Citrix Receiver for Chrome 

!!!danger "Important"
		 This feature has been verified with the launch of a single app or desktop only.

## Prerequisites 

Citrix Receiver for Chrome supports only the whitelisted third-party Chrome apps. You can whitelist a third-party Chrome app by adding the policy file for Citrix Receiver for Chrome using Chrome management settings




```
{
	"settings": {

		 "Value": {

			 "settings_version": "1.0",

			 "store_settings": {

					"externalApps": [“<3rdParty_App1_ExtnID>”,“<3rdParty_App2_ExtnID>”]


            }


        }


    }


}
```
!!!tip "Note"
		&lt;3rdParty_App1_ExtnID&gt; is used as an example for the name of externalApps and can send messages to Citrix Receiver for Chrome. Get your appid from the `chrome://extensions` site.

## Additional references:

