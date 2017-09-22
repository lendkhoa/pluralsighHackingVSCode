# Hacking VS Code
> Sep 21, 2017

- Built upon Electron

## snippet
- A json object:
    - prefix
    - body
    - description

```
"print to console": {
    "prefix": "log",
    "body": [
        "console.log('$1');",
        "$2"
    ],
    "description":"Log output to console"
}

```

- $ is defined as tab stop
    - able to 