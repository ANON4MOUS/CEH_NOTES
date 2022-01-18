<center><h1> Google Dorking</h1></center>

1. site : shows result of the specified site only - 
	i. eg :- `site: hide01.ir`

2. allinurl:  pages containing all the query terms specified in the URL. 

	i. Example:- `allinurl:google careeer`

3. inurl:  pages containing the specified word in the URL.

	i. Example:- `inurl: copy site:www.google.com `

4. allintitle: pages containing all the query terms specified in the title.

	i. Example:- `allintitle: detect malware`

5. intitle: pages containing the specified term in the title.

	i. Example:- `malware detection intitle:help` 

6. inanchor: pages containing the query terms specified in the anchor text on links to the page.

	i. Example:- `Anti-virus inanchor:Norton`

7. allinanchor: pages containing all query terms specified in the anchor text on links to the pages.

	i. Example:- `allinanchor: best cloud service provider`

8. cache: This operator displays Google's cached version of a web page instead of the current version of the web page.

	i. Example:-`cache:www.eff.org` will show Google’s cached version of the Electronic Frontier Foundation home page.

9. link: This operator searches websites or pages that contain links to the specified website or page.

	i. Example:- `link:www.googleguide.com` finds pages that point to Google Guide’s home page.

###### *Note: According to Google’s documentation, “you cannot combine a link: search with a regular keyword search.” When we combine "link:" with another advanced operator, Google may not return all pages that match*

10. related: Similar or related to url specified

	i. Example: `related:www.microsoft.com`

11. info: Finds information for the specified webpage 
	
	i. Example: `info:www.gothotel.com`

12. location: Finds information for a specific location

	i. Example: `location:@22.565656515,88.6546548` or `location:8b bus stand`

13. Filetype or ext: shows result of pages containing the same file type

	i. Example: `site: www.microsoft.com filetype:pdf` or `site: www.microsoft.com ext: docx`