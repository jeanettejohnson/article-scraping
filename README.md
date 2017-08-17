# article-scraping
for summer 2017 news article scraping

## File list
* ```in_progress.py```
  * could be named better :P
  * program that does the scraping
  * outputs ```articles.json```
  * uses Python 3
* ```graph2.py```
  * input is ```articles.json```
  * outputs ```output.json```
  * since cpl-prov uses Python 2, uses python 2 as well
* ```upload.py```
  * uploads ```output.json``` to <http://camflow.org/demo>
  * outputs ```sshot.png```, the resulting graph
  * uses Python 3

## How to run
* ```python3 in_progress.py [url of article]```
* ```python graph2.py```
* ```python3 upload.py```

## Current issues
* working on comparing sentiment of paragraph to quote
  * not sure it will actually be accurate
* LATimes finding authors is a special case
* linked vs unliked quotes
* labeled corpus

good articles:
https://www.nytimes.com/2017/07/19/us/politics/john-mccain-brain-cancer.html
http://www.washingtonexaminer.com/senate-judiciary-committee-approves-fbi-nominee-christopher-wray/article/2629199

bad articles:


retracted articles:
* https://web.archive.org/web/20170622210615/http://www.cnn.com/2017/06/22/politics/russian-investment-fund-under-investigation/index.html
