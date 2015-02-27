# mprint-native
MPrint desktop and mobile app

# Michigan Hackers MPrint Specs

Overview:

To make a desktop and mobile app that will connect to MPrint, allowing the user to print any document from his or her device without using a web browser.

* An app for desktops and mobiles
* Saves Michigan login to device

Minimum Viable Product: Working desktop application that allows user to select which document to print to which UMich printer.

How the App works/ Frontend:
* The user will click on the desktop app and will be presented with the window for selecting which document to print. This will, by default, be the user’s “My Documents” folder.
* After selecting the document to print, user will select “Select a printer” which will open up a search bar to search for a printer name.
* Essentially the same layout as the MPrint website

Backend:
* Need mprint api to access UMich server from desktop
* http://mprint.umich.edu/api

Languages:
* jquery - For pulling and sending requests from websites
* ajax (asynchronous javascript)
* javascript - Frontend and backend (allows jquery and ajax to be used)
* Java - For Android app

* The iOS app we found was written in objective-C. So we could use that or swift.

Creative Assets:
* Icon for desktop/mobile app
* Buttons for printing and options

Things to Do:
* get a list of available printers, starting from near user location
* pull a queue of busy printers
* learn MPrint api
* learn jscript on mprint.umich.edu

iOS app:

https://github.com/davidquesada/BluePrinter
