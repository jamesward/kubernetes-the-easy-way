# Create A Kubernetes Cluster on Google Cloud

Make sure the "container" service is enabled for your account:
```
gcloud services enable container
```
Otherwise you get an error like `Consumer XXXXXXXXX should enable service:container.googleapis.com before generating a service account.`

Create the Kubernetes Cluster:
```
gcloud container clusters create kubernetes-the-easy-way
```

Next: [Smoke Test](13-smoke-test.md)
