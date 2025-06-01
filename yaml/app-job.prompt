Generate a Kubernetes YAML manifest for a `Job` using `apiVersion: batch/v1`.

- Set the job `name` to `app-job-rsync`.
    
- The job should run a container using the image `google/cloud-sdk:275.0.0-alpine`.
    
- The container should execute the command:  
    `gsutil -m rsync -dr gs://glow-sportradar/ /data/input`  
    using `/bin/sh -c`.
    
- Mount a volume named `data-input` to the path `/data/input`.
    
- This volume should be a GCE persistent disk named `glow-data-disk-200` with `fsType: ext4`.
    
- Set the `restartPolicy` to `Never`.
    
- Set `backoffLimit` to `0`.