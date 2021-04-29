# helm-chart

Reference link: https://medium.com/@mattiaperi/create-a-public-helm-chart-repository-with-github-pages-49b180dbb417

Commands: <br />
helm lint helm-chart-sources/* <br />
helm package helm-chart-sources/* <br />
helm repo index --url https://Amit-Prajapati.github.io/helm-chart/ . <br />
cat index.yaml <br />
git add . && git commit -m “Initial commit” && git push origin main <br />
helm list -A <br />
helm repo add myhelmrepo https://amit-prajapati.github.io/helm-chart/ <br />
helm repo update <br />
helm search repo test <br />
k create ns myhelmrepo <br />
helm install myhelmrepo/helm-chart-test -n myhelmrepo --generate-name <br />
k get all -n myhelmrepo <br />
