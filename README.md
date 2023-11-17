Install [it](https://addons.mozilla.org/en-US/firefox/addon/chatgptff/)

Try https://chat.openai.com/?q=test

## Install serach plugin
```
# run python server to serve chatgpt.html, for some reason it's not working if you open it like file:///
python -m http.server 8080

firefox localhost:8080/chatgpt.html
```

Follow open serach installation instructions https://support.mozilla.org/en-US/kb/add-or-remove-search-engine-firefox

## Distribution
```bash
zip chatgpt.zip chatgptff.js manifest.json
```
