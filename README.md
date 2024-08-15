# HELM CHARTS

```sh
# for each charts
$ helm lint charts/terraform-nomad/
$ helm template charts/terraform-nomad/
$ helm package charts/terraform-nomad/
# then create the index.yaml
$ helm repo index --url https://gperreymond.github.io/helm-charts/ .
```
