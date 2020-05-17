# Containers and Kubernetenetes 101

This is a step-by-step guide to perform CLI tasks along with the presentation to gain better understanding.

## Getting Started

Here you will find a copy of the entire Howto, CLI and code for the workshop.

### Prerequisites

Things that you need to install

Docker,
VirtualBox + Minikube + Kubectl,
eksctl

### Installing

https://docs.docker.com/get-docker/

Based on your OS, pls follow the instructions, there’s always Google and Cloud Seeders team to help you out in case of any issues.

Create a docker hub login account for the docker images.

Install Virtualbox + Minikube + kubectl

VirtualBox is a generic tool for running virtual machines.

https://www.virtualbox.org/wiki/Downloads

Minikube is a Kubernetes utility that runs a Kubernetes cluster on your machine.

https://kubernetes.io/docs/tasks/tools/install-minikube/

Remember to turn virtualization on at BIOS level. Also a note that nested virtualization may not work unless you have higher end virtualization software. With vagrant or virtual box there might be some issues.

Kubectl is the interface that will be needed to create, modify, delete the environment.

https://kubernetes.io/docs/tasks/tools/install-kubectl/ You will find the details here.

eksctl

You can create the cluster with a tool called eksctl — a third-party command-line tool that allows creating an EKS cluster with a single command. You can install eksctl according to the instructions in the official project page.

https://github.com/weaveworks/eksctl

Should you have any questions, pls feel free to use the slack channel or mighty networks.

## Authors
* Madhavi Gauripeddi, Cloud Seeders

## Template
* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
