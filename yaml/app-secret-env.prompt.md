Generate a Kubernetes YAML manifest for a `Pod` using `apiVersion: v1`.

- Set the Pod name to `app-secret-env`.
    
- Add one container named `mycontainer` using the `redis` image.
    
- Define two environment variables, `SECRET_USERNAME` and `SECRET_PASSWORD`, whose values come from a Kubernetes Secret named `mysecret1` with keys `username` and `password` respectively.
    
- Set the Pod’s `restartPolicy` to `Never`.