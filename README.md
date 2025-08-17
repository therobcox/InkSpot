# InkSpot
Dynamic Wallpaper for gnome desktop

![inkspot3](https://github.com/user-attachments/assets/5ab215c3-5bc4-4808-a9e7-ad0f12642cd3)

InkSpot-LowDef

# Description
A simple monochrome Dynamic Wallpaper theme for gnome desktop.

The spots change color every 15 seconds creating a subtle and pleasant background.

InkSpot-LowDef is a lower pixel rate (72 ppi), producinging oldschool graphics vibe.

InkSpot-HighDef is made using high pixel rate (300 ppi).

The Dynamic Wallpapers can be installed directly into the system backgrounds folder.

Then you can enable using the gnome Settings -> Backgrounds section of your distribution. 

![inkspot1](https://github.com/user-attachments/assets/532ac8fe-bf9a-47fa-8865-911eb9ece1f5)

InkSpot-HighDef

# Installation
To install, copy files to the system backgrounds folder using root privileges.

Repeat process for both wallpaper themes.

 - Extract InkSpot.tar.xz to Downloads folder
 
 - Right-click InkSpot folder and select "open in terminal"
 
 - sudo cp -r inkspot-lowdef /usr/share/backgrounds/

  
Change owner and permissions to root

 - sudo chown -R root:root inkspot-lowdef
 
 - sudo chmod -R 755 inkspot-lowdef

 
Copy dynamic-wallpapers.xml to gnome-background-properties folder

 - sudo cp dynamic-wallpapers.xml /usr/share/gnome-background-properties/
 
 - sudo chown -R root:root dynamic-wallpapers.xml
 
 - sudo chmod -R 755 dynamic-wallpapers.xml
 
 
To set new wallpaper, use Settings -> Background or right-click desktop "Change Background..."


# Troubleshooting:

 - If new wallpaper is not showing, or shows blank screen, check permissions
 
 - Check folder spelling and location
 
 - You may need to log out and back in
