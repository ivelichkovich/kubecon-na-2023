1. create kind cluster
   1. `kind create cluster --config kind-config.yaml`
   2. `KUBECONTEXT=kind-kind`
2. launch validating webhook globally
   1. show it working
   2. launch a deployment that fails
   3. easy to troubleshoot right
4. show KCM and scheduler restart
5. launch deployment, nothing happens
6. delete deployment nothing happens
7. service undable to clear endpoints or create endpoints


# demo 2
1. fix cluster above with match conditions
2. create VAP, show it working
2. use VAP to force match-conditions on admission webhooks
3. break cluster again with VAP