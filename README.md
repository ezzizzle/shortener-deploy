# Shortener Deploy

Deploys [ziz-shortner](https://github.com/ezzizzle/ziz-shortener) onto [MicroK8s](https://microk8s.io).

Deploys the following services:

* Secret configured to be used by [oauth2-proxy](https://oauth2-proxy.github.io/oauth2-proxy/auth-configuration#azure-auth-provider) with the Azure `client-id` and `client-secret`
* [oauth2-proxy](https://github.com/oauth2-proxy/oauth2-proxy) to protect the API
* [ziz-shortner](https://github.com/ezzizzle/ziz-shortener)
* 3 `ingress`es
