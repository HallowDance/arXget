A simple tool to download papers from arxiv.org. Simply give 
the article(s) identifying number as argument(s).

Example usage:
```
arXget 2006.16285 2006.16275
```

Articles are downloaded in ```$HOME/documents/CURRENTH_MONTH``` where
CURRENT_MONTH is formated as %b%YY.

Additionally, you can set the option `-d` to copy the downloaded file to 
a directory (set in the script with the variable `CUSTOM_DIR`) as well

