# hexo-server-live

[![NPM version](https://badge.fury.io/js/hexo-server-live.svg)](https://www.npmjs.com/package/hexo-server-live)

Live reload while source file changed for [Hexo].

## Installation

```bash
$ npm i -D hexo-server-live
```

## Usage

```bash
$ hexo server
```

## Options

```yaml
live_reload:
    delay: 150
    info: true
    retry: 3000
```

- **delay**: Reload delay after file updates
- **info**: Whether to print information when file updates
- **retry**: Delay for retrying to connect SSE

## License

MIT

[hexo]: https://hexo.io