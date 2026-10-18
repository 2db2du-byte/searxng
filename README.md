# SearXNG, on demand 🔎

A private search engine ([SearXNG](https://github.com/searxng/searxng)) for one laptop, bound to `127.0.0.1:8888`, with JSON
output turned on so local AIs (Open WebUI, scripts) can search through it.

```
./searxng start | stop | status | open
```

`compose.yml` runs the container; `searxng` is the start/stop helper (`open` uses Omarchy's web-app launcher).

## License

MIT. Built by Rabbid Raccoon with Claude. Use it, change it, share it.
