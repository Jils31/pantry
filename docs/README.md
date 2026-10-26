# Screenshots

Local and CI

| File | What it shows |
|---|---|
| `pytest.png` | the test suite passing |
| `compose-up-and-smoke.png` | `docker compose up -d --build`, items added, one consumed, filters, stats, metrics |
| `app-compose.png` | the UI served by the compose stack |
| `ci-run.png` | a GitHub Actions run on a push: tests, frontend build, both images with Trivy, kind deploy and smoke test |

AWS, Terraform and EKS

| File | What it shows |
|---|---|
| `terraform-plan.png` | `terraform plan` for the VPC and EKS cluster |
| `terraform-apply.png` | the applies that created the VPC, cluster, node group and add-ons |
| `eks-aws-cli.png` | the cluster, node group, add-ons, VPC, subnets, NAT gateway and spot instances as reported by the AWS CLI |
| `eks-cluster-setup.png` | nodes ready, ingress-nginx and metrics-server installed |
| `eks-helm-deploy.png` | `helm upgrade --install` into the `pantry` namespace, pods, services, ingress, HPA, bound PVC, `helm list`, requests through the load balancer |
| `eks-app-via-ingress.png` | the UI through the Ingress on the AWS load balancer |
| `eks-api-docs.png` | the API docs through the Ingress |
| `eks-load-and-hpa.png` | load against the Ingress, HPA readings, `kubectl top` |
| `eks-prometheus-queries.png` | Prometheus targets, PromQL answers, alert rules, Grafana provisioning |
| `eks-prometheus-targets.png` | the Prometheus targets page with every backend Pod up |
| `eks-hpa-events.png` | the HPA scaling the backend from two to five Pods under load, with its events |
| `argocd-application.png` | the Argo CD Application, Synced and Healthy, and its spec |
| `argocd-gitops-change.png` | a values change pushed to `main`, Argo CD on the new revision, the frontend Deployment following |
| `eks-grafana-dashboard.png` | the provisioned Grafana dashboard with live panels |
| `terraform-destroy.png` | `terraform destroy` removing everything |
