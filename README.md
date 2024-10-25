# cert-manager-abion-kustomize

I have a dislike for Helm charts, so I decoded the Abion cert-manager webhook plugin into a Kustomize solution that is more easilly adjusted and implemented with argocd (in my humble experience)

to upgrade Cert-manager, change the cert-manager release version in the top level Kustomize file 
to upgrade the Abion webhook solver, change the image tag in solvers/abion/deployment.yaml to the latest one.
