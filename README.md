# Helm Charts

This repository contains packaged Helm charts provided by Lian Duan.   
The Chert files is used to Terraform and EKS Training


## Add Repository (stable)
`$ helm repo add lians-demo  https://lianduantrain.github.io/HelmTerraformEKS/stable`   
`$ helm repo update`

## Install Packages (stable)  
`$ helm install my-release lians-demo/demo-nginx [--version=2.0.0]`  

