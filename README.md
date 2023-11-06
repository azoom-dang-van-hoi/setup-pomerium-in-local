1. Install mkcert https://github.com/FiloSottile/mkcert
- Mac: `brew install mkcert`
2. Run `mkcert -install`
3. Create your wildcard domain:
`mkcert "*.localhost.pomerium.io"`
4. Run docker-compose:
`docker-compose up -d`