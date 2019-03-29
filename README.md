# k8s-manifests

This repository contains manifest files used for bringing up the containers in
Kubic, where the most of them are the part of Kubernetes infrastructure not
deployed by kubeadm - like CNI plugins, ingress controllers, monitoring
platforms etc.

Each of the manifest can be applied by `kubectl apply -f manifest-name.yaml`
and uses container images from
[openSUSE Container Registry](https://registry.opensuse.org/).
