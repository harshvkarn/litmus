## Create Kubernetes Cluster for CI in Azure Cloud (AKS)

### Steps:
- To create a cluster:
```bash
ansible-playbook create-k8s-cluster.yml --extra-vars "azure_username=litmus azure_password=P@ssw0rd"
```

- To delete the cluster

```bash
ansible-playbook delete-k8s-cluster.yml --extra-vars "azure_username=litmus azure_password=P@ssw0rd"
```

**NOTE**: Currently the total node count is three and VM Size is set to `Standard`