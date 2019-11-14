# Papertrail Retrieve
A Python Notebook to download Papertrail Logs with ease.

## Requirements
- A Papertrail account and its API Token.

## Usage
Set the date and the hours range (in 24h format) of the logs you want to download.

```
#Dates to retrieve logs in format YYYY-MM-DD
date="2019-11-10"

#Range of hours in 24h format
hour_start="14"
hour_end="15"
```

Set your Papertrail API Token

```
papertrail_api_token="abcdefghijklmnop"
```

Then run the Notebook. All the files will be stored in your local path + "/logs". If the folder doesn't exist, it will create one. After downloading the files, the notebook will uncompress them in the same folder. 
