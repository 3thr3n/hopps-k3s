# hopps-k3s
[Hopps](https://github.com/hopps-app/hopps)

## Disclaimer
This is a deployment of the current hopps `27.01.2025` chart `0.0.4`.

It is for test purposes only, you can use this as a template BUT **do not use** this in production

## How To
1. clone this repo
2. update all the hosts
3. update the `coredns-custom.yaml` in templates
4. run `helm dependency update`
5. add repositories if needed
6. run `helm install hopps .`
7. add secret `hopps-minio` with key `user` and `pass`
8. after changes run `helm upgrade hopps .`
