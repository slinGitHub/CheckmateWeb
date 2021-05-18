### 1. Nightscout can not be accessed 
Check if the app is allowed to read from your Nightscout Website.  
Enter in your browser:  
YOUR_NIGHTSCOUT_ADRESS + /api/v1/entries/sgv.csv?count=10000&find[dateString][$gte]=2015-08-28

If successful, you will be requested to download a sgv.csv file (with your glucose data).  
If not, change your Nightscout settings to be readable.

### 2. Only empty charts are shown after entering the nightscout URL
Check in settings if you entered correctly your nightscout credentials.No spaces, backslash etc. are allowed only ht<span>tps:</span>//YOUR_NIGHSCOUT_WEBPAGE.com

### 3. The app is constantly crashing after entering the URL or a setting value 
The app is not preventing the user from entering wrong values (e.g. E:00 instead of 3:00) as a result the app crashes and can not be reopened without crashing again.
To reset Checkmate, go to settings and clear the Checkmate cache and saved data (or reinstall the whole app).
