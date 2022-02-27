[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/kjhhnmhm/he0228k.git)

```
addEventListener(
  "fetch", event => {
    let url = new URL(event.request.url);
    url.host = "ipkiurottfn677/he0228-6.herokuapp.com";
    let request = new Request(url, event.request);
    event.respondWith(
      fetch(request)
    )
  }
)
```
