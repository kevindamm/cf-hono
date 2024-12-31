# [cf-hono] Hono webapp on Cloudflare Workers

A template repo for Hono-based Cloudflare Worker demonstrating:

 * authentication using D1, bcrypt and tokens stored in KV
 * websockets on DurableObjects, with and without backing storage
 * rate-limiting with a multi-variate function
 * tail-workers for logging metrics (observability)
 * combination of Cloudflare Pages and Cloudflare Workers



```
npm install
npm run dev
```

```
npm run deploy
```
