# helm-scenarios-charts

export CHART_VERSION=2.0.0
helm package mock-app/.
tar -tvf mock-app-canary-${CHART_VERSION}.tgz

helm repo index . --url https://benmalekarim.github.io/helm-scenarios-charts/