Generate a Kubernetes YAML manifest for a `Pod` using `apiVersion: v1`.

- Set the Pod name to `app-livenessprob` and place it in the `demo` namespace.
    
- The Pod should have one container named `app` using the image `gcr.io/k8s-k3s/demo:v1.0.0`.
    
- Configure a `livenessProbe` that performs an HTTP GET on path `/` at port `8000`.
    
    - Set `initialDelaySeconds` to 5, `timeoutSeconds` to 1, `periodSeconds` to 10, and `failureThreshold` to 3.
        
- Expose container port `8080` with the name `http`.