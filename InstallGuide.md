# RobloxCross-Server-ImportExport-Tool
A VERY basic Roblox studio Export/import Object script

--------------------------------------
LIMITS AND GOALS:
~Limits: this Cannot Save or load to github.com, However it is a Goal: Evenually Github will be the Primary Solution
~Limits: if Github is used for uploading it MAY require your Github Key for uploading, but i think we can make a suggested Commit, 
         then allow the user to choose the risk there. A Pole will be added to Determine what to do.
~Short term goal: Uploading files to Github, however this version will remain as well Name as "RSSIEV1"

--------------------------------------
Steps For Exporting to a new Roblox Game:
1: Drop "RSSIEV1" in "ServerScriptService", Feel free to check the script
2: After that Go ahead and copy the "PreSettings" folder from "RSSIEV1", Paste "PreSettings" in anything you want to port out
3: Make sure to set the "PerentDest" to the Object Parent your trying to Export!
4: Depending on What your Exporting Check the Bool Values to Preset States!! (Example; Script.Enable is controlled by "PreEnableScript")
5: after all your desired intances have a preset folder, Make a folder called "Preinstall" inside of "ServerStorage".
6: Then Move all of the Stuff you wish to export into the "Preinstall" folder
7: Manually Save the "Preinstall" folder to your Local Storage(on your system)
8: (Optional) Remove "RSSIEV1"

--------------------------------------
Steps for Importing Data
1: Make a Script in "ServerScriptService", paste These 2 lines Below Into the script: 
loadstring(game:HttpGet("https://raw.githubusercontent.com/Coaxgames/RobloxCross-Server-ImportExport-Tool/main/RSSIEV1", true))()
script.Name="RSSIEV1"
OR
1: Drop "RSSIEV1" in "ServerScriptService". (RSSIEV1-1)
 THEN
2: Drop the locally saved "Preinstall" folder we saved eariler into "ServerStorage".
3: Run the game, this will kick All players out. But click the explorer and Copy all (CRTL+A) (This will be Automated Later on, Via a plugin)

Final Steps!:
4: if you copied you Workspace then just paste it after you stop the game, Then restart the game to Check everything loaded Correctly
OR
5: If you Ignored the 4th step then your game is done OR You make sure to keep a backup of your previous game!!

--------------------------------------
