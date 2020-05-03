# Whois Data Downloader
Auto downloader of whoisdatabase by cron file. 

#Newly Registered Domains Downloader

#Features
Download a ewly Registered Domains list from WhoisDataCenter.com
Retrieve WHOIS Information
Retrieve Reverse WHOIS (by Name) Information

#Example
sh whoisdatacenter.sh
or 
cron
0 2 * * * wget --user=USER --password='PASSWD' https://global.whoisdatacenter.com/$yesterday.zip >/dev/null 2>&1

