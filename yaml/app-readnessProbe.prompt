Generate a Kubernetes YAML manifest for a `Pod` using `apiVersion: v1`.

- Set the Pod name to `app-readinessprob`.
- Add one container named `app` using the image `gcr.io/k8s-k3s/demo:v2.0.0`.
- Configure a `livenessProbe` with HTTP GET on path `/` at port `8000`, with:
    - `initialDelaySeconds: 5`, `timeoutSeconds: 1`, `periodSeconds: 10`, `failureThreshold: 3`.
- Configure a `readinessProbe` with HTTP GET on path `/ready` at port `8000`, with:
    - `initialDelaySeconds: 0`, `periodSeconds: 2`, `failureThreshold: 3`, `successThreshold: 1`.
- Expose container port `8000` named `http`.