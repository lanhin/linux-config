# linux-config
Backup for my OS configures

## Screen
Move the `dot.screenrc` to `~/.screenrc` and modify it according to your environments. It configs `screen`.

## Shadowsocks
`ss_server.json` and `ss_local.json` are json config files for server and client separately.

Modify your password in `ss_server.json` and run:
```bash
python shadowsocks/server.py -c ss_server.json
```

For client, modify local_address and password in `ss_local.json` and run:
```bash
python shadowsocks/local.py -c ss_local.json
```
