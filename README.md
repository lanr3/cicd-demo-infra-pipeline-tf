# cicd-demo-infra-pipeline-tf

### Tools to connect with eks cluster
```
aws-cli
kubectl
```

### How to connect to eks cluster
```
aws eks --region <your-region> update-kubeconfig --name <cluster-name>
```

### Troubleshooting
```sh
rm ~/.kube/config

```