# generic Helm chart

Scaffolded minimal Helm chart for a generic service.

To lint and install:

```bash
helm lint charts/generic
helm install my-generic charts/generic --set image.repository=nginx,image.tag=stable
```
