# README

This is a simple repo, that reads from a file.

The built docker image is used in order to test a full Tekton CI/CD workflow, see [k8s_tekton_example](https://github.com/PaulHuettl/k8s_tekton_example).

In particular we clone a repo, build a docker container and deploy a pod in a kubernetes cluster
running the docker container as a k8s job.