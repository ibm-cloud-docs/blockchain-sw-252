---

copyright:
  years: 2019, 2021
lastupdated: "2021-08-11"


keywords: release note, latest changes, Hyperledger Fabric, multicloud

subcollection: blockchain-sw-252

---

{:DomainName: data-hd-keyref="APPDomain"}
{:DomainName: data-hd-keyref="DomainName"}
{:android: data-hd-operatingsystem="android"}
{:api: .ph data-hd-interface='api'}
{:apikey: data-credential-placeholder='apikey'}
{:app_key: data-hd-keyref="app_key"}
{:app_name: data-hd-keyref="app_name"}
{:app_secret: data-hd-keyref="app_secret"}
{:app_url: data-hd-keyref="app_url"}
{:audio: .audio}
{:authenticated-content: .authenticated-content}
{:beta: .beta}
{:c#: .ph data-hd-programlang='c#'}
{:c#: data-hd-programlang="c#"}
{:cli: .ph data-hd-interface='cli'}
{:codeblock: .codeblock}
{:curl: #curl .ph data-hd-programlang='curl'}
{:curl: .ph data-hd-programlang='curl'}
{:deprecated: .deprecated}
{:dotnet-standard: .ph data-hd-programlang='dotnet-standard'}
{:download: .download}
{:external: .external target="_blank"}
{:external: target="_blank" .external}
{:faq: data-hd-content-type='faq'}
{:fuzzybunny: .ph data-hd-programlang='fuzzybunny'}
{:generic: data-hd-operatingsystem="generic"}
{:generic: data-hd-programlang="generic"}
{:gif: data-image-type='gif'}
{:go: .ph data-hd-programlang='go'}
{:help: data-hd-content-type='help'}
{:hide-dashboard: .hide-dashboard}
{:hide-in-docs: .hide-in-docs}
{:important: .important}
{:ios: data-hd-operatingsystem="ios"}
{:java: #java .ph data-hd-programlang='java'}
{:java: .ph data-hd-programlang='java'}
{:java: data-hd-programlang="java"}
{:javascript: .ph data-hd-programlang='javascript'}
{:javascript: data-hd-programlang="javascript"}
{:middle: .ph data-hd-position='middle'}
{:navgroup: .navgroup}
{:new_window: target="_blank"}
{:node: .ph data-hd-programlang='node'}
{:note: .note}
{:objectc: .ph data-hd-programlang='Objective C'}
{:objectc: data-hd-programlang="objectc"}
{:org_name: data-hd-keyref="org_name"}
{:php: .ph data-hd-programlang='PHP'}
{:php: data-hd-programlang="php"}
{:pre: .pre}
{:preview: .preview}
{:python: .ph data-hd-programlang='python'}
{:python: data-hd-programlang="python"}
{:right: .ph data-hd-position='right'}
{:route: data-hd-keyref="route"}
{:row-headers: .row-headers}
{:ruby: .ph data-hd-programlang='ruby'}
{:ruby: data-hd-programlang="ruby"}
{:runtime: architecture="runtime"}
{:runtimeIcon: .runtimeIcon}
{:runtimeIconList: .runtimeIconList}
{:runtimeLink: .runtimeLink}
{:runtimeTitle: .runtimeTitle}
{:screen: .screen}
{:script: data-hd-video='script'}
{:service: architecture="service"}
{:service_instance_name: data-hd-keyref="service_instance_name"}
{:service_name: data-hd-keyref="service_name"}
{:shortdesc: .shortdesc}
{:space_name: data-hd-keyref="space_name"}
{:step: data-tutorial-type='step'}
{:step: data-tutorial-type='step'} 
{:subsection: outputclass="subsection"}
{:support: data-reuse='support'}
{:swift: #swift .ph data-hd-programlang='swift'}
{:swift: .ph data-hd-programlang='swift'}
{:swift: data-hd-programlang="swift"}
{:table: .aria-labeledby="caption"}
{:term: .term}
{:terraform: .ph data-hd-interface='terraform'}
{:tip: .tip}
{:tooling-url: data-tooling-url-placeholder='tooling-url'}
{:topicgroup: .topicgroup}
{:troubleshoot: data-hd-content-type='troubleshoot'}
{:tsCauses: .tsCauses}
{:tsResolve: .tsResolve}
{:tsSymptoms: .tsSymptoms}
{:tutorial: data-hd-content-type='tutorial'}
{:ui: .ph data-hd-interface='ui'}
{:unity: .ph data-hd-programlang='unity'}
{:url: data-credential-placeholder='url'}
{:user_ID: data-hd-keyref="user_ID"}
{:vbnet: .ph data-hd-programlang='vb.net'}
{:video: .video}




# Release notes
{: #release-notes-saas-20}

<div style="background-color: #f4f4f4; padding-left: 20px; border-bottom: 2px solid #0f62fe; padding-top: 12px; padding-bottom: 4px; margin-bottom: 16px;">
  <p style="line-height: 15px;">
    <strong>Running a different version of IBM Blockchain Platform?</strong> Switch to version
    <a href="/docs/blockchain-sw?topic=blockchain-sw-release-notes-saas-20">2.1.2</a>,
    <a href="/docs/blockchain-sw-213?topic=blockchain-sw-213-release-notes-saas-20">2.1.3</a>,
    <a href="/docs/blockchain-sw-25?topic=blockchain-sw-25-release-notes-saas-20">2.5</a>,
    <a href="/docs/blockchain-sw-251?topic=blockchain-sw-251-release-notes-saas-20">2.5.1</a>, 2.52
    </p>
</div>

Use these release notes that are grouped by date to learn about the latest changes to {{site.data.keyword.blockchainfull}} Platform for {{site.data.keyword.cloud_notm}} that built on Hyperledger Fabric v1.4.12 and v2.2.3.
{: shortdesc}


[Installing the 2.5.2 fix pack](/docs/blockchain-sw-252?topic=blockchain-sw-252-install-fixpack)  
For instructions on how to apply the latest fix pack to your blockchain instance.  


[Installing patches](/docs/blockchain?topic=blockchain-ibp-console-manage-console#ibp-console-manage-patch)  
For instructions on how to apply patches to your existing blockchain nodes. Patches are cumulative. This means that if multiple patches, for example `1.4.7-0` and `1.4.12-1`, are available for a node, you should always select the latest patch, `1.4.12-1` in this case, wherever possible because it includes the fixes from the previous patches as well.   

## 10 Aug 2021
{: #10-08-2021}

Miscellaneous bug fixes and security patches.

Export certificates in .pem format for easy management and maintenance in {{site.data.keyword.cloud_notm}} Certificate Manager. See [viewing and updating identities](/docs/blockchain-sw-252?topic=blockchain-sw-252-ibp-console-identities#ibp-console-identities-update-identities) to learn more details.



## 14 Jul 2021
{: #14-07-2021}

**Certificate Authority (CA) patch 1.5.0-1, Peer and ordering node patch 1.4.12-2, 2.2.3-2**

Miscellaneous bug fixes and security patches.



## 16 Jun 2021
{: #16-06-2021}

**Certificate Authority (CA) patch 1.4.9-8, Peer and ordering node patch 1.4.12-1, 2.2.3-1**

Miscellaneous bug fixes and security patches.

The platform has been updated to include support for Hyperledger Fabric v1.4.12 and v2.2.3.


## 05 May 2021
{: #05-05-2021}

**Certificate Authority (CA) patch 1.4.9-7, Peer and ordering node patch 1.4.11-2, 2.2.2-2**

Miscellaneous bug fixes and security patches.





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


