---

copyright:
  years: 2017, 2021
lastupdated: "2021-02-12"

keywords: IBM Blockchain Platform, release, new features, multicloud

subcollection: blockchain-sw-251

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:pre: .pre}
{:note: .note}
{:important: .important}
{:tip: .tip}
{:external: target="_blank" .external}


# What's new
{: #whats-new}

<blockchain-sw-251><div style="background-color: #f4f4f4; padding-left: 20px; border-bottom: 2px solid #0f62fe; padding-top: 12px; padding-bottom: 4px; margin-bottom: 16px;">
  <p style="line-height: 10px;">
    <strong>Running a different version of IBM Blockchain Platform?</strong> Switch to version
    <a href="/docs/blockchain-sw?topic=blockchain-sw-whats-new">2.1.2</a>,
    <a href="/docs/blockchain-sw-213?topic=blockchain-sw-213-whats-new">2.1.3</a>,
    <a href="/docs/blockchain-sw-25?topic=blockchain-sw-25-whats-new">2.5</a>
    </p>
</div></blockchain-sw-251>

## January 19, 2021
{: #whats-new-01-19-2021}

The {{site.data.keyword.blockchainfull}} Platform extension for VS Code V2.0 is now available for download from the Visual Studio Marketplace. This new version includes support for Fabric v2.0 lifecycle along with updated tutorials. [Download the extension](https://marketplace.visualstudio.com/items?itemName=IBMBlockchain.ibm-blockchain-platform) from the marketplace to get started then visit our [Developer Tooling](/docs/blockchain-sw-252?topic=blockchain-sw-252-develop-vscode#develop-vscode-install) topic for more information.

<blockchain-sw-251>## October 30, 2020</blockchain-sw-251>
{: #whats-new-11-02-2020}

<blockchain-sw-251>
{{site.data.keyword.blockchainfull_notm}} Platform 2.5.1 is now available.</blockchain-sw-251>

{{site.data.keyword.blockchainfull_notm}} Platform <blockchain-sw-251>2.5.1</blockchain-sw-251> now supports the Fabric v2.x smart contract lifecycle that allows for decentralized governance of smart contract definitions on a channel. The platform has been updated to support Kubernetes v1.17-v1.19 and OpenShift container Platform <blockchain-sw-251>4.5, 4.6.</blockchain-sw-251>

**Support for Fabric v2.x lifecycle**

The series of processes around installing, managing, and using smart contracts, collectively known as the "lifecycle" of the smart contract, has been updated. This new lifecycle allows organizations to collaborate in the channel-level decision making process regarding smart contracts, eliminate the need for smart contract fingerprint matches, and allow smart contracts to be written with only the code relevant to an organization's business role.

The {{site.data.keyword.IBM_notm}} Developer tooling has been updated to support generation of Fabric v2.x smart contract packages as well as testing smart contracts by using the new lifecycle process. Learn more about how to [deploy a smart contract using Fabric v2.x](/docs/blockchain-sw-252?topic=blockchain-sw-252-ibp-console-smart-contracts-v2) and [how to write powerful smart contracts](/docs/blockchain-sw-252?topic=blockchain-sw-252-write-powerful-smart-contracts) that leverage the new governance.

**New process for enabling Hardware Security Module (HSM) support**

A new process for configuring an HSM to work with your blockchain nodes is available and offers faster performance over the use of the existing HSM PKCS #11 proxy which is now deprecated. Current customers who are using the PKCS #11 proxy should check out the new process in the [Advanced deployment](/docs/blockchain-sw-252?topic=blockchain-sw-252-ibp-console-adv-deployment#ibp-console-adv-deployment-hsm-build-docker) options.

**Ability to upgrade existing nodes and channel application capability to Fabric v2.x**

You continue to have the option to select the Fabric v1.4 or v2.x image when creating your CAs, peers, and ordering nodes. However, you now have the ability to upgrade your existing nodes that are running Fabric v1.4.x to the Fabric v2.x image. If you have peers using the Fabric v1.4.x image, you must upgrade your nodes and update your channel capabilities to take advantage of the new smart contract lifecycle.

For information about upgrading nodes, check out [Upgrading to a new version of Fabric](/docs/blockchain-sw-252?topic=blockchain-sw-252-ibp-console-govern-components#ibp-console-govern-components-upgrade). For information about updating the capabilities of your channels, check out [Capabilities](/docs/blockchain-sw-252?topic=blockchain-sw-252-ibp-console-govern#ibp-console-govern-capabilities).

**Enhancements to the certificate renewal process**

Because all actions on a blockchain network depend on the existence of valid and verifiable certificates, renewing certificate is vital to avoiding network outages. To streamline the certificate renewal process, the console now allows you to renew your CA TLS certificate, and peer and ordering node enrollment and TLS certificates. While it is preferable to renew certificates before they expire, it is possible to restore components whose certificates have already expired in many cases. Learn more about the new options in [Certificate management](/docs/blockchain-sw-252?topic=blockchain-sw-252-cert-mgmt#cert-mgmt-cert-types).

<blockchain-sw-251>
If you have an existing {{site.data.keyword.blockchainfull_notm}} Platform v2.1.x or 2.5.0 deployment and are interested in upgrading to {{site.data.keyword.blockchainfull_notm}} Platform 2.5.1, see the following topics:
- [Upgrading your console and components on the OpenShift Container Platform](/docs/blockchain-sw-251?topic=blockchain-sw-251-upgrade-ocp)
- [Upgrading your console and components on Kubernetes](/docs/blockchain-sw-251?topic=blockchain-sw-251-upgrade-k8)
- [Upgrading the {{site.data.keyword.blockchainfull_notm}} images](/docs/blockchain-sw-251?topic=blockchain-sw-251-blockchain-images#blockchain-images-upgrade)
</blockchain-sw-251>


<blockchain-sw-251>See the [Release notes](/docs/blockchain-sw-251?topic=blockchain-sw-251-release-notes-saas-20#10-20-2020) for more details on the new features that are included in this release.</blockchain-sw-251>


