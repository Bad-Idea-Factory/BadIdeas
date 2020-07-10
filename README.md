Multi-User Playground for Unreal Engine 4 
Created by Bad Idea Factory & The Kickons Crew

This project uses a google stream drive for content, a multi user server hosted on a linux VPS and a ZeroTier VPN to enable real-time collaborative editing through the Unreal Engine Multi-User mode. 

Install Unreal Engine 4.25.1 

Use github desktop to pull this project to a folder in your Unreal Projects folder.

Download & Install the G-Drive stream client from https://dl.google.com/drive-file-stream/GoogleDriveFSSetup.exe

(You will be given the credentials when you're invited to a colaborative editing session)

Edit the drivelink.bat file in the Badideas project directory, change the paths to suit the location of your project directory and drive stream letter

Run the drivelink.bat to create the linked Content directory in Unreal Engine

Browse to the Google stream drive and install the programs from the installers folder

Connect to the ZeroTier VPN credentials provided 
(you will need to be authorised by the admin after you try to connect)

Once you're connected, determine your IP address on the VPN

Open the project with Unreal Engine and wait AGES for it to find all the assets and compile everything locally

Edit the project settings in Unreal Engine and specify your VPN IP address under UDP Messages

Open the multi-user editing window and connect to a session!

Note: this is not for public consumption, this project is hosted on github for UE4 editing jams hoted by Bad Idea Factory and The Kickons Crew. 
