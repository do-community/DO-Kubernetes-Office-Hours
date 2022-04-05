# Answers 

1. How do you get started with Kubernetes? 

Learn by doing
    - [Learn Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/)
    - [DigitalOcean Getting Started with Kubernetes](https://www.digitalocean.com/landing/doks-resources)
    - [Linux Foundation Kubernetes Exams](https://training.linuxfoundation.org/full-catalog/?_sft_product_type=training&_sft_topic_area=cloud-containers)
1. What's the best way to run Kubernetes on your computer when you have limited cpu and ram?
    - [Minikube vs Kind vs K3s](https://www.youtube.com/watch?v=NP_EcjzoJv8)
    - [How To Use minikube for Local Kubernetes Development and Testing](https://www.digitalocean.com/community/tutorials/how-to-use-minikube-for-local-kubernetes-development-and-testing)
    - [Getting Started with K3s](https://rancher.com/docs/k3s/latest/en/quick-start/)
1. How do you set up TLS certs on multiple hosts?
    - Decide on your ingress controller 
        - NGINX
            - [Configuring Nginx Ingress Rules for Backend Services](https://github.com/digitalocean/Kubernetes-Starter-Kit-Developers/blob/main/03-setup-ingress-controller/nginx.md#step-4---configuring-nginx-ingress-rules-for-backend-services)
            - [Setting up Ingress to use Wildcard Certificates](https://github.com/digitalocean/Kubernetes-Starter-Kit-Developers/blob/main/03-setup-ingress-controller/guides/wildcard_certificates.md)         
        - Ambassador Edge Stack  
            - [Defining the Hosts for Ambassador Edge Stack](https://github.com/digitalocean/Kubernetes-Starter-Kit-Developers/blob/main/03-setup-ingress-controller/ambassador.md#step-3---defining-the-hosts-for-ambassador-edge-stack)
1. Kubernetes vs. App Platform -- when to use and when to switch?
    - [Is Kubernetes Right for Me?](https://www.digitalocean.com/blog/is-kubernetes-right-for-me)
1. What is the best approach to understand Helm charts? 
    - [Artifact Hub](https://artifacthub.io/)
    - [Helm Hello World](https://github.com/helm/examples/tree/main/charts/hello-world)
    - [Helm Quickstart](https://helm.sh/docs/intro/quickstart/)
    - [An Introduction to Helm, the Package Manager for Kubernetes](https://www.digitalocean.com/community/tutorials/an-introduction-to-helm-the-package-manager-for-kubernetes)
    - [Kubernetes Package Management with Helm](https://www.linkedin.com/learning/kubernetes-package-management-with-helm)
