# charts
Install via: 
```shell script
KV_API_KEY="key"; helm install --repo https://keyval-dev.github.io/charts keyval keyval --set keyval.apikey=$KV_API_KEY --namespace keyval-system --create-namespace
```