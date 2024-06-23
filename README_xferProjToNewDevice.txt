1) Compress all files in the parent Project folder (zip and send, in this case it's the U22_URP_demo folder) to send to a new device/person to edit. 
This is also the project head and GitHub repository name.

2) You don't necessarily need all the folders though. Important ones are Assets, Packages, and ProjectSettings.

3) The Library holds all the imported assets. Any asset used in the project must be converted to the native Unity format, so this is the folder that Unity self-imports
all of the project assets to be used. Unity can generate this itself at any time, so the folder isn't necessary to xfer projects, but it may take
a long time for Unity to do this depending on the size of the project.