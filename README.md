# nodeFeatureRules

Extra rules for Node Feature Discovery (NFD.

After installing NFD on your cluster, apply these manifests to add extra node labels.

## network-speed.yaml

Label your nodes based on the speeds of their active network interfaces.

```yaml
feature.node.kubernetes.io/network-2.5G: true
```
