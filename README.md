# k8s-gitops-sandbox

Throwaway manifests for trying out a GitOps tool against a test cluster.
Two generic demo workloads, no real services, no configuration of any real
environment. Safe to delete.

- `apps/web`: an unprivileged nginx behind a Service.
- `apps/worker`: a container that only sleeps.

Neither sets a namespace: the tool that deploys them chooses it.
