# Kustomization for Deploying OpenShift Serverless (Knative)

## Deploying OpenShift Serverless

```
$ oc apply --kustomize serverless-operator/base
```

```
$ oc apply --kustomize knative-serving/overlays/development
```

```
$ oc apply --kustomize knative-eventing/overlays/development
```
