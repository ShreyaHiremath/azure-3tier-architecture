# Deployment Steps Summary

## 1. Created Resource Group

* rg-azure-3tier

## 2. Created Virtual Networks

* West Europe VNet
* North Europe VNet
* Configured subnets for Web, App, DB tiers

## 3. Configured Network Security Groups

* Web NSG: Allowed HTTP & SSH
* App NSG: Allowed traffic only from Web subnet
* DB NSG: Allowed only MySQL traffic from App subnet

## 4. Configured VNet Peering

* Enabled bidirectional peering between regions

## 5. Deployed Virtual Machines

* Web VM with Public IP
* App VM private
* DB VM private

## 6. Tested Connectivity

* Verified tier isolation
* Validated NSG rules using port testing

## 7. Implemented Database Service

* Installed MySQL for application connectivity testing
