Generate a Kubernetes YAML manifest for a `Pod` using `apiVersion: v1`.

- Set the Pod name to `app-volume`.
- Add one container named `app` using the image `gcr.io/kuar-demo/kuard-amd64:1`.
- Configure a `livenessProbe` with an HTTP GET on path `/healthy` at port `8080`, with:
    - `initialDelaySeconds: 5`, `timeoutSeconds: 1`, `periodSeconds: 10`, `failureThreshold: 3`.
- Configure a `readinessProbe` with an HTTP GET on path `/ready` at port `8080`, with:
    - `initialDelaySeconds: 0`, `periodSeconds: 2`, `failureThreshold: 3`, `successThreshold: 1`.
- Expose container port `8080` named `http`.
- Mount a volume named `data` at `/data`.
- Define a volume `data` of type `hostPath` that maps to `/var/lib/app` on the host.