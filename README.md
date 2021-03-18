

# Azure K8s

## Azure Container Registry

```sh
$ az logout  # to change Azure account if needed
$ az login
$ az account show  # confirm your account
$ az acr login -n <registry-name>  # login with your registry name
$ docker pull hello-world  # or create a docker image
$ docker tag hello-world <registry-name>.azurecr.io/hello-world:v1
$ docker push <registry-name>.azurecr.io/hello-world:v1
```

