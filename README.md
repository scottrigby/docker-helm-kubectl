# docker-helm-kubectl

Alpine [Docker image](https://hub.docker.com/r/r6by/docker-helm-kubectl/) with helm, kubectl, and CLI goodies like jq, and yq.

Note this is nearly the same as [Codefresh Helm Plugin](https://github.com/codefresh-io/cf-plugin-helm), except without the `release_chart` script, and with the additional benefit of getting Helm values in JSON format for custom scripting.

Note that once https://github.com/kubernetes/helm/pull/3226 or https://github.com/kubernetes/helm/pull/2950 land in Helm, this project can be deprecated in favor of `cf-plugin-helm`.
