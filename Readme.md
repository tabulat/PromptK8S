The following table describes of custom prompts for generating and parsing Kubernetes manifests from the list

| NAME           | PROMPT                              | DESCRIPTION                                                            | EXAMPLE                            |
| -------------- | ----------------------------------- | ---------------------------------------------------------------------- | ---------------------------------- |
| Pod            | [prompt](app.prompt)                | Create basic Pod with container port                                   | [example](app.yaml)                |
| Configmap      | [prompt](app-configmap.prompt)      | Create Pod with Volume, env, configmap                                 | [example](app-configmap.yaml)      |
| Job            | [prompt](app-job.prompt)            | Create Job                                                             | [example](app-job.yaml)            |
| CronJob        | [prompt](app-cronjob.prompt)        | Create Cronjob                                                         | [example](app-cronjob.yaml)        |
| LivenessProbe  | [prompt](app-livenessProbe.prompt)  | Create pod with livenessprobe                                          | [example](app-livenessProbe.yaml)  |
| ReadnessProbe  | [prompt](app-readnessProbe.prompt)  | Create pod with livenessprobe and readnessProbe                        | [example](app-readinessProbe.yaml) |
| Multicontainer | [prompt](app-multicontainer.prompt) | Create pod with volumes                                                | [example](app-multicontainer.yaml) |
| Resources      | [prompt](app-resources.prompt)      | Create pod with livenessprobe and readnessProbe and limit of resources | [example](app-resources.yaml)      |
| Secret-env     | [prompt](app-secret-env.prompt)     | Create pod with secrets                                                | [example](app-secret-env.yaml)     |
| VolumeMounts   | [prompt](app-volumeMounts.prompt)   | Create pod with livenessprobe and readnessProbe and volumeMount        | [example](app-volumeMounts.yaml)   |

