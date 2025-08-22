InkSpot Dynamic Wallpapers by robcox
________________________________________

To install, copy files to the system backgrounds folder using root privileges

 - Extract InkSpot.tar.xz to Downloads folder
 
 - Right-click InkSpot folder and select "open in terminal"
 
 
Copy theme folders to backgrounds and change permissions to root
 
 - sudo cp -r inkspot-highdef inkspot-lowdef /usr/share/backgrounds/
 
 - sudo chown -R root:root inkspot-highdef inkspot-lowdef
 
 - sudo chmod -R 755 inkspot-highdef inkspot-lowdef
 
 
Copy inkspot-wallpapers.xml to gnome-background-properties and change permissions

 - sudo cp inkspot-wallpapers.xml /usr/share/gnome-background-properties/
 
 - sudo chown -R root:root inkspot-wallpapers.xml
 
 - sudo chmod -R 755 inkspot-wallpapers.xml 

 
To set new wallpaper, use Settings -> Background or right-click desktop "Change Background..."


Troubleshooting:

 - If new wallpaper is not showing, or shows blank screen, check permissions
 
 - Check folder spelling and location
 
 - You may need to log out and back in
 
 
Uninstall:

 - Open terminal and run following commands
 
 - sudo rm -r /usr/share/backgrounds/inkspot-highdef
 
 - sudo rm -r /usr/share/backgrounds/inkspot-lowdef
 
 - sudo rm -r /usr/share/gnome-background-properties/inkspot-backgrounds.xml
 
 Enjoy!!
 
