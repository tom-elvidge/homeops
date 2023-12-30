# Charts

```sh
helm install my-release ./kevin-base --values ./kevin-base/example.yaml --dry-run
helm install my-release ./kevin-base --values ./kevin-base/example.yaml
helm upgrade my-release ./kevin-base --values ./kevin-base/example.yaml
helm status my-release
helm uninstall my-release
```