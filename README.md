Code developed by Yitong Huang, Caleb Mayer, and Olivia Walch. 

# License
This software is open source and under an MIT license.

Roque's updates
after Zoom meeting with Kevin on 8/23:

1. Unable to upload files via "copy path" into browser. 
  You can run your file in http-server.
    1. Have Node.js installed in your system.
    2. In CMD, run the command npm install http-server -g
    3. Navigate to the specific path of your file folder in CMD and run the command http-server
    4. Go to your browser and type localhost:8080. Your Application should run there.

2. Project requirement complete: Wired routes for Hannay's single population model.  
  Modificaitons to code:
    1. Functions end in "_Hannay"
    2. This version's code has "Upload CSV files - Hannay" upload button
        1. If you upload CSV in this version, in models.js, getCircadianOutput_Hannay, lines 356-359 are active and 360 is commented out. Output DLMO changes with each upload. However, if you comment 356-359 and activate 360, the DLMO output will hold at 21.00.
    3. Will need to modify variables so that DLMO output accurately reflects mathematics in Hannay's single population model.

3. Working on bonus portions. 
