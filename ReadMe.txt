Youtube Scrapper - App script for google sheet

Creator: Ionut Franciuc - ionufi@gmail.com
https://www.youtube.com/channel/UCoD4ZHOt-yNb1dqrGzDxMYg

Install steps

1. Log in to your google account.
2. Copy the .ods / .xls file to google sheets or google drive.
3. Open the file with Google Sheets.
4. In the tabs menu go to "Extensions" and click on "App Script".
5. Go back to drive/folder and open "youtube scrapper script.txt" and copy all text from here.
6. Go back to the browser in the App Script tab and delete all the text with "function myFunction... etc". We need to remain with a white page here to insert our script.
7. Paste the text you copied from the "youtube scrapper script.txt" file. If you want you can rename the script name on the top.
8. Click save or "ctrl + s"
9. In the left tab, go to "Services" and click on "+"
10. Scroll down and select "YouTube Data API v3". Make sure to have as identifier "YouTube" and click "Add".
11. If all worked well, you should see under "Services" the new activated service called "YouTube".
12. Run the script from the button "Run". You will be asked for permisions on Youtube API.
13. Click on "review permisions" and log in / select your account.
14. As we didn't create an app for this script will be prompted with "Google hasn’t verified this app". You can create an app if you want or just give access to the script.
15. Click on "Advanced" and click on "Go to Untitled project (unsafe)". Also you can rename the script if you want and you didn't rename it already.
16. You will be prompted with "Untitled project / your renamed script name" wants to access your Google Account. Now we need to give access to the script to use youtube API and also to edit google sheet (where we put the data scrapped from Youtube API).
17. Click Allow.

Done!
You can run the script, you should get some results with preset keyword search.


Using the scrapper

!!! You should edit only the green cells. Never change the values for the orange cells. You can break the script by editing orange cells. !!!

Go to Youtube Scrapper sheet.
You shuld have some results printed already from the previous API call.
If you want to make a new search for another keyword you should delete the list with the existing results. Otherways the new results will overwrite the old ones and will be a little hard to read.
Insert your keyword in the coresponding green cell.
You can set the date before/after published. Optional.
"Scan next" green cell is recomanded to be always "yes". This gives you the option to run the script again and get next page with results from the API.
"Title filter" green cell is a filter in the script which return results only with exact match in video titles. Can be deactivated with other word e.g. "no".

For more details, read the documentation from the sheet. In the bottom you have the tab with that.








