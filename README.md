# Neptune4Pro

Original Files
-----------------
The Config files i have uploaded are the original configs for the Neptune 4 Pro.
These are to help anyone who needs to go back to default or who as messed up there configs some how :)



Firmware Updates
-----------------
As of 02/09/2023 the Deb file is the latest version 1.2 for the neptune 4 Pro.

Ways to update --

# Use included USB Drive.
create a folder on the root of the device called "ELEGOO_UPDATE_DIR"
add the ELEGOO_APP.deb to the folder.
Put the USB back into the machine go to about on the settings page and click the update button.
after a reboot it should be back on.
if your printer is only showing 1 heated bed instead of 2 then use the printer.cfg i have uploaded to replace the one on the device.


# If you find this error 
GCode path received from Klipper does not match expected path
try this. 
SSH into the printer.
cd ~/moonraker/scrirpts/
sudo sh data-path-fix.sh