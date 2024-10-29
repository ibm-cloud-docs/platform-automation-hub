---

copyright:
  years: 2024, 2024
lastupdated: "2024-10-29"


keywords: platform automation
subcollection: platform-automation-hub

---


{{site.data.keyword.attribute-definition-list}}

# Comparing Platform Automation products
{: #compare}

{{site.data.keyword.cloud}} offers several products for platform automation, including {{site.data.keyword.en_short}}, {{site.data.keyword.appconfig_short}}, {{site.data.keyword.bpshort}}, and {{site.data.keyword.contdelivery_short}}.
{: shortdesc}

## {{site.data.keyword.en_full_notm}}
{: #compare-en}

{{site.data.keyword.en_short}} is a routing service that provides information about critical events that occur in your {{site.data.keyword.cloud_notm}} account or triggers automated actions by using webhooks.

| Feature | Description |
|----------|---------|
| Centralized alert routing | From a single dashboard, route event notifications from {{site.data.keyword.compliance_long}} (SCC), {{site.data.keyword.secrets-manager_full_notm}}, or {{site.data.keyword.monitoringfull_notm}} to relevant stakeholders. |
| Filtered source events | Filter incoming events into one or more topics. Use filters to fine-tune topic content to adjust the event set you need. Connect multiple topics to one source, or connect multiple sources to a single topic. |
| Built-in communication providers | Add the included basic email and SMS capabilities as destinations to any {{site.data.keyword.en_short}} subscription for instant connectivity. |
| Webhooks | Use webhooks to integrate outbound notifications into management and collaboration tools or into your own applications. |
| Multi-destination routing | Route a single event notification to many destinations with just a few clicks - a person, your application, or your automation suite all at the same time. |
| Governance | Track user and notification activity can be tracked through {{site.data.keyword.cloudaccesstraillong_notm}} and {{site.data.keyword.loganalysislong_notm}} so you can closely monitor what happened and when. |
{: row-headers}
{: caption="Event Notifications benefits" caption-side="bottom"}

## {{site.data.keyword.appconfig_notm}}
{: #compare-appcfg}

{{site.data.keyword.appconfig_short}} is a centralized feature management and configuration service for use with web and mobile applications, microservices, and distributed environments. Instrument your applications with {{site.data.keyword.appconfig_short}} SDKs, and use the {{site.data.keyword.appconfig_short}} dashboard or {{site.data.keyword.appconfig_short}} administrator API to define features flags, which are organized into collections and targeted to segments.

| Feature | Description |
|----------|---------|
| Centralized configuration | Configure multiple, distributed resources from a central location. Use collections to organize your flags by app or resource. |
| Dark launch | Include restricted-availability features in your deployments, and activate them when you're ready. |
| Segmented feature rollout | Activate features for different segments at different times or vary features by segment. |
| Feature rollback | Instantly revert problematic features. |
| Phased feature rollout | Progressively release features through the use of feature flags. |
| Configuration aggregator | Collect metadata of multiple, distributed resources in {{site.data.keyword.cloud_notm}} accounts for governance and compliance initiatives. |
{: row-headers}
{: caption="App Configuration benefits" caption-side="bottom"}

## {{site.data.keyword.bplong_notm}}
{: #compare-schematics}

{{site.data.keyword.bpshort}} provides a powerful set of Infrastructure as Code (IaC) tools - Terraform, Ansible, and Helm - to program your cloud infrastructure. You can run end-to-end automation to build multiple stacks of cloud resources, manage the lifecycle and configuration changes, deploy your app workloads, and perform Day 2 operations.

{{../schematics/sc-about-overview.md#benefits-table}}

## {{site.data.keyword.cloud_notm}} {{site.data.keyword.contdelivery_short}}
{: #compare-cd}

{{site.data.keyword.contdelivery_short}} provides DevOps or DevSecOps practices and industry-leading tools for building, testing, and delivering applications.

| Feature | Description |
|----------|---------|
| Integrated DevOps toolchains | Simplify how you build, deploy, and manage your apps. |
| Toolchain templates | Use customizable templates to quickly create toolchains for DevSecOps, Kubernetes deployments, and more.
| Automated delivery pipelines | Use Tekton-based delivery pipelines to repeatably build, test, and deploy with minimal human intervention. |
| Git repos and issue tracking | Manage source code with Git repositories hosted by {{site.data.keyword.IBM_notm}}. |
{: row-headers}
{: caption="Continuous Delivery benefits" caption-side="bottom"}
