# helm-chart

Reference link: https://medium.com/@mattiaperi/create-a-public-helm-chart-repository-with-github-pages-49b180dbb417

Commands:
helm lint helm-chart-sources/*
helm package helm-chart-sources/*
helm repo index --url https://Amit-Prajapati.github.io/helm-chart/ .
cat index.yaml
git add . && git commit -m “Initial commit” && git push origin main
helm list -A
helm repo add myhelmrepo https://amit-prajapati.github.io/helm-chart/
helm repo update
helm search repo test
k create ns myhelmrepo
helm install myhelmrepo/helm-chart-test -n myhelmrepo --generate-name
k get all -n myhelmrepo
