# Mac Phish

Author: ahhh
Version: Version 1.0

## Description

Credz to Fuzznop for introducing me to the technique: http://fuzzynop.blogspot.com/2014/10/osascript-for-local-phishing.html
Using ducky script, it opens a terminal and uses the osascript command in an attempt to social engineer the root password, then saves this back to bash bunny in the loot dir

## Configuration

This is configured for Macbooks as a keyboard, opens terminal via spotlight 

## STATUS

| LED              | Status                                |
| ---------------- | ------------------------------------- |
| Blue             | Setup                                 |
| Amber            | Running the scripts                   |
| Green            | Finished                              |

## Future features and expansions on this branch:
-Divide the script into modules
-Edit text for alert, assure user that no restart will be required and that it is a critical update
-Schedule cron job to start after 5 minutes, edit script to pop back up if they hit cancel or enter the wrong password
-Exfil
-Attempt enabling ssh, at least open a bind shell
