# Gathering Information Using Advance Search & Advance Image Search :-


### Google Advance Search
- Finds sites that link back to targeted organisations site.
- No need to remember dorks
- [Google Advance Search](https://www.google.com/advanced_search)

### Google Advance Image Search
- Can search images using advance options
- [Google Advance Image Search](https://www.google.com/advanced_image_search)

### Reverse Image Search
 - Image as search query
 - all online location of that image
 - helps in tracking down
 - [Google Reverse Image Search](https://www.google.com/imghp?sbi=1)

### Gathering Information Using Video Search Engines
- Helps in gathering information of the target
- Analyzing video content for hidden information (date,time,thumbnail)
- Convert video into text or other format to gain critical info
- [Youtube Data Viewer](https://citizenevidence.amnestyusa.org/)
- [Youtube Metadata](https://mattw.io/youtube-metadata/)
- [EZGif](https://ezgif.com/reverse-video)

### Meta Search Engines 
- Uses other search engines to build meta data of Internet
- Can give more information such as images, videos, blogs, news, articles about target
- Privacy by hiding user's IP Address.
- [StartPage](https://www.startpage.com/)
- [MetaGer](https://metager.org/)

### Gathering Information From FTP Search Engines
- Search for files on FTP server to gain critical info about target org
- [NAPALM FTP Indexer](https://www.searchftps.net/)
- [FileSearching](http://www.filesearching.com/)
- [AnonymousFTPlogin](https://github.com/turbo/openftp4)
- **[Reference](https://www.briskbard.com/blog/?q=node/26)**
	#### Google Dork for FTP Servers :- 
	| Google Dork | Description |
	|--------------|-------------|
	|inurl:github.com intext:.ftpconfig -issues|SFTP/FTP server credentials on Github|
	|type:mil inurl:ftp ext:pdf | ps | Sensetive directories on FTP|
	|intext:pure-ftpd.conf intitle:index of|servers exposing pure-ftpd cofiguration files|
	|intitle:"Index Of" intext:sftp-config.json|Extracts list of FTP/SFTP passwords from sublime text|
	|inurl:"ftp://www." "Index of /"|Various online FTP servers|
	
- <u>**inurl:~/ftp;//193 filetype:(php | txt | html |asp | xml | cnf | sh) ~' /html'** **- List of FTP servers by IP address, mostly Windows NT servers with guest login capabilities**</u>

### Gathering Information From IOT Search Engines
- IOT search engine crawls the internet for publicly accessible IOT devices
- without pass or default pass
- attacker gains manufacturer details, geographical location, IP address, hostname, open ports an services running there
- [Shodan](https://www.shodan.io/)
- [Censys](https://search.censys.io/)