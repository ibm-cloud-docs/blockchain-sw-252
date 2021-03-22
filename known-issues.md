---

copyright:
  years: 2019, 2021
lastupdated: "2021-03-22"

keywords: catalina, chrome, external CA, TLS, orderer, error, multicloud

subcollection: blockchain-sw-252

---

{:external: target="_blank" .external}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:note: .note}
{:important: .important}
{:tip: .tip}
{:pre: .pre}


# Known issues
{: #sw-known-issues}

This page describes known issues that you might encounter when you use {{site.data.keyword.blockchainfull_notm}} Platform 2.5.2.
{:shortdesc}

<div style="background-color: #f4f4f4; padding-left: 20px; border-bottom: 2px solid #0f62fe; padding-top: 12px; padding-bottom: 4px; margin-bottom: 16px;">
  <p style="line-height: 10px;">
    <strong>Running a different version of IBM Blockchain Platform?</strong> Switch to version
    <a href="/docs/blockchain-sw?topic=blockchain-sw-sw-known-issues">2.1.2</a>,
    <a href="/docs/blockchain-sw-213?topic=blockchain-sw-213-sw-known-issues">2.1.3</a>,
    <a href="/docs/blockchain-sw-25?topic=blockchain-sw-25-sw-known-issues">2.5</a>,
    <a href="/docs/blockchain-sw-251?topic=blockchain-sw-251-sw-known-issues">2.5.1</a>
    <a href="/docs/blockchain-sw-252?topic=blockchain-sw-252-sw-known-issues">2.5.2</a>
    </p>
</div>







## Peer 1.4 Failure on VPC cluster
{: #sw-known-issues-peer14-failure}

Peer 1.4 might not work on VPC cluster due to an issue of mtu mismatch in DinD container.




