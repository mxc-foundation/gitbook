# Technical FAQs

**Do I need another M2 Pro near mine to see rewards?**\
No, the M2 pro doesn't require any other miner nearby, because we work on a Proof of Participation model, where each miner gets rewarded for their own work without the need of having other miners around.

**How much electricity and bandwidth does the M2 Pro require?**\
The power consumption of one M2 Pro is less than 3 Watts, and it doesn't require a lot of bandwidth because it uses the LPWAN technology, nor it requires a lot of speed: 10-20 Mbit/s is enough for the miner to work flawlessly. The amount of data used by the miner will depend on the number of devices connected to your M2 Pro.&#x20;

The M2 Pro allows you to mine tokens without bearing huge electricity costs or impacting your internet speed.\
\
**What frequencies does the M2 Pro work on and in what regions?**\
You will be able to find all frequencies per country via[ this link](https://www.thethingsnetwork.org/docs/lorawan/frequencies-by-country/). The M2 Pro supports all of the listed frequencies.\


**Can I change the location of my M2 Pro easily? Do I need to pay a fee for this?**\
Yes, you can change the location of your M2 Pro whenever you want. Simply unplug the miner, and plug it in again in your new location.&#x20;

If you are moving the miner to another country, please check on [this document](https://lora-alliance.org/resource\_hub/rp2-1-0-3-lorawan-regional-parameters/) from the LoRa Alliance to see if the frequencies are the same. If you wish to move to a country with a different frequency, please get in contact with the team using the [Technical Support](https://matchx.io/pages/support) system

**Can I connect the miner via wi-fi?**\
Yes. To do so, please follow this [guide](https://support.matchx.io/hc/en-gb/articles/4414433321489-How-to-connect-M2-Pro-using-WiFi-connection-).

**Can I use the miner as an Access Point to connect other devices to internet via the M2 Pro?** \
No, the Access Point function is just for setup purposes. You cannot use the miner to provide internet connectivity.

**Why do the miner health descriptions show a different number than the dashboard?** \
The miner health description pages are hard coded and are used only as an example. They do not include live information. We agree that this can be confusing, and we are working to make those pages dynamic.&#x20;

**Plugging in your M2 Pro for the first time** \
After the initial “start” the M2 Pro might need to update. Do not unplug it for at least the first 30 minutes! Doing so could interrupt the update, and damage the M2 Pro. During an update the LED will turn purple. So – if the LED is purple, never unplug your M2 Pro.&#x20;

If after 30 minutes the LED is not green, please join the [Telegram Group](https://t.me/mxcfoundation) and report the issue to the moderators. They will guide you on the next steps.\
\
**Different kind of colored LED meanings**\
If your M2 Pro shows a specific colored light, green, yellow, purple and more there's something going on with your M2 Pro. You can simply click the link [here](https://gyazo.com/4004efe2954af801990c03a630b58001), to see what they mean. \
\
**Why my mined tokens aren't showing in the wallet?** \
Since the launch of miner health, miner revenue is visible in Fuel, and not on the “revenue” item in the app. Check every 15 minutes to see if your fuel tank size and content are increasing. If they are, then you’re receiving your MXCs. \
\
**My uptime isn’t reliable. How can I improve it?** \
Uptime is heavily reliant on your local internet provider. Very few internet providers provide any sort of guarantee on whether or not they provide 100% connectivity. In fact, every internet provider often has blips throughout the day. These aren't noticeable for an average user, who logs in, does some tasks and then moves on. In fact, streaming sites like Netflix are well aware of this, and therefore have a "buffer" to store data locally in the event a blip occurs while streaming. Unfortunately these blips affect an M2 Pro's uptime. If you want to check and see if it's an internet provider blip that's causing your issue, follow the steps outlined [here.](https://dev.mxc.org/docs/tutorials/m2-pro/troubleshooting)

Some other times it may be a poor wi-fi connection. This case is rather rare, but it still happens, so it's worth mentioning it here. Try installing the miner via ethernet for 24 hours, then compare the logs and see if the ethernet log is more reliable. You can use a powerline nearby the miner to ensure a better wi-fi coverage, or simply use a different router.

**I keep getting "Error: invalid email", what do I do?**\
First, be sure to type the email manually: copying and pasting the email sometimes creates an extra space at the start or the end of the email, so check for it if you do paste the email. The box is case-sensitive, so when you type the email, be sure to make it all in lower case.

**I forgot the password to access the webpage settings of the miner, what do I do?**\
You need to reset your M2 Pro to default. To do so, press and hold the reset button on the left of the LED for at least ten seconds. The LED will start blinking fast in blue. Release the button, then press again but don't hold it. Wait for the miner to reboot.&#x20;

Once reset, the new username will be 'admin' and the password will be the serial number of the miner. Do not abuse the reset feature. You will not lose your mining rewards resetting the miner, but you will not receive rewards while the miner is offline.

**How do I reboot/power off the miner?**\
There is no power off button. Simply remove the power cord/the ethernet cable if you're using the POE injector, and it will be powered off. Plug it back in to power it on again.
