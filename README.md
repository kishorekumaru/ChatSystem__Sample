ChatSystem__Sample
==================

NodeJS/Mongo DB/ SOCKET IO 


Resource : https://www.youtube.com/watch?v=QISU14OrRbI

Chat system is a simple Socket IO Node JS services build to interact with multiple client instances. I have created the 
file by following the video.

To run the application please follow the below steps

Step 1: Install Node JS

Install Nodejs in your system. I am using windows machine, you can find other Operating system servers 
from http://nodejs.org/download/
(Windows)
   Once you downloaded run the *.msi file to install Node JS
   
   After installation type node in your command promt to check Node JS is installed. If you recieve any expection 
   please uninstall and reinstall again, sometime it may fix those problems.
   
   To Quit Node press Ctrl+C twice

Step 2: Install Mongo DB

Mongo DB is required for this application. Install Mongo DB from http://www.mongodb.org/

(Windows)
    Once you downloaded the zip file create a folder called MongoDB in your C: and move the unzipped contents to MongoDB folder 
    so it should look like C:\MongoDB>  Create a folder called "data" under C: (Mongo DB internally refers the folder 
    to hold Mongo DB data so it should look like C:\data>). Its highly recommeded to create MongoDB and data folder on the 
    root of C:\ avoid pasting these items inside another  folder Ex: C:\Mongo\MongoDB> or C:\Mongo\Data> - not advisable  

  After pasting the files open the command prompt go to bin folder and type mongod to start MongoDB
  Ex: C:/MongoDB/bin>mongod -- This will start your Mongo DB server (minimize once its started)
  
  Open an other command prompt in the same bin folder and type mongo to access Mongo database
  Ex: C:/MongoDB/bin>mongo
  
  
  Step 3: Install Mongo & Socket IO node modules for this application
  
  Create a folder and paste this application. For Ex : C:\YOURNAME\Chats\
  
  Open this location in command prompt and install Mongo & socket io (This part is clearly explained the above video URL)
  
  Run the index.html in two different browser and start chating :)
  
  
  

