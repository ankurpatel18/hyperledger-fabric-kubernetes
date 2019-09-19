Hyperledger Fabric on Kubernetes
===================================


## S2-L1 - BYFN Example
1) cd fabric-samples/first-network
NOTE - If you have a problem with the generation of the certs use the binaries provided in the repo
2) ./byfn.sh generate
3) ./byfn.sh up
4) ./byfn.sh down


## S1-L1 - Introduction
[Link to Hyperledgers Main Site](https://www.hyperledger.org/projects/fabric)
[Link to Hyperledgers Getting Started Page](https://hyperledger-fabric.readthedocs.io/en/release-1.4/getting_started.html)

## S1-L2 - 
[Link to install of Linux Mint on Windows 10](https://www.youtube.com/watch?v=qPdNFuDGnFA)

## S1-L6 -
[Link to github repo](https://github.com/happilymarrieddad/hyperledger-fabric-kubernetes)

This is for Ubuntu-like distro's
1) sudo apt update -y && sudo apt upgrade -y && sudo apt dist-upgrade -y
2) Install virtual box - https://www.virtualbox.org/wiki/Linux_Downloads
3) sudo apt install build-essential zsh curl make emacs htop -y
4) https://github.com/robbyrussell/oh-my-zsh
5) https://golang.org/dl/
    - tar -C /usr/local -xzf go1.13.linux-amd64.tar.gz
6) sudo apt install nodejs
    - curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash - && sudo apt-get install --yes nodejs
7) http://docs.docker.com/install/linux/docker-ce/ubuntu/
    - IF ON MINT!!!! Make sure you use this command instead
        - sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu xenial stable"
8) https://kubernetes.io/docs/tasks/tools/install-kubectl/
    - curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt`/bin/linux/amd64/kubectl
9) https://kubernetes.io/docs/tasks/tools/install-minikube/
    - curl -Lo minikube https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64 \
  && chmod +x minikube
    - sudo install minikube /usr/local/bin
10) curl -sSL http://bit.ly/2ysbOFE | bash -s
    - export PATH=$HOME/bin:$PATH

OPTIONAL
11) https://docs.docker.com/compose/install/

## My Own Notes
[Link to Markup for README's](https://guides.github.com/features/mastering-markdown/)
