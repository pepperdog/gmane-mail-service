# gmane-mail-service
An Automator service that opens up the gmane page for the selected message in MacOSX Mail.app

## Directions
* Open up a Finder Window
* cmd-shift-G, type "~/Library/Services"
* drop gmane.workflow in to the Services folder
* restart Mail
* You may want to Mail->Services->Services Preferences... and add a key equivalent for this item.

## Bugs
If you are in threaded mode, you can't get it to open up the message you're focused on. This service is only smart enough to know which message or messages you have selected in the list view. Anybody who's an AppleScript guru is welcome to make it better.

