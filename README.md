# Blockchain Based Certificate Transparency for Microservices
## Blockchain Network for POC

Nephos was used to deploy hyperledger fabric to kubernetes cluster. (Nephos : https://github.com/hyperledger-labs/nephos)

A hyperledger fabric network with four peer nodes, one orderer node and ca node is used in this POC.

use this command to run hyperledger fabric network on minikube:

    ./nephos/deploy.py --verbose -f ./bc-network/dev-ctm/nephos_config.yaml fabric