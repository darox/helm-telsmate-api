# A Helm Chart for Teslamate-API

## Instructions

1. Add the Helm repository:
    ```
    helm repo add teslamate-api https://darox.github.io/helm-telsmate-api
    ``` 
2. Install the chart:
    ```
    helm install teslamate-api teslamate-api/teslamate-api -n <namespace> --create-namespace
    ```