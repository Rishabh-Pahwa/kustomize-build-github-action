# 🔍 Kustomize PR Checker

A GitHub Action that validates [Kustomize](https://github.com/kubernetes-sigs/kustomize) builds in pull requests by running `kustomize build` on changed YAML files or specific directories. This ensures that Kubernetes manifests are correctly rendered before merging.

---

## ✅ Features

- Detects changed `.yaml` / `.yml` files in pull requests
- Automatically runs `kustomize build` on your configured overlays or base paths
- Fails the pull request if build errors occur
- Customizable version of Kustomize and target paths

---

## 🚀 Usage

Save this as `.github/workflows/kustomize-check.yml` in your repository
