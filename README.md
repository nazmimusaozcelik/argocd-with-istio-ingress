It contains ARGOCD installation and istio(GW and VS) yaml files in HA structure.



Default admin user password:

kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d
