> Generate a Kubernetes YAML manifest for a `Pod` using `apiVersion: v1`.
> 
> - Set the Pod name to `app-multi-containers`.
>     
> - Define a shared volume named `html` using `emptyDir`.
>     
> - Add two containers:
>     
>     - The first container, named `1st`, uses the `nginx` image and mounts the `html` volume at `/usr/share/nginx/html`.
>         
>     - The second container, named `2nd`, uses the `debian` image and mounts the same volume at `/html`.
>         
>         - It should run a shell loop that appends the current date to `/html/index.html` every second.
>