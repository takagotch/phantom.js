### phantom.js
---
https://github.com/ariya/phantomjs

https://github.com/takagotch/phantomjs

```py
// test/lib/www/echo.py
def handle_request(req):
  url = urlparse.urlparse(req.path)
  headers = {}
  for name, value in req.headers.items():
    headers[name] = value.rstrip()
  
  d = dict(
    command = req.command,
    version = req.protocol_version,
    origin = req.client_address,
    url = req.path,
    
  )

```

```
```

```
```

