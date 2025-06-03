The following table describes of custom prompts for generating and parsing Kubernetes manifests from the list

| NAME           | PROMPT                              | DESCRIPTION                                                            | EXAMPLE                            |
| -------------- | ----------------------------------- | ---------------------------------------------------------------------- | ---------------------------------- |
| Pod            | [prompt](yaml/app.prompt)                | Create basic Pod with container port                                   | [example](yaml/app.yaml)                |
| Configmap      | [prompt](yaml/app-configmap.prompt)      | Create Pod with Volume, env, configmap                                 | [example](yaml/app-configmap.yaml)      |
| Job            | [prompt](yaml/app-job.prompt)            | Create Job                                                             | [example](yaml/app-job.yaml)            |
| CronJob        | [prompt](yaml/app-cronjob.prompt)        | Create Cronjob                                                         | [example](yaml/app-cronjob.yaml)        |
| LivenessProbe  | [prompt](yaml/app-livenessProbe.prompt)  | Create pod with livenessprobe                                          | [example](yaml/app-livenessProbe.yaml)  |
| ReadnessProbe  | [prompt](yaml/app-readnessProbe.prompt)  | Create pod with livenessprobe and readnessProbe                        | [example](yaml/app-readinessProbe.yaml) |
| Multicontainer | [prompt](yaml/app-multicontainer.prompt) | Create pod with volumes                                                | [example](yaml/app-multicontainer.yaml) |
| Resources      | [prompt](yaml/app-resources.prompt)      | Create pod with livenessprobe and readnessProbe and limit of resources | [example](yaml/app-resources.yaml)      |
| Secret-env     | [prompt](yaml/app-secret-env.prompt)     | Create pod with secrets                                                | [example](yaml/app-secret-env.yaml)     |
| VolumeMounts   | [prompt](yaml/app-volumeMounts.prompt)   | Create pod with livenessprobe and readnessProbe and volumeMount        | [example](yaml/app-volumeMounts.yaml)   |

