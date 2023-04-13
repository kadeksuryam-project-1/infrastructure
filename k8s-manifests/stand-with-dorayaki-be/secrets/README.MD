# How to Generate Secret
Example:
```
kubectl -n swd create secret generic swd-be-env --dry-run=client --from-env-file=.env -o yaml | kubeseal -o yaml > swd-be-env.yaml
```
