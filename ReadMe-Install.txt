InkSpot Dynamic Wallpapers by robcox
________________________________________

To install, copy files to the system backgrounds folder using root privileges
Repeat process for both wallpaper themes

 - Extract InkSpot.tar.xz to Downloads folder
 
 - Right-click InkSpot folder and select "open in terminal"
 
 - Run command: sudo cp -r inkspot-lowdef /usr/share/backgrounds/
 
 
Change owner and permissions to root

 - sudo chown -R root:root inkspot-lowdef
 
 - sudo chmod -R 755 inkspot-lowdef
 
 
Copy dynamic-wallpapers.xml to gnome-background-properties folder

 - sudo cp dynamic-wallpapers.xml /usr/share/gnome-background-properties/
 
 - sudo chown -R root:root dynamic-wallpapers.xml
 
 - sudo chmod -R 755 dynamic-wallpapers.xml
 
 
To set new wallpaper, use Settings -> Background or right-click desktop "Change Background..."


Troubleshooting:

 - If new wallpaper is not showing, or shows blank screen, check permissions
 
 - Check folder spelling and location
 
 - You may need to log out and back in
 
 
Uninstall:

 - Open terminal and run following commands
 
 - sudo rm -r /usr/share/backgrounds/inkspot-highdef
 
 - sudo rm -r /usr/share/backgrounds/inkspot-lowdef
 
 - sudo rm -r /usr/share/backgrounds/dynamic-backgrounds
 
 Enjoy!!
 
