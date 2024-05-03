# helm-scenarios-charts

export CHART_VERSION=1.9.0
helm package mock-app/.
tar -tvf mock-app-${CHART_VERSION}.tgz

helm repo index . --url https://benmalekarim.github.io/helm-scenarios-charts/