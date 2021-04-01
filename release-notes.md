---

copyright:
  years: 2019, 2021
lastupdated: "2021-04-01"


keywords: release note, latest changes, Hyperledger Fabric, multicloud

subcollection: blockchain-sw-252

---

{:note: .note}
{:important: .important}
{:tip: .tip}
{:shortdesc: .shortdesc}
{:pre: .pre}
{:external: target="_blank" .external}


# Release notes
{: #release-notes-saas-20}

<div style="background-color: #f4f4f4; padding-left: 20px; border-bottom: 2px solid #0f62fe; padding-top: 12px; padding-bottom: 4px; margin-bottom: 16px;">
  <p style="line-height: 10px;">
    <strong>Running a different version of IBM Blockchain Platform?</strong> Switch to version
    <a href="/docs/blockchain-sw?topic=blockchain-sw-release-notes-saas-20">2.1.2</a>,
    <a href="/docs/blockchain-sw-213?topic=blockchain-sw-213-release-notes-saas-20">2.1.3</a>,
    <a href="/docs/blockchain-sw-25?topic=blockchain-sw-25-release-notes-saas-20">2.5</a>,
    <a href="/docs/blockchain-sw-251?topic=blockchain-sw-251-release-notes-saas-20">2.5.1</a>
    </p>
</div>

Use these release notes that are grouped by date to learn about the latest changes to {{site.data.keyword.blockchainfull}} Platform for {{site.data.keyword.cloud_notm}} which is built on Hyperledger Fabric v1.4.11 and v2.2.2.
{:shortdesc}




[Installing patches](/docs/blockchain?topic=blockchain-ibp-console-manage-console#ibp-console-manage-patch)  
For instructions on how to apply patches to your existing blockchain nodes. Patches are cumulative. This means that if multiple patches, for example `1.4.7-0` and `1.4.7-1`, are available for a node, you should always select the latest patch, `1.4.7-1` in this case, wherever possible because it includes the fixes from the previous patches as well.   




## 29 Mar 2021
{: #29-03-2021}

**Certificate Authority (CA) patch 1.4.9-6, Peer and ordering node patch 1.4.11-1, 2.2.2-1** 



## 22 Feb 2021
{: #02-22-2021}

**Certificate Authority (CA) patch 1.4.9-5, Peer and ordering node patch 1.4.9-5 and 2.2.1-5**

## 12 Jan 2021
{: #01-12-2021}

**Certificate Authority (CA) patch 1.4.9-4, Peer and ordering node patch 1.4.9-4, 2.2.1-4**

Miscellaneous bug fixes and security patches.

### New logging configuration panel
{: #01-12-2021-logger-ui}

A new panel is available to override peer and ordering node log levels for specific component loggers. See [Configuring node logging](/docs/blockchain-sw-252?topic=blockchain-sw-252-console-icp-manage#ibp-console-manage-logger) for more information.

## 08 Dec 2020
{: #12-08-2020}

**Certificate Authority (CA) patch 1.4.9-3, Peer and ordering node patch 1.4.9-3, 2.2.1-3**

Miscellaneous bug fixes and security patches.  


## 19 Nov 2020
{: #11-19-2020}

**Certificate Authority (CA) patch 1.4.9-2, Peer and ordering node patch 1.4.9-2, 2.2.1-2**

Miscellaneous bug fixes and security patches.  




## 30 Oct 2020
{: #10-20-2020}


**Certificate Authority (CA) patch 1.4.9-1, Peer and ordering node patch 1.4.9-1, 2.2.1-1**

Miscellaneous bug fixes and security patches.  

If you are running **OpenShift Container Platform 3.11** in {{site.data.keyword.cloud_notm}}, it is recommended that you [upgrade your cluster to 4.4](https://docs.openshift.com/container-platform/4.4/migration/migrating_3_4/planning-migration-3-to-4.html){: external} now in order to fully take advantage of the new features. After you upgrade your cluster, follow instructions to [refresh your blockchain console](/docs/blockchain?topic=blockchain-ibp-console-manage-console#ibp-console-refresh) to experience the latest functionality in this release.
{: important}

### Fabric v2.x node upgrade
{: #11-02-2020-upgrade}

In addition to deploying new nodes based on the latest Fabric v2.2.1 image, you can upgrade your existing nodes to Fabric v2.x and the capabilities of your channels, allowing organizations to take advantage of the new smart contract lifecycle process.

For information about upgrading nodes, check out [Upgrading to a new version of Fabric](/docs/blockchain-sw-252?topic=blockchain-sw-252-ibp-console-govern-components#ibp-console-govern-components-upgrade). For information about updating the capabilities of your channels, check out [Capabilities](/docs/blockchain-sw-252?topic=blockchain-sw-252-ibp-console-govern#ibp-console-govern-capabilities).

### Support for Fabric v2.x smart contract lifecycle
{: #11-02-2020-lc}

The platform has been updated to include support for Fabric v2.x smart contract lifecycle process, which enables the distributed governance of smart contracts. Learn mode about how to [Deploy a smart contract using Fabric v2.x](/docs/blockchain-sw-252?topic=blockchain-sw-252-ibp-console-smart-contracts-v2).

### Improvements for HSM support
{: #11-02-2020-hsm}

A new [process](/docs/blockchain-sw-252?topic=blockchain-sw-252-ibp-console-adv-deployment#ibp-console-adv-deployment-hsm-build-docker) is available to configure an HSM for your blockchain nodes, delivering faster performance.

### Certificate renewal enhancements
{: #11-02-2020-cert-renew}

Customers can now use the console to renew certificates that have expired or are about to expire, including the Certificate Authority (CA) TLS certificate, peer and ordering node enrollment certificates, and peer and ordering node TLS certificates.

### Remove registered user from CA
{: #11-02-2020-delete-user}

You can now delete registered users from a CA.


