# cleverbit-kubernetes-engineer


In order to run this project:
clone the repository
cd to ./cluster/flux-system
bootstrap flux by running: kubectl kustomize . | kubectl apply -f -

the images required are under the names
    4719/s2s:v1
    4719/authority:v1
