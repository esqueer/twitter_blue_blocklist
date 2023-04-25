# twitter_blue_blocklist
List of Twitter Blue Verified accounts that are active and excludes legacy verified accounts. It's sorted by biggest follower numbers to smallest. 

There are 3 csv files in this repository:

1. The original file I create with a filter of <2000 followers.
2. The full active blue subscriber list excluding legacy verified sorted largest follower counts to smallest
3. The full active blue subscriber list split into columns <5000 for easier input into blockpartyapp.

Credit to https://github.com/travisbrown/blue for providing the full repository of twitter blue subscribers. 

This list is current as of 4/20/2023. Will update periodically.

There are about 521,106 accounts total which will take quite a while to block. I suggest using blockpartyapp and inputting them 5,000 at a time. It takes only usernames and not user ID's so I removed the User Id in the recent update. Let me know if you want me to add it back. 


This only applies to the original <2000 follower file from January:
TROUBLESHOOTING USER_ID in Excel

The original CSV file may open in excel with scientific notation on the User_ID column. This is because excel limits number values to less than 15 numbers and will cutoff the remaining numbers in Twitter 19 digit user id numbers. To fix this, open in a text editor and manually copy it over to an excel spreadsheet. Run text to columns and make sure the text option is selected for the data field. Should import the user ids and store them as text rather than number. 
