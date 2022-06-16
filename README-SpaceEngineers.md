# unraid-templates
In order for the server to start, there are still a few steps that need to be taken.

- After the Docker has been installed and all files have been downloaded. Stop the server, go to user/appdata/SpaceEngineersDedicated/Instances.
- Upload the SpaceEngineers-Dedicated.cfg there. In the file itself, you can change the following parameters yourself.
    Under Administrator you can enter your SteamID, the GroupID of Steam if the server is only intended for a certain group.
    ServerName - Your server name that you want to find in the overview. WorldName - The name of the world

- Then continue: in the folder Saves you create a new folder with Docker Star System
    IMPORTANT: If you have changed the WorldName in the CFG before, enter the corresponding name.
    
    INFO: The port 27017 was defined by me because I had already occupied the standard port of 27016.
    If you want to change this, you can find the entry in the SpaceEngineers-Dedicated.cfg under Serverport.
    
- Then go into the folder and upload all the files that are stored in my GitHub account under Docker Star System.

After that, you should be able to start the server.
