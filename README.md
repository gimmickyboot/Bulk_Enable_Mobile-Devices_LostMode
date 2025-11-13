# Bulk Enable Mobile Devices LostMode
Use these scripts to enable lost mode on either staic or smart groups of mobile devices

`bulk_enable_mobile-devices_lostmode-pro.sh` requires Jamf Pro v11.21 or later. If in doubt, use the classic version

## How to use
1. download the required script
2. set the following variables (don't modify the single or double inverted commas)
   - username
   - password
   - url
   - groupID - this is the ID of the staic or smart group
   - lost_mode_message
   - lost_mode_phone
   - lost_mode_footnote
   - always_enforce_lost_mode (classic only)
   - lost_mode_with_sound (classic only)
   - play_lost_mode_sound (pro only)
3. run the script
