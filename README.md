# hlf2-template
A Hyperledger Fabric network template 

More info about how to create it at:
* [Medium](https://medium.com/@ialberquilla/creating-a-hyperledger-fabric-2-network-template-in-four-simples-steps-cf804d5075e2) 

# Installation instructions

1. Download the template:
`git clone https://github.com/ialberquilla/hlf1.4-couchdb`

2. Download bin and config files
`curl -sSL https://bit.ly/2ysbOFE | bash -s -- -d -s`


# Start the network
1. Generate the crypto material
`./network.sh up createChannel`


# Stop the network
`./network.sh down`

