# cloudflare worker yew test

## deploy

```
wrangler deploy
```

## preview

https://workers-kv-from-rust.paul-asvb.workers.dev/

## original init
```
wrangler generate workers-kv-from-rust https://github.com/cloudflare/rustwasm-worker-template/
wrangler kv:namespace create yew_worker_test
```
