<h2 align="center">Discord (Optimization).bat</h2>
The Discord (Optimization).bat script moves unnecessary features that are not required by most users to the .backup folder to restore them later in case of problems. This will improve the performance of Discord.

### Functions
1. Kill process Discord.exe (necessary for optimization)
2. Creating backup folders (necessary for mkdir to work as well)
3. Moving noise suppression by KRISP
4. Moving Vulkan
5. Moving the chrome_*.pak files (if using Better Discord - delete the line)
6. Moving game activity (Games from Discord)
7. Moving overlay
8. Moving notifications
9. Moving unnecessary submodules in the voice module
10. Moving unnecessary modules
11. Moving various junk files
12. Moving Update Discord

### Installation Instructions
1. Copy/move Discord (Optimization).bat to the root folder with Discord (%USERPROFILE%\AppData\Local\Discord).
2. Run Discord (Optimization).bat
3. Check the size of the .backup folder. If it is less than 243 MB, try restarting Discord (Optimization).bat.

### IMPORTANT UPDATE INFORMATION
Each time Discord is updated, the files and folders will be re-uploaded, so you will need to re-run Discord (Optimization).bat.

<h2 align="center">Discord (Launcher).bat</h2>
The Discord (Launcher).bat script clears Discord's temporary files and launches it with the desired startup parameters for optimization.

### Installation Instructions
1. Copy/move Discord (Launcher).bat to the root folder with Discord (%USERPROFILE%\AppData\Local\Discord).
2. Run Discord (Launcher).bat
3. Delete the old Discord shortcut and create a new one - Discord (Launcher).bat
