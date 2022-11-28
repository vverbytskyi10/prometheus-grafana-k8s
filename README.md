# prometheus-grafana-k8s

## Execution
# Open root project's dir in terminal
# Run `minikube start --profile <profile_name>`
# Run `minikube mount --profile <profile_name> grafana:/grafana`
# Run `minikube mount --profile <profile_name> prometheus:/prometheus`
# Open k8s dir
# Run `kubectl apply -f .`
# Run `minikube tunnel --profile <profile_name>`
