# rBG-Wonderland
A friendly, CAPTCHA-less portal to RarBG (media piracy site) powered using their torrentAPI

Access the web app at: [RarBG Portal](https://gabba.ga/rbg.html)

## Features
- Cool looking GUI
- Table sorting: by seeds, leachers, name and file size. One can also group by file type
- Free of nasty CAPTCHAs (meaning I have to trust on random internet peeps not to abuse my website)
- Suggestions bar (Movies only)
- Direct magnet links

![alt text](https://user-images.githubusercontent.com/12468102/105800947-eda95300-5fd2-11eb-9c75-f16770bdaa65.png "Screenshot_0")

##How to use
- Select one or more categories
- Type in the search query
  *if there is a suggestion avaiable click it to refine your query
- Press enter/click the submit button
- A table with a bunch of links should be generated:
  * If you know what you're doing select your prefereed file to open the magnet link
  * If not, the general rule of thumb is to select the file with the most seeds so click on the 'S.' to sort by seads and select the file with the greatest seeds
- Clicking on a link should open the magent link - prompting you to open a [torrent client](https://www.qbittorrent.org/)

## Limitations:
- Api limits maximum search results to 100 so if your query has >100 results, keep in mind that there are probably more results that aren't displayed. When results exceed 100 the result count above the results table is red and you should either try narrowing your query or use rarBG. 
- You can't run the html file directly due to the COR's restriction. You can either bypass it using [Cors Unblock](https://chrome.google.com/webstore/detail/cors-unblock/lfhmikememgdcahcdlaciloancbhjino?hl=en) or just use my website
- Unlike RarBG, the query submitted on their api needs to be word-by-word accurate else it fails, I've mitigated this by implementing suggestions as you type (powered by IMDB) 

## Issues
Search may not yield results on the first query

## Acknowledgments
Thanks to RarBG for creating TorrentAPI and documenting it!
<hr>

Finally, feel free to contribute however you like, I know my code is **far** from perfect!
