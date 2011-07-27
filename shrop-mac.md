### shrop-mac
**Apps**  
1Password  
Alfred  
Apple Remote Desktop  
Casper    
Casper Suite  
Citrix Receiver    
Colloquy  
Dropbox  
Evernote  
FireFox  
Google Chrome  
GrabBox  
Growl  
HardwareGrowler    
Hazel  
Homebrew  
iLife '11  
iStat Menus  
iWork '09  
MAMP  
Marked  
MindNode Pro  
MPlayerX  
OmniFocus  
OmniGraffle Pro  
OmniOutliner Pro  
Picturesque  
Pixelmator  
Reeder  
Sequel Pro  
Server Admin Tools 10.7  
SizeUp  
Skype  
Snippets  
Sound Studio  
Spotify  
TextMate  
TotalFinder  
Tower  
Transmit  
Twitterific  
VirtualHostX  
VMWare Fusion  

**Configurations**  
General configurations

* Setup suaritadmin account  
* Configure AD (its.uncc.edu) for authentication  
* Add Dropbox folder to the Dock  

System Preferences

* Set the "Computer Name" and "Local Hostname" in "Sharing"
* Turn on "Dock hiding"  
* Turn on "Screen Sharing" for "Administrators" and "mdshrops"  
* Turn on "Show Remote Management status in menu bar"  
* Turn on "Remote Login"  
* Show "displays" options in the "menu bar"  
* Turn off the Wifi menu bar icon  
* Turn off discoverable mode in Bluetooth settings  
* Turn on "Secondary click" in "Mouse" settings  
* Set F5 to show desktop in "Mission Control" settings  
* Setup Time Machine  
* Mail, Contacts and Calendars  
 * Add gmail account Google Chat to iChat  
 * Add AIM account to iChat  
 * Add work Exchange account for mail, contacts and calendars  
 * Add Googla Apps account for mail and calendars  

1Password

* Point to database in Dropbox  
* Select the option to include betas in updates  
* Install all browser extensions  

Alfred

* Setup Dropbox sync  
* Setup Command + Spacebar for action and turn this key combo off for Spotlight  
* Turn on "Enable Clipboard History"  
* Hide hat on Alfred window  
* Default Results  
 * Extras: Folders  

Colloquy  

* Setup connection to shropnet.dyndns.org (See 1 Password for configuration info for the connection)
* Change Appearance style to "Flat"
* Mute all notification sounds  
* Show event bubble option  
 * ...only if Colloquy is in the background  
 * ...and keep on screen until activated  

Evernote  

* Turn off the "Find in Evernote" short cut key as it conflicts with full screen mode in Lion  
* After a clip: Uncheck "Bring the new note to the front"  

Finder  

* Show these items on the desktop: all    
* New Finder windows show: ~/Dropbox  
* Sidebar: Check "Hard disks"  
* Uncheck "Show warnings before changing an extension"  
* Uncheck "Show warnings before emptying the Trash"  
* When performing a search: Search the Current Folder  
* TotalFinder:  
 * Turn on The Asepis Feature
  * Check "Don't write .DS_Store to network"  
 * Tweaks  
  * Check "Hide icon in Menu Bar"  
  * Check "Show Cut&Pate buttons in Context Menus"  
  * Check "Allow path copying from Context Menus"  

Dropbox

* Setup "Selective Sync" as necessary  
* Change icon to black and white  

FireFox  

* Set the home page to "https://citrix.uncc.edu"  

GrabBox  

* Setup the Dropbox Public folder per instructions  
* Settings:  
 * Check "Use random filenames"  
 * Check "Make random filenames longer"  
 * URL Shortener: bit.ly  

Growl  

* Set Growl to launch at login in the Growl preferences  
* Set the display to Smoke and to show in the lower left corner  
* Add HardwareGrowler to login items  

Hazel  

* Set up folder "Downloads" to throw away duplicate files and incomplete downloads after 1 week. Load the same rule sets and select "Old Files" for Downloads.
 * Make sure the Downloads folder is in the Dock  
* Trash: Delete files sitting in Trash for more than 1 week  
* Enable App Sweep and multi-user sweep  
* Setup folder "OmniFocus Backups" ("~/Dropbox/OmniFocus Backups") to user the "Old Files" sample rule  

Homebrew  

* Install in /usr/local 
* Make sure /usr/local is owned by myuser:staff 
* Install drush  
* Install git  
* Install nmap  
* Install svn  

iCal

* Check which calendars to show  

iStats Menu  

* Use black graphs and icons in menubar
* Set combined the following order of items  
 * Menubar Items: CPU  
 * Dropdown Items: CPU, Memory, Disk Usage, Activity, Network and Sensors  
* Set the red date icon and show time as hh:mmAM/PM  

Mail  

* Remove the Apple Mail rule  
* Turn off RSS check for updates  
* Delete the "Apple News" RSS feed in the mailboxes listing  
* Turn off sounds for new mail and sending mail  

MAMP  

* Preferences  
 * Start/Stop  
  * Uncheck all  
 * Ports  
  * Set to default Apache and MySQL ports  
 * PHP  
  * PHP 5.3.6  
  * Cache: APC  

OmniFocus  

* Point backups to "~/Dropbox/OmniFocus Backups"  
* Setup OmniSync Server  
* Turn off "Due Soon" from displaying in the dock icon  
* Set Mail clippings to trigger to the inbox via Ctrl+Command+M. Make sure to install the Clip-O-Tron 3000.  
* Turn on the Mail rule to create OmniFocus actions:  
 * Add mdshrops@uncc.edu and mdshrops@shropnet.net to the allowed email addresses  
 * Archive processed messages in the [Gmail]Trash folder  

Safari  

* Evernote Clipper in the Bookmark bar
* SafariOmnibar - https://github.com/rs/SafariOmnibar  

Sizeup  

* Set Screen Edge Margins to 150px  
* Set Partition to 50px  
* Turn off Send Window Center resize to function   

Snippets  

* Setup symlink "~/Library/Application Support/Snippets" to point to "~/Dropbox/Library/Application Support/Snippets"  

Sound Studio  

* Set color preset to "Green on black"  

Terminal  

* Set theme to Pro  
* Set the font to 14pt  
* Set "When the shell exits" to "Close if the shell exited cleanly"  
* Set IR_Black theme for excellent Terminal colors: http://blog.toddwerth.com/entries/13  

Textmate  

* Setup symlink "~/Library/Application Support/TextMate" to point to "~/Dropbox/Library/Application Support/TextMate"  
 * Includes Bundles: Git, JavaScript JQuery, mCSS, mHTML, PHP Drupal Shropshire, Mark's Bundle and Snippets  
 * Includes the Missing Drawer for TextMate: https://github.com/jezdez/textmate-missingdrawer  
* Turn on line numbers in the gutter  
* Set tabsize to 2 (soft Tabs: Spaces)  
* General Preferences:  
 * Check "Hightlight current line"  
 * Check "Don't create untitled documents"  
* Fonts & Colors Preferences:  
 * Set the theme to "Tomorrow Night"  
* Software Update Prefrences  
 * Watch For: Cutting-Edge  
* Advanced  
 * Shell Variables  
  * TM_ORGANIZATION_NAME = "SUAR IT"  
  
Tower  

* Install the Command Line Tool under the Integration section of the Tower menu  

Twitterific  

* Show Growl notifications for mentions and messages 
* Keep Timeline Scrolled to Top   
* Applications Icons: Do not show in the Menubar  
* Turn off "Play Notification Sound"  
* Bookmarking: Instapaper  