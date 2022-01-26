# LiveDatabase-processing-MONGODB
Uploading live data in MongoDB Atlas (python)

**Project Code Description**<br > <br > 

1. *Make Folders with code named **Processing,queue and Processed** <br > 
2. *A file(txt) **every second** in the Processing folder*<br >
3.  Picks up all the files from processing and moves all the files to queue every **5 seconds**<br >
4.  It then picks files from the queue folder and updates a column in **MongoDB** table as 0/1 and moves the file to the Processed folder<br >
5.  Also no files are moved from Processing to queue until the queue folder is empty.
