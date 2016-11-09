README.MD

## Tested on OSX only
But its just a css, it should work everywhere.

## "Android" Theme supported only!!!

### 1. Go here on your local system and make a backup: 

```cd ~/Library/Application\ Support/Google/Chrome/Default/Extensions/bikioccmkafdpakkkcpdbppfkghcmihk/[CURRENT SIGNAL VERSION]/stylesheets

mv manifest.css manifest.23
```

* My Signal version is "0.25.4_0" So I go here: 

```~/Library/Application\ Support/Google/Chrome/Default/Extensions/bikioccmkafdpakkkcpdbppfkghcmihk/0.25.4_0/stylesheets/
```

### 2. Get the replacement dark theme file.

```curl -O https://raw.githubusercontent.com/NoDataFound/Signal/master/manifest.css
```
### 3. Restart Signal

To revert to the default theme, just rename your manifest.23 back to manifest.css



