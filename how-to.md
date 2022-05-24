---

copyright:
  years: 2022
lastupdated: "2022-22-04"

keywords: tutorials, how-to, learn

subcollection: blockchain-sw-251

---

{:external: target="_blank" .external}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:note: .note}
{:important: .important}
{:tip: .tip}
{:term: .term}
{:pre: .pre}


# How to
{: #ibp-how-to}

Use the IBM Blockchain Platform how-tos to complete common tasks for building and using an IBM Blockchain network. 
{: shortdesc}

**Target audience:** This topic is designed for architects, system administrators, and developers who are responsible 
for planning, configuring, and developing applications for {{site.data.keyword.blockchainfull_notm}} 2.5.1.


## Install on OpenShift Container Platform 
{: #install-ocp}

Review the [deployment options](howto-deployment-options.md) and detailed steps for 
deploying {{site.data.keyword.blockchainfull_notm}} 2.5.1 on OpenShift Container Platform. 

For existing installations on OpenShift, details on [upgrading your console and components](howto/console-upgrade-ocp.md) 
and [removing your deployment](howto/console-delete-ocp.md) are provided.


## Install on Kubernetes
{: #install-k8s}

Review the procedures for [deploying IBM Blockchain Platform 2.5.1](howto/console-deploy-k8.md) and 
[deploying IBM Blockchain Platform 2.5.1 behind a firewall](howto/console-deploy-k8-firewall.md) on Kubernetes.

For existing installations on Kubernetes, details on [upgrading your console and components](howto/console-upgrade-k8.md) and 
[removing your deployment](howto/console-delete-k8.md) are provided.


## Installing the 2.5.1 fix pack
{: #install-251-fixpack}

Review the procedures for [installing the 2.5.1 fix pack](howto/console-deploy-k8.md) on an OpenShift or  
Kubernetes {{site.data.keyword.blockchainfull_notm}} installation.


## Using the IBM Blockchain images
{: #using-ibp-images}

Learn about [using the IBM Blockchain images](internal/blockchain_images.md), which are commercial Hyperledger Fabric images 
signed and supported by IBM, for peer, Certificate Authority (CA), ordering service, and smart contract (chaincode) containers. 


## Using the IBM Blockchain Platform console
{: #using-ibp-console}

Learn about [using the IBM Blockchain Platform console](howto-using-ibp-console.md) to manage a {{site.data.keyword.blockchainfull_notm}} 2.5.1 network:

* [Administering your console](howto/console-ocp-manage.md)
* [Advanced deployment options](howto/ibp-console-advanced-deployment.md)
* [Advanced channel deployment and management](howto/ibp-console-advanced-channel.md)
* [Adding and removing ordering service nodes](howto/ibp-console-add-remove-raft.md)
* [Importing nodes, MSPs, and identities](howto/ibp-console-import-nodes.md)
* [Creating and managing identities](howto/ibp-console-identities.md)
* [Managing organizations](howto/ibp-console-organizations.md)
* [Managing certificates](howto/ibp-console-certificates.md)
* [Upgrading and deleting deployed nodes](howto/ibp-console-govern-components.md)
* [Operating nodes with operations service](/blockchain/blockchain-operations_service)


## Developing smart contracts and applications
{: #develop-contracts-applications}

Review procedures for [developing smart contracts and applications](howto-develop-contracts-applications.md) on 
{{site.data.keyword.blockchainfull_notm}} 2.5.1, including [developing smart contracts with IBM Blockchain Developer Tools](vscode-extension.md), 
[writing powerful smart contracts](write-powerful-smart-contracts.md), and [best practices for application development](best_practices.md). 


## Backing up and restoring components and networks
{: #backup-restore-components-networks}

Learn how to manage [backing up and restoring components and networks](howto/backup-restore.md) on 
{{site.data.keyword.blockchainfull_notm}} 2.5.1.


## Using the IBM Blockchain Platform APIs
{: #using-ibp-apis}

Learn about [using the IBM Blockchain Platform APIs](howto/ibp-v2-apis.md) to develop applications 
on {{site.data.keyword.blockchainfull_notm}} 2.5.1.
