# Random-Lists

```python
______                _                       _     _     _       
| ___ \              | |                     | |   (_)   | |      
| |_/ /__ _ _ __   __| | ___  _ __ ___ ______| |    _ ___| |_ ___ 
|    // _` | '_ \ / _` |/ _ \| '_ ` _ \______| |   | / __| __/ __|
| |\ \ (_| | | | | (_| | (_) | | | | | |     | |___| \__ \ |_\__ \
\_| \_\__,_|_| |_|\__,_|\___/|_| |_| |_|     \_____/_|___/\__|___/
[$] By 0xRar
```

## What Can i use the lists in this repo for:
The wordlists in this repo are really good for Penetration Testers & Bug Hunters especially 
for burpsuite intruder.

## Example Use Cases:
- ### XSS
HTTP Request:
```
GET /search?q=§§ HTTP/1.1
Host: some-vulnerable.host
[...]
```

- ### IDOR
HTTP Request:
```
POST /messages/§§/invite HTTP/1.1
Host: some-vulnerable.host
[...]
```
