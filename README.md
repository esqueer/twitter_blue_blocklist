# twitter_blue_blocklist
List of Twitter Blue Verified accounts that have less than 2000 followers and excludes legacy verified accounts.

Credit to https://github.com/travisbrown/blue for providing the full repository of twitter blue subscribers. 

This list is current as of 1/20/2023. Will update periodically.

There are about 200,000 accounts total which will take quite a while to block. I suggest using blockpartyapp and inputting them 5,000 at a time. 

TROUBLESHOOTING USER_ID in Excel

The CSV file may open in excel with scientific notation on the User_ID column. This is because excel limits number values to less than 15 numbers and will cutoff the remaining numbers in Twitter 19 digit user id numbers. To fix this, open in a text editor and manually copy it over to an excel spreadsheet. Run text to columns and make sure the text option is selected for the data field. Should import the user ids and store them as text rather than number. 
