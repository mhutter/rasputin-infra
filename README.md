# rasputin-infra

## monitoring

Prep:

    kubectl -n mh-monitoring create secret generic hc-token --from-literal token=<from healthchecks.io>
