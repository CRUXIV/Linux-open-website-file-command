# Linux-open-website-file-command
This is a fun little file linux file that when you execute the file it opens "youtube.com" ( You can change it)
--INSTRUCTIONS--

Open a Terminal.
--------------
Create a new file for your script. For example, you can name it "open_website.sh":
--------------------
touch open_website.sh
-------------------------------------------
Edit the file using a text editor like nano:
---------------------
nano open_website.sh
-------------------------------------
Add the following content to the file:
-------------------------------------
#!/bin/bash
firefox https://www.example.com
-------------------------------
Replace https://www.example.com with the URL you want to open.
-------------------------------------------------------------------------------------------------------
Save and exit the editor. If you’re using nano, you can do this by pressing CTRL + X, then Y, and Enter.
--------------------------
Make the script executable:
------------------------
chmod +x open_website.sh
-------------------------
Run the script to test it:
---------------------
./open_website.sh
-----------------
When you run open_website.sh, it should open Firefox and navigate to the specified website.
------------------------------------------------------------------------------------------
Hope You liked it!
