# caddy-tailscale-reverse

## [Tailscale](https://tailscale.com/)

[Enabling HTTPS](https://tailscale.com/kb/1153/enabling-https)

```sh
sudo tailscale cert machine-name.domain-alias.ts.net
```

## [Caddy](https://caddyserver.com/)

[Use Caddy to manage Tailscale HTTPS certificates](https://tailscale.com/blog/caddy)

Use `Caddyfile_temp` to create `Caddyfile`:

- Replace `machine-name.domain-alias.ts.net` with your Tailscale
- Replace `42069` with your port
