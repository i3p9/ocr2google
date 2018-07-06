# ocr2google
Script to OCR and google the phrase automatically

First of all the script was made for Bash so I probably won't get around to write one for Powershell. 

### Dependencies
- Google Tesseract - *brew install tesseract*
- Python3 - *brew install python*
- [Homebrew](https://docs.brew.sh/Installation) - You probably already have this install but just in case you don't, you need it for *brew*.

### How to run
Clone the repo and open a terminal window in that folder. 
```
$ bash run.sh
```

### Notes

- Default coordinates for screenshots are at top right corner of the screen. You may change it by changing x,y,w,h *(x,y is the top left co-ordniates, and then use w/h for width/height pixels)*
- Default browser is set to Google Chrome. You may change it by replacing chrome with your preferred browser. You can find the browser type name from [here](https://docs.python.org/2/library/webbrowser.html).
