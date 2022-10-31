# nirnayai-charts


## Installing Helmfile 

Download latest release tarzip from below location 

    wget https://github.com/helmfile/helmfile/releases/download/v0.147.0/helmfile_0.147.0_linux_amd64.tar.gz

Unzip the tar file 

    tar -xvzf helmfile_0.147.0_linux_amd64.tar.gz
    sudo mv helmfile /usr/local/bin
    helmfile version 


## Installing Lakehouse Platform

Install the application's latest release 

    helmfile apply -f git::https://github.com/nirnay-ai/nirnayai-charts.git@helmfiles/nirnayai-lakehouse/helmfile.yaml?ref=main&always_pull=true




## Docs
Go getter URL 

    git::https://github.com/cloudposse/helmfiles.git@releases/kiam.yaml?ref=0.40.0
    helmfile apply -f git::https://github.com/nirnay-ai/nirnayai-charts.git@helmfiles/nirnayai-lakehouse/helmfile.yaml?ref=main&always_pull=true




