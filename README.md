## How to push azure ACR:
    az login
    az acr login --name shopifyWebk8Registry
    docker build --tag shopifyWebk8Registry.azurecr.io/node_backend:<version> .
    docker push shopifyWebk8Registry.azurecr.io/node_backend:<version>