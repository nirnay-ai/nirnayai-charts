# nirnayai-charts


## Installing Helmfile 

Download latest release tarzip from below location 

    wget https://github.com/helmfile/helmfile/releases/download/v0.147.0/helmfile_0.147.0_linux_amd64.tar.g

Unzip the tar file 

    tar -xvzf helmfile_0.147.0_linux_amd64.tar.gz
    sudo mv helmfile /usr/local/bin
    helmfile version 


## Installing Helmfile for a release example
Go getter URL 

git::https://github.com/cloudposse/helmfiles.git@releases/kiam.yaml?ref=0.40.0


## Install NirnayAI Platform with minio as backend 

helmfile apply -f git::https://github.com/nirnay-ai/nirnayai-charts.git@helmfiles/nirnayai-lakehouse/helmfile.yaml?ref=main&always_pull=true




