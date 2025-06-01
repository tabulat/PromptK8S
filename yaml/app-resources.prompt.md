Generate a Kubernetes YAML manifest for a `Pod` using `apiVersion: v1`.

- Set the Pod name to `app-resource`.
    
- Add a container named `app` using the image `gcr.io/kuar-demo/kuard-amd64:1`.
    
- Expose container port `8080` with the name `http`.
    
- Configure a `livenessProbe` using HTTP GET on path `/healthy` at port `8080` with:
    
    - `initialDelaySeconds: 5`, `timeoutSeconds: 1`, `periodSeconds: 10`, `failureThreshold: 3`.
        
- Configure a `readinessProbe` using HTTP GET on path `/ready` at port `8080` with:
    
    - `initialDelaySeconds: 0`, `periodSeconds: 2`, `failureThreshold: 3`, `successThreshold: 1`.
        
- Set resource `requests` to `cpu: 100m`, `memory: 128Mi`, and `limits` to `cpu: 100m`, `memory: 256Mi`.