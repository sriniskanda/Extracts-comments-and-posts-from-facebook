# Extracts-comments-and-posts-from-facebook
This python code extracts Facebook comments and posts using graph API and saves it in csv file.
Run this code on command line from commnad line give following input arguments in order
first argument give "User name"  
second argument give "number of days" (How many days you want to extract comments and posts)
third argument give APP_SECRET you will get from facebook developer account
fourth argument give APP_ID which also you will get from facebook developer account
code output will be csv file with parameters in order are POST ID, COMMENT ID, USERNAME, COMMENT (outFile.csv)

To get APP_SECRET snd APP_ID register your app in https://developers.facebook.com/ after registering app APP_SCRET and APP_ID is generated.


How to run this code:

cmd or terminal: 

python facebookScrap.py user_name days APP_SECRET APP_ID

example:

python facebookScrap.py xxx 7 APP_SECRET APP_ID


