# BestWay hot tub Cloudflare Worker

## Requirements

- Node.js
- [wrangler](https://developers.cloudflare.com/workers/wrangler/)
- tinygo 0.29.0 or later

## Development

Use something like fnm to install Node.js then run `fnm use` to install and activate the required node version.

```sh
npm install
```

```sh
make dev     # run dev server
make build   # build Go Wasm binary
make deploy # deploy worker
```
