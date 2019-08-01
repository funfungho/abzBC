- The `fabric-ccenv` image which is used to build chaincode, currently includes the github.com/hyperledger/fabric/core/chaincode/shim (“shim”) package.
    - > https://hyperledger-fabric.readthedocs.io/en/release-1.1/releases.html
- `chaintool` is a hyperledger Fabric **chaincode compiler**
    - `chaintool` is a utility to assist in various phases of Hyperledger Fabric chaincode development, such as compilation, test, packaging, and deployment. A chaincode app developer may express the interface to their application in a high-level interface definition language, and `chaintool` will generate (1) chaincode stubs and (2) package the chaincode for convenient deployment.
    - > https://fabric-chaintool.readthedocs.io/en/latest/