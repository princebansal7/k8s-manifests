# Kubernetes demo applications

###### Apologies for low audio in demo videos (watch in 1.5x)
- Node DB app on k8s demo | [YT](https://youtu.be/Q7aZ8Jrl4E4?si=S0_ODgsWFMWjb7ZV)
- Ingress service k8s demo | [YT](https://youtu.be/vIvbZynxYDA)
- Mimic Ingress service demo | [YT](https://youtu.be/UhT6qguVWz8)
- CICD with GitOPS and ArgoCD demo | [YT](https://youtu.be/1rP_r2Nizdc) | [Repo](https://github.com/princebansal7/gitops-argocd-k8s?tab=readme-ov-file#readme) | [cicd-file](https://github.com/princebansal7/npx-cicd-project/blob/main/.github/workflows/ci-cd.yaml)

- Node app deployment on GKE (Google Kubernetes Engine) (Old) | [Link](https://github.com/princebansal7/backend-docker-k8s?tab=readme-ov-file#readme)

- Useful commands to Build multi platform docker images (on Apple silicon)
  
  - Building image for both platforms
    ```bash
    docker buildx build --platform linux/arm64,linux/amd64 -t <docker-hub-username>/<repo-name>:<tag> --load .
    ```
  - Building image for Linux platform (on Apple silicon)
    ```bash
    docker build --platform=linux/amd64 -t <docker-hub-username>/<repo-name>:<tag> .
    ```
