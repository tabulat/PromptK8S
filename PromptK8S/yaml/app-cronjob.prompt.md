Generate a Kubernetes YAML manifest for a `CronJob` using `apiVersion: batch/v1beta1`.

- Set the name to `app-cronjob`.
    
- Schedule the job to run every 5 minutes (`"*/5 * * * *"`).
    
- The job should run a container named `hello` using the `bash` image.
    
- The container should execute the command `echo "Hello world"`.
    
- Set `restartPolicy` to `OnFailure`.