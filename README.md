# gcp-proxy-func
Very simple Google Cloud Function that proxies requests using Express and `http-proxy-middleware`. You define the address that requests should be proxied to by filling out config.js (copy `config.example.js` to `config.js`, and then change the URL).

# Using
Fill in `config.js`, and then either zip up the files and upload via Gcloud admin, or use [the Gcloud CLI](https://cloud.google.com/sdk/gcloud/) and `npm run deploy`.
