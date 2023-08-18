# Cableship Charts

## Update a Chart
```sh
podman run --rm --volume "$(pwd)/charts/argocd-source-tracker:/helm-docs" -u $(id -u) docker.io/jnorwood/helm-docs:latest
```
```sh
docker run --rm --volume "$(pwd)/charts/argocd-source-tracker:/helm-docs" -u $(id -u) jnorwood/helm-docs:latest
```