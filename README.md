1. Install mkcert https://github.com/FiloSottile/mkcert
- Mac: `brew install mkcert`
2. Run `mkcert -install`
3. Create your wildcard domain:
`mkcert "*.localhost.pomerium.io"`
4. Change provider config in file `config.yaml`: https://www.pomerium.com/docs/identity-providers/google
5. Run docker-compose: `docker-compose up -d`