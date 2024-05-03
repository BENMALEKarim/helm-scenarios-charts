# helm-scenarios-charts

export CHART_VERSION=2.1.0
helm package .
tar -tvf mock-app-${CHART_VERSION}.tgz