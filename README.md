# Bed and Breakfast

## Useful commands
```bash
$NS = "bed-and-breakfast"
$NAME = "bed-and-breakfast"
helm list -n $NS

helm history $NAME --namespace $NS

helm rollback $NAME 1 --namespace $NS

helm uninstall $NAME --namespace $NS
```