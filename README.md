# helm-charts
```
curl https://abeyuki.github.io/helm-chart-circleci/stable/index.yaml
```
```
helm repo add circleci-runner https://abeyuki.github.io/helm-chart-circleci/stable/ \
  --set runnerToken=$CIRCLECI_RUNNER_TOKEN \
  --set resourceClass=$CIRCLECI_RUNNER_RESOURCE_CLASS \
  --namespace $YOUR_NAMESPACE \
  --create-namespace
```

# official
https://circleci.com/docs/ja/runner-on-kubernetes