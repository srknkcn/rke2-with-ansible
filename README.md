# rke2-with-ansible

Setup RKE2 cluster within minutes with only one command. rancher &amp; kube-vip setup included with "3 master" and "0 to N worker" nodes

This project supports the following guest operating systems:

## Linux Distributions


| Operating System         | Version   |
| :------------------------- | :---------- |
| Ubuntu Server            | 22.04 LTS |
| Red Hat Enterprise Linux | 8         |
| Red Hat Enterprise Linux | 9         |

## Create RKE2 Kubernetes cluster

For Development Environments

`ansible-playbook main.yml -i inventory/k8s-dev`

For Production Environments

`ansible-playbook main.yml -i inventory/k8s-prod`
