# Linux GSM Rust Server

## start server
- `docker-compose up`

## wipe
```bash
docker-compose exec linuxgsm ./rustserver full-wipe
```

## install oxide
```bash
docker-compose exec linuxgsm ./rustserver mods-install
rustoxide
```

## append plugin
```bash
docker-compose exec linuxgsm bash
cd serverfile/oxide/plugins
```

## connect to rcon
- login [rcon:io](https://rcon.io)

