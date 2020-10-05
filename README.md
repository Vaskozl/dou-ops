# dou-ops
Devops for a k3s Raspberry Pi cluster.

Big thanks to onedr0p: https://github.com/onedr0p/k3s-gitops-arm

dou-ops ▶ gotk bootstrap github --components=source-controller,kustomize-controller,helm-controller,notification-controller --arch=arm64 --version=latest --watch-all-namespaces --owner='vaskozl' --repository='dou-ops' --branch='master' --personal --verbose
