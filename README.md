# gitops pipeline example

this repo contains code to do CD on kubernetes using helm, flux, flagger.
more info:
https://www.weave.works/blog/managing-helm-releases-the-gitops-way
https://www.weave.works/blog/automated-canary-management-to-kubernetes-with-flagger-istio-and-gitops-pipelines

## projects branching model

- dev branch (feature-ready state)
- stg branch (release-candidate state)
- master branch (production-ready state)

## requirements

see: https://github.com/ewol123/kops-aws-terraform/K8S


## how it works

![gitops](https://raw.githubusercontent.com/weaveworks/flagger/master/docs/diagrams/flagger-flux-gitops.png)
