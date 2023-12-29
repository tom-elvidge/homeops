# Backup and Restore

Secrets have to be created manually, fill in the template `secrets.yaml` and apply. Then run the flux bootstrapping process, entering the PAT when prompted.

```sh
kubectl apply -f docs/secrets.yaml
flux bootstrap github --owner=tom-elvidge --repository=homeops --branch=main --path=./cluster --personal
```
