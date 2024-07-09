### SmAppsec Helm charts



# Add Repo
helm repo add my-charts https://sm-appsec.github.io

# Install repo
helm install <release-name> <repo-name>/smappsec --namespace <namespace>

helm repo list

helm install linsan my-charts/smappsec --namespace <namespace>
