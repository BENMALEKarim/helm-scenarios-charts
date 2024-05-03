# helm-scenarios-charts

export CHART_VERSION=2.2.0
helm package mock-app/.
tar -tvf mock-app-${CHART_VERSION}.tgz

helm repo index . --url https://benmalekarim.github.io/helm-scenarios-charts/