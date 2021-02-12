---

copyright:
  years: 2017, 2021
lastupdated: "2021-02-12"

keywords: site map
subcollection: blockchain-sw-251

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
{:authenticated-content: .authenticated-content}
{:beta: .beta}
{:c#: data-hd-programlang="c#"}
{:cli: .ph data-hd-interface='cli'}
{:codeblock: .codeblock}
{:curl: .ph data-hd-programlang='curl'}
{:deprecated: .deprecated}
{:dotnet-standard: .ph data-hd-programlang='dotnet-standard'}
{:download: .download}
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
{:java: .ph data-hd-programlang='java'}
{:java: data-hd-programlang="java"}
{:javascript: .ph data-hd-programlang='javascript'}
{:javascript: data-hd-programlang="javascript"}
{:new_window: target="_blank"}
{:note .note}
{:note: .note}
{:objectc data-hd-programlang="objectc"}
{:org_name: data-hd-keyref="org_name"}
{:php: data-hd-programlang="php"}
{:pre: .pre}
{:preview: .preview}
{:python: .ph data-hd-programlang='python'}
{:python: data-hd-programlang="python"}
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
{:subsection: outputclass="subsection"}
{:support: data-reuse='support'}
{:swift: .ph data-hd-programlang='swift'}
{:swift: data-hd-programlang="swift"}
{:table: .aria-labeledby="caption"}
{:term: .term}
{:tip: .tip}
{:tooling-url: data-tooling-url-placeholder='tooling-url'}
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



# Site map
{: #sitemap}




## What is blockchain?

[What is blockchain?](https://www.ibm.com/blockchain/what-is-blockchain){: external}


## High availability
{: #sitemap_high_availability}



## Getting started
{: #sitemap_getting_started}



## Deploy a smart contract
{: #sitemap_deploy_a_smart_contract}



## Certificate Authority (CA) options
{: #sitemap_certificate_authority_(ca)_options}



## Hardware Security Module (HSM)
{: #sitemap_hardware_security_module_(hsm)}



## Ansible Playbooks
{: #sitemap_ansible_playbooks}



## Install on the OpenShift Container Platform
{: #sitemap_install_on_the_openshift_container_platform}



## Deployment options
{: #sitemap_deployment_options}


[Deploy {{site.data.keyword.blockchainfull_notm}} Platform 2.5.1 manually](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp)
* [Get your entitlement key](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#deploy-ocp-entitlement-key)
* [Before you begin](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#deploy-ocp-prerequisites)
* [Log in to your OpenShift cluster](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#deploy-ocp-login)
* [Create the `ibpinfra` project for the webhook](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#deploy-ocp-ibpinfra)
* [Create a secret for your entitlement key](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#deploy-ocp-secret-ibpinfra)
* [Deploy the webhook and custom resource definitions (CRDs) to your OpenShift cluster](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#deploy-ocp-webhook-crd)
  * [1. Configure role-based access control (RBAC) for the webhook](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#webhook-rbac)
  * [2. (OpenShift cluster only) Apply the Security Context Constraint](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#webhook-scc)
  * [3. Deploy the webhook](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#webhook-deploy)
* [Create a new project for your {{site.data.keyword.blockchainfull_notm}} Platform deployment](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#deploy-ocp-project)
* [Create a secret for your entitlement key](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#deploy-ocp-docker-registry-secret)
* [Add security and access policies](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#deploy-ocp-scc)
* [Deploy the {{site.data.keyword.blockchainfull_notm}} Platform operator](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#deploy-ocp-operator)
* [Deploy the {{site.data.keyword.blockchainfull_notm}} Platform console](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#deploy-ocp-console)
  * [Advanced deployment options](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#console-deploy-ocp-advanced)
  * [Use your own TLS Certificates (Optional)](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#console-deploy-ocp-use-your-own-tls-certificates-optional)
* [Log in to the console](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#deploy-ocp-log-in)
* [Next steps](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp#console-deploy-ocp-next-steps)

[Deploy {{site.data.keyword.blockchainfull_notm}} Platform 2.5.1 on-prem manually](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall)
* [Get your entitlement key](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#deploy-ocp-entitlement-key-firewall)
* [Before you begin](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#deploy-ocp-prerequisites-firewall)
* [Pull the {{site.data.keyword.blockchainfull_notm}} Platform images](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#deploy-ocp-images-firewall)
* [Log in to your OpenShift cluster](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#deploy-ocp-login-firewall)
* [Create the `ibpinfra` project for the webhook](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#deploy-ocp-ibpinfra)
* [Set up the entitlement for a local registry](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#deploy-ocp-secret-ibpinfra-fw)
* [Deploy the webhook and custom resource definitions to your OpenShift cluster](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#deploy-k8s-webhook-crd)
  * [1. Configure role-based access control (RBAC) for the webhook](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#webhook-rbac)
  * [2. (OpenShift cluster only) Apply the Security Context Constraint](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#webhook-scc)
  * [3. Deploy the webhook](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#webhook-deploy)
* [Create a new project for your {{site.data.keyword.blockchainfull_notm}} Platform deployment](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#deploy-ocp-project-firewall)
* [Set up the entitlement for a local registry](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#deploy-ocp-docker-registry-secret)
* [Add security and access policies](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#deploy-ocp-scc-firewall)
  * [Apply the Security Context Constraint](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#deploy-ocp-scc-firewall-apply)
  * [Apply the ClusterRole](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#deploy-ocp-clusterrole-firewall)
  * [Apply the ClusterRoleBinding](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#deploy-ocp-clusterrolebinding-firewall)
* [Deploy the {{site.data.keyword.blockchainfull_notm}} Platform operator](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#deploy-ocp-operator-fw)
* [Deploy the {{site.data.keyword.blockchainfull_notm}} Platform console](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#deploy-ocp-console-fw)
  * [Advanced deployment options](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#console-deploy-ocp-advanced-firewall)
* [Log in to the console](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#deploy-ocp-log-in)
* [Next steps](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-ocp-firewall#console-deploy-ocp-next-steps-fw)


## Install on Kubernetes
{: #sitemap_install_on_kubernetes}


[Deploying {{site.data.keyword.blockchainfull_notm}} Platform 2.5.1](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8)
* [Resources required](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-resources-required)
* [Browsers](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-browsers)
* [Storage](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-storage)
* [Filesystem permissions](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-fs-perm)
* [Get your entitlement key](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-entitlement-key)
* [Before you begin](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-prerequisites)
* [Log in to your cluster](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-login)
* [Create the `ibpinfra` namespace for the webhook](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-ibpinfra)
* [Create a secret for your entitlement key](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-secret-ibpinfra)
* [Deploy the webhook and custom resource definitions (CRDS) to your Kubernetes cluster](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8s-webhook-crd)
  * [1. Configure role-based access control (RBAC) for the webhook](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#webhook-rbac)
  * [2. (OpenShift cluster only) Apply the Security Context Constraint](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#webhook-scc)
  * [3. Deploy the webhook](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#webhook-deploy)
* [Create a new namespace for your {{site.data.keyword.blockchainfull_notm}} Platform deployment](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-namespace)
* [Create a secret for your entitlement key](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-docker-registry-secret)
* [Add security and access policies](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-scc)
  * [Apply the Pod Security Policy](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-apply-psp)
  * [Apply the ClusterRole](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-clusterrole)
  * [Apply the ClusterRoleBinding](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-clusterrolebinding)
  * [Create the role binding](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-rolebinding)
* [Deploy the {{site.data.keyword.blockchainfull_notm}} Platform operator](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-operator)
* [Deploy the {{site.data.keyword.blockchainfull_notm}} Platform console](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-console)
  * [Advanced deployment options](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#console-deploy-k8-advanced)
  * [Use your own TLS Certificates (Optional)](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-tls)
  * [Verifying the console installation](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-verify)
* [Log in to the console](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#deploy-k8-log-in)
* [Next steps](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#console-deploy-k8-next-steps)
* [Considerations when using Kubernetes distributions](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8#console-deploy-k8-considerations)

[Deploying {{site.data.keyword.blockchainfull_notm}} Platform 2.5.1 behind a firewall](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall)
* [Resources required](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-resources-required-firewall)
* [Browsers](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-browsers-firewall)
* [Storage](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-storage-firewall)
* [Get your entitlement key](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-entitlement-key-firewall)
* [Before you begin](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-prerequisites-firewall)
* [Pull the {{site.data.keyword.blockchainfull_notm}} Platform images](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-images-firewall)
* [Log in to your Kubernetes cluster](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8s-login-firewall)
* [Create the `ibpinfra` namespace for the webhook](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-ibpinfra-fw)
* [Set up the entitlement for a local registry](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-secret-ibpinfra-fw)
* [Deploy the webhook and custom resource definitions to your OpenShift cluster](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8s-webhook-crd-fw)
  * [1. Configure role-based access control (RBAC) for the webhook](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#webhook-rbac)
  * [2. (OpenShift cluster only) Apply the Security Context Constraint](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#webhook-scc)
  * [3. Deploy the webhook](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#webhook-deploy)
* [Create a new namespace for your {{site.data.keyword.blockchainfull_notm}} Platform deployment](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-namespace-firewall)
* [Set up the entitlement for a local registry](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8s-docker-registry-secret-fw)
* [Add security and access policies](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-scc-firewall)
  * [Apply the Pod Security Policy](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-scc-apply-fw)
  * [Apply the ClusterRole](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-clusterrole-fw)
  * [Apply the ClusterRoleBinding](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-clusterrolebinding-fw)
  * [Create the role binding](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-createrole-fw)
* [Deploy the {{site.data.keyword.blockchainfull_notm}} Platform operator](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-operator-firewall)
* [Deploy the {{site.data.keyword.blockchainfull_notm}} Platform console](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-fw-console)
  * [Advanced deployment options](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#console-deploy-k8-advanced-firewall)
  * [Use your own TLS Certificates (Optional)](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-tls-fw)
  * [Verifying the console installation](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-verify-fw)
* [Log in to the console](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#deploy-k8-log-in-fw)
* [Next steps](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#console-deploy-k8-next-steps-fw)
* [Considerations when using Kubernetes distributions](/docs/blockchain-sw-252?topic=blockchain-sw-251-deploy-k8-firewall#console-deploy-k8-considerations)


## Using the IBM Blockchain Platform console
{: #sitemap_using_the_ibm_blockchain_platform_console}



## Developing smart contracts and applications
{: #sitemap_developing_smart_contracts_and_applications}



## Advanced tutorials
{: #sitemap_advanced_tutorials}



## Using Ansible Playbooks
{: #sitemap_using_ansible_playbooks}
