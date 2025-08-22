# InkSpot
Dynamic Background for gnome desktop

![inkspot3](https://github.com/user-attachments/assets/5ab215c3-5bc4-4808-a9e7-ad0f12642cd3)

InkSpot-LowDef

# Description
A simple monochrome Dynamic Background theme for gnome desktop.

The spots change color every 15 seconds creating a subtle and pleasant background.

InkSpot-LowDef is a lower pixel rate (72 ppi), producinging oldschool graphics vibe.

InkSpot-HighDef is made using high pixel rate (300 ppi).

The Dynamic Background can be installed directly into the system backgrounds folder.

Then you can enable using the gnome Settings -> Backgrounds section of your distribution. 

![inkspot1](https://github.com/user-attachments/assets/532ac8fe-bf9a-47fa-8865-911eb9ece1f5)

InkSpot-HighDef

# Installation
Download InkSpot Dynamic Background here: <a href="https://www.gnome-look.org/p/2313312/">https://www.gnome-look.org/p/2313312/</a>

To install, copy files to the system backgrounds folder using root privileges.

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


# Troubleshooting:

 - If new wallpaper is not showing, or shows blank screen, check permissions
 
 - Check folder spelling and location
 
 - You may need to log out and back in


# Uninstall:

 - Open terminal and run following commands
 
 - sudo rm -r /usr/share/backgrounds/inkspot-highdef
 
 - sudo rm -r /usr/share/backgrounds/inkspot-lowdef
 
 - sudo rm -r /usr/share/gnome-background-properties/inkspot-backgrounds.xml


# Extras

Looks great with PhotoCopy Theme:

PhotoCopy Theme here: <a href="https://github.com/therobcox/PhotoCopy">https://github.com/therobcox/PhotoCopy</a>

PhotoCopy Icon Theme here: <a href="https://github.com/therobcox/PhotoCopy-Icons">https://github.com/therobcox/PhotoCopy-Icons</a>

