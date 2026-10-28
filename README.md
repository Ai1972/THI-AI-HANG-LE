# Product Level Blocking Demo

Note: Must use a pinpad that supports handling of the "PLB" PAD Tag (Transactions will work regardless, however blocking occurs in the pinpad). Product level blocking should only occur on associated cashless debit cards when the PLB flag is sent down as '1'.

## Sending Product Level Blocking

Select the PAD to send from the 'Send PLB Data?' drop down box as shown below.

![DROP_DOWN_3](README_PICS\DROP_DOWN.PNG)

![DROP_DOWN](README_PICS\DROP_DOWN_2.PNG)

![DROP_DOWN_2](README_PICS\DROP_DOWN_3.PNG)

```
Don't Send PLB In Transaction = Send PAD as ""
Send PLB As Enabled = Send PAD as "PLB0011"
Send PLB As Disabled = Send PAD as "PLB0010"
```

When a transaction is sent with PLB enabled with a DSS card used, the POS will display as such:

![ERROR_RESPONSE](README_PICS\ERROR_RESPONSE.PNG)

## Connecting To The Pinpad/Client

If the POS is having issues connecting to the pinpad or client, click on the gear on the top right of the window

![SETTINGS_ICON](README_PICS\SETTINGS_ICON.PNG)

Then confirm that the server address is correct and press the refresh button to the right of the textbox

![SETTINGS](README_PICS\SETTINGS.PNG)

