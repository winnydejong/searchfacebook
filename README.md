# searchfacebook

Python 2.7 script to collect search results from query Facebook Graph API. By default the script 

### How to use this script
1. Copy-paste your access token into facebook_credentials.py. You can get your Facebook Graph API access token here: https://developers.facebook.com/. 
2. List all of your queries, 1 on each line, in a textfile named 'query.txt'. Save this file in the same directory as all the .py scripts. By default the script will iterate over all lines in query.txt. 
3. The script will assume that you're looking for pages. If you want to search for groups or personal accounts, change this in the main.py script on line XXX XXX and XXX. (Search for # Change Step 3 in main.py.)
4. Open the directory with Python scripts in the terminal. To run the script type "python main.py" in the terminal. 

### Good to know:
- Depending on the size of query.txt. the API call may take a while, due to sleep time added to the script. 
- For every search query, based on query.txt from step 2,  save the page name, page id and page category. While doing so the script will print "INFO - Processing Data for Page Name" in the terminal. 
- You'll know the script is finished, when it prints "INFO - The Script Execution started at date time" 
