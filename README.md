# telegram-member-scraper
Export all users from member groups using Telethon. 

This is a Python script based off a tutorial for scraping Telegram users from groups. 
The original code allowed the user to export an individual group's members into one CSV file. 
I have now adapted the code so that each group's members can be outputed into individual CSV files which are
appropriately named as the corresponding groups. 

The original tutorial can be found here: https://python.gotrained.com/scraping-telegram-group-members-python-telethon/ 

## Requirements:

You're going to need to install Telethon package for Python, and configure it to suit the Telegram API. 
Navigate over to https://my.telegram.org and using the API development tools configure your credentials. 
For this you are going to ned an `api_id` and `api_hash` and your phone number. 
Paste these values in the appropriate fields in `member_go.py`.

To install Telethon you can do:
`python pip install telethon `


## Execution:

Once you have fulfilled the requirements go ahead an launch the script from your command prompt or terminal.
Please note that your output folder will be the same directory as where you have your script saved. 

## Feedback:
This is my first submission to Github, and I am quite fresh to python so please feel free to send me any constructive feedback:
mailto:ivan.s@eastmillcapital.com 
