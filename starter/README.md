# CD12352 - Infrastructure as Code Project Solution
# Tuan Dang Ho Anh

## Spin up instructions
### Spin up network stack
./run.sh deploy cd12352-udagram-network network.yml network-parameters.json
### Spin up server stack
./run.sh deploy cd12352-udagram-server udagram.yml udagram-parameters.json

## Tear down instructions
### Tear down network stack
./run.sh delete cd12352-udagram-network
### Tear down server stack
./run.sh delete cd12352-udagram-server

## Other considerations
[Diagram](Diagram.png)