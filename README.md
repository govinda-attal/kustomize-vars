# kustomize-vars

This repo is created to serve as an example for kustomize issue: https://github.com/kubernetes-sigs/kustomize/issues/2275

```bash
kustomize build ./overlays/composed-app/

Error: accumulating resources: recursed merging from path '<path>/overlays/app2': var 'COLOR' already encountered
```
