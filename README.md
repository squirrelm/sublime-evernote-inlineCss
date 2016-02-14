# sublime-evernote-inlineCss
Customer inline css for [sublime-evernote](https://github.com/bordaigorl/sublime-evernote)

```
     "inline_css": {
        "body": "",
        "pre": "color: #000000; font-family: monospace,monospace; font-size: 0.9em; white-space: pre-wrap; word-wrap: break-word; border: 1px solid #cccccc; border-radius: 3px; overflow: auto; padding: 6px 10px; margin-bottom: 10px;",
        "code": "color: black; font-family: monospace,monospace; font-size: 0.9em;",
        "inline-code": "color: #000000; font-family: monospace,monospace; padding: 0.1em 0.2em; margin: 0.1em; font-size: 85%; background-color: #F5F5F5; border-radius: 3px; border: 1px solid #cccccc;",
        "h1": "margin-bottom: 0.7em; padding-bottom: 0.3em; margin-top: 1.2em; border-bottom: 1px solid #ccc;",
        "footnotes": "border-top: 1px solid #9AB39B; font-size: 80%;",
        "hr": "color:#9AB39B; padding: 0; margin: 16px 0; background-color:#9AB39B; height:4px; border:0 none; margin-top: 3em; margin-bottom: 3em;",
        "sup": "color:#6D6D6D;font-size:1ex",
        "blockquote": "border-radius: 3px; border-left: .7ex solid #BFBFBF; padding-top: 0.5em; padding-bottom: 0.5em; margin-left: 0px; padding-left: 1em; margin-top: 1.4285em; margin-bottom: 1.4285em; background-color:rgba(102,128,153,.05);",
        // ONLY USED IF wiki_tables or gfm_tables are enabled
        "table": "border-collapse: collapse; border-spacing: 0; margin: 1em;",
        "td": "border: 1px solid #DDD; padding: 6px 13px;",
        "th": "border: 1px solid #DDD; padding: 6px 13px;",
        "tr:odd": "border: 1px solid #DDD; padding: 6px 13px;",
        "tr:even": "border: 1px solid #DDD; padding: 6px 13px; background-color: #F8F8F8;"
    },
```

# Usage

In `Sublime Text 3`, go to `Preferences` > `Package Settings` > `Evernote` > `Settings - User`, replace `inline_css` segment with the above  style codes.
