## How to push azure ACR:
    az login
    az acr login --name jsprod
    docker build --tag jsprod.azurecr.io/backend:<version> .
    docker push jsprod.azurecr.io/backend:<version>