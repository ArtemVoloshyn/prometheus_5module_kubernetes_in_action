
---

## Templates of ai created manifests

| NAME               | PROMPT                                              | DESCRIPTION                                                 | EXAMPLE                                              |
|-------------------------|-----------------------------------------------------|-------------------------------------------------------------|------------------------------------------------------|
| app.yaml                | create app yaml manifest for Pod              | Defines a basic Pod resource                               | [app.yaml](https://raw.githubusercontent.com/ArtemVoloshyn/prometheus_5module_kubernetes_in_action/main/yaml/app.yaml)                |
| app-livenessProbe.yaml  | create yaml liveness probe manifest for Pod                          | Configures a liveness probe for the Pod                    | [app-livenessProbe.yaml](https://raw.githubusercontent.com/ArtemVoloshyn/prometheus_5module_kubernetes_in_action/main/yaml/app-livenessProbe.yaml)  |
| app-readinessProbe.yaml | create yaml readiness probe manifest for Pod                          | Configures a readiness probe for the Pod                   | [app-readinessProbe.yaml](https://raw.githubusercontent.com/ArtemVoloshyn/prometheus_5module_kubernetes_in_action/main/yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml   | create yaml volume mounts manifest for Pod                            | Defines volume mounts for the Pod                          | [app-volumeMounts.yaml](https://raw.githubusercontent.com/ArtemVoloshyn/prometheus_5module_kubernetes_in_action/main/yaml/app-volumeMounts.yaml)   |
| app-cronjob.yaml        | create yaml cronjob resource manifest for Pod                  | Schedules jobs on a cron-like schedule                      | [app-cronjob.yaml](https://raw.githubusercontent.com/ArtemVoloshyn/prometheus_5module_kubernetes_in_action/main/yaml/app-cronjob.yamll)        |
| app-job.yaml     | create app job manifest for Pod            | Creates app job manifest for Pod    | [app-job.yaml](https://raw.githubusercontent.com/ArtemVoloshyn/prometheus_5module_kubernetes_in_action/main/yaml/app-job.yaml)    |
| app-multicontainer.yaml | create yaml multiple containers manifest for Pod                         | Defines a Pod with multiple containers                      | [app-multicontainer.yaml](https://raw.githubusercontent.com/ArtemVoloshyn/prometheus_5module_kubernetes_in_action/main/yaml/app-multicontainer.yaml) |
| app-resources.yaml      | create yaml resource limits and requests manifest for Pod             | Configures resource limits and requests for the Pod        | [app-resources.yaml](https://raw.githubusercontent.com/ArtemVoloshyn/prometheus_5module_kubernetes_in_action/main/yaml/app-resources.yaml)      |
| app-secret-env.yaml     | create yaml manifest for Pod that use a secret to set environment variables            | Retrieves values from a Secret as environment variables    | [app-secret-env.yaml](https://raw.githubusercontent.com/ArtemVoloshyn/prometheus_5module_kubernetes_in_action/main/yaml/app-secret-env.yaml)    |

---

