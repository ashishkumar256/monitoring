helm -n monitoring upgrade --install grafana-operator oci://ghcr.io/grafana-operator/helm-charts/grafana-operator --version v5.0.0
#helm -n monitoring upgrade --install grafana-operator oci://ghcr.io/grafana-operator/helm-charts/grafana-operator --version v5.0.0-rc0
helm -n monitoring upgrade --install grafana .
