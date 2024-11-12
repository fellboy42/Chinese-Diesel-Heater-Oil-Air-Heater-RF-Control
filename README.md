
update video_live_install_rf_control sh.txt works on RPI ZERO 
works on RPI2, RPI4


script i made for my work shop to automate chinese  oil air heater for remote control from any where on the loacl network with help from https://github.com/milaq/rpi-rf/tree/master thanks
Key Changes Made to html
Confirmation Dialog:
Before executing the command, a confirmation dialog is displayed using confirm().
The message in the dialog is dynamically generated based on the command being executed (e.g., "Are you sure you want to turn on the heater?").
Early Exit:
If the user clicks "Cancel" in the confirmation dialog, the function exits early, preventing the command from being sent.
Benefits
This approach helps to reduce the risk of accidental commands by requiring user confirmation, making the interface safer and more user-friendly.
