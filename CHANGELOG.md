# CHANGELOG

## 2.0.0
- completely renewed dependencies and removed unnecessary overhead
- implemented new configuration properties to allow different socks proxies at the same time
- added white-/blacklisting based on target hostnames

## 1.1.1
- src: Use parsed url hostname instead of host which may contain also port

## 1.1.0
- src: Support setting local address of the http-service.
- src: Format timestamp of logs.

## 1.0.4
- src: Support setting the `--level` option in `createServer()`.

## 1.0.3
- src: Bind `error` event on sockets to prevent servers from exiting in some node runtimes.

## 1.0.2

- Exports "main" fields in `package.json`.
