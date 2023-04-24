# Recommended architecture of HashiCorp Vault cluster
The training was designed by Kamil Ciaś, kamil.cias@goto.systems

> Manage Secrets & Protect Sensitive Data with Vault Secure, store and tightly control access to tokens, passwords, certificates, encryption keys for protecting secrets and other sensitive data using a UI, CLI, or HTTP API.



![Recommended architecture of HashiCorp Vault cluster](https://content.hashicorp.com/api/assets?product=tutorials&version=main&asset=public%2Fimg%2Fvault%2Fvault-integrated-storage-reference-architecture.svg)

> With five nodes in the Vault cluster distributed between three availability zones, this architecture can withstand the loss of two nodes from within the cluster or the loss of an entire availability zone. If deploying to three availability zones is not possible, the same architecture may be used across two or one availability zones, at the expense of significant reliability risk in case of an availability zone outage.

### Documentation
* [Raft reference archiecture](https://developer.hashicorp.com/vault/tutorials/day-one-raft/raft-reference-architecture)
