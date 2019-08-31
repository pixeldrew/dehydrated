# dehydrated
Docker setup for dehydrated with cloudflare dns validation hooks

## configuration
Copy .env.default to .env
```sh
$ cp .env.default .env
```
Update .env with your details

```sh
docker build -t dehydrated . && docker run -it --env-file=./.env
```
