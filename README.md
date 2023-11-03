1. Install mkcert and run `mkcert -install`
2. Create your wildcard domain:
`mkcert "*.localhost.pomerium.io"`
3. Run docker-compose:
`docker-compose up -d`