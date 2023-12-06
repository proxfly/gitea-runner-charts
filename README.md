# Helm Charts


## Usage

1. Add this helm chart repo to your helm client configuration

    ```
    helm repo add gitea-runner-charts https://proxfly.github.io/gitea-runner-charts
    ```
2. Update repo and search

    ```
    helm repo update
    helm search repo -l gitea-runner-charts
    ```
3. Install the chart

    ```
    helm install act-runner gitea-runner-charts/act-runner --set runner.runnerToken.value=<runner registration tokent>
    ```

4. Uninstall
    ```
    helm uninstall act-runner
    ```
