The following table describes of custom prompts for generating and parsing Kubernetes manifests from the list

| NAME           | PROMPT                        | DESCRIPTION                                                            | EXAMPLE                     |
| -------------- | ----------------------------- | ---------------------------------------------------------------------- | --------------------------- |
| Pod            | [[app.prompt]]                | Create basic Pod with container port                                   | [[app.yaml]]                |
| Configmap      | [[app-configmap.prompt]]      | Create Pod with Volume, env, configmap                                 | [[app-configmap.yaml]]      |
| Job            | [[app-job.prompt]]            | Create Job                                                             | [[app-job.yaml]]            |
| CronJob        | [[app-cronjob.prompt]]        | Create Cronjob                                                         | [[app-cronjob.yaml]]        |
| LivenessProbe  | [[app-livenessProbe.prompt]]  | Create pod with livenessprobe                                          | [[app-livenessProbe.yaml]]  |
| ReadnessProbe  | [[app-readnessProbe.prompt]]  | Create pod with livenessprobe and readnessProbe                        | [[app-readinessProbe.yaml]] |
| Multicontainer | [[app-multicontainer.prompt]] | Create pod with volumes                                                | [[app-multicontainer.yaml]] |
| Resources      | [[app-resources.prompt]]      | Create pod with livenessprobe and readnessProbe and limit of resources | [[app-resources.yaml]]      |
| Secret-env     | [[app-secret-env.prompt]]     | Create pod with secrets                                                | [[app-secret-env.yaml]]     |
| VolumeMounts   | [[app-volumeMounts.prompt]]   | Create pod with livenessprobe and readnessProbe and volumeMount        | [[app-volumeMounts.yaml]]   |
