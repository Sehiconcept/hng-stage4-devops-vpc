# HNG DevOps Stage 4: Virtual Private Cloud (VPC) on Linux

This project implements a cloud-like VPC using only Linux networking tools.

## Features
- Network namespaces as subnets
- Linux bridge as VPC router
- NAT for public internet access
- VPC isolation
- CLI: `vpcctl`

## Usage
sudo ./vpcctl create --name prod --internet-interface eth0
sudo ./vpcctl delete --name prod
