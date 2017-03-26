#### Cepheus Private Repo Example

This is an example of how to store your Cepheus data in private repo internal or external to your organization. This specific repo is not private simply because it's a public example of how to store private data used in Cepheus.

Cepheus is a full management system for Ceph. It allows you to build new clusters from bare-metal that is fully automated. Cepheus uses Chef for the heavy lifting and Ansible for maintenance tasks and orchestration. We have found that Ansible is super simple for orchestration of large clusters but not as good as Chef for managing large clusters.

The directory structure of this repo mimics Cepheus' structure. The reason is simple, layers. Cepheus uses layers that will overlay the exact data found in the base Cepheus repo as part of the build process.
