---

copyright:
  years: 2024
lastupdated: "2024-10-14"

keywords: customer responsibilities, IBM responsibilities, terms and conditions, disaster recovery, deployable architecture

subcollection: platform-automation-hub

---

{{site.data.keyword.attribute-definition-list}}

# Your responsibilities when using the DevSecOps Application Lifecycle Management deployable architecture
{: #responsibilities-automation}

Learn about the management responsibilities and terms and conditions that you have when you use the DevSecOps Application Lifecycle Management deployable architecture. 
{: shortdesc}

- For more information about the responsibilities for you and for {{site.data.keyword.IBM}} when you use a deployable architecture, see [Understanding your responsibilities when you use deployable architectures](/docs/secure-enterprise?topic=secure-enterprise-responsibilities-deployable-architectures).
- For a high-level view of the service types in {{site.data.keyword.cloud}} and the breakdown of responsibilities between you and {{site.data.keyword.IBM_notm}} for each type, see [Shared responsibilities for using {{site.data.keyword.cloud}} products](/docs/overview?topic=overview-shared-responsibilities).
- For the overall terms of use, see [{{site.data.keyword.cloud_notm}} Terms and Notices](/docs/overview?topic=overview-terms).
  
## Incident and operations management
{: #incident-and-ops}

Incident and operations management includes tasks such as monitoring, event management, high availability, problem determination, recovery, and full state backup and recovery.

The DevSecOps Application Lifecycle Management deployable architecture does not identify specific responsibilities in this area. For more information about the general incident and operations management responsibilities when you use deployable architectures, see [Incident and operations management](/docs/secure-enterprise?topic=secure-enterprise-responsibilities-deployable-architectures#incident-and-ops-da).

## Change management
{: #change-management}

Change management includes tasks such as deployment, configuration, upgrades, patching, configuration changes, and deletion.

The DevSecOps Application Lifecycle Management deployable architecture does not identify specific responsibilities in this area. For more information about the general change management responsibilities when you use deployable architectures, see [Change management](/docs/secure-enterprise?topic=secure-enterprise-responsibilities-deployable-architectures#change-management-da).

## Identity and access management
{: #iam-responsibilities}

Identity and access management includes tasks such as authentication, authorization, access control policies, and approving, granting, and revoking access.

| Task | {{site.data.keyword.IBM_notm}} responsibilities | Your responsibilities |
|----------|-----------------------|--------|
| Secure with least privilege | Document the minimal IAM access requirements to run the dpeloyable architecture. | Ensure that the documented IAM requirements are met. |
| Manage secrets | N/A  | * Generate the necessary secrets (IAM API keys) and configure trusted profiles that are required for the deployable architecture. \n * Manage generated secrets by following secure best practices. |
{: row-headers}
{: caption="Responsibilities for identity and access management" caption-side="bottom"}
{: summary="The rows are read from left to right. The first column describes the task that the customer or IBM might be responsibility for. The second column describes {{site.data.keyword.IBM_notm}} responsibilities for that task. The third column describes your responsibilities as the customer for that task."}

For more information about the general IAM responsibilities when you use deployable architectures, see [Identity and access management](/docs/secure-enterprise?topic=secure-enterprise-responsibilities-deployable-architectures#iam-responsibilities-da).

## Security and regulation compliance
{: #security-compliance}

Security and regulation compliance includes tasks such as security controls implementation and compliance certification.

| Task | {{site.data.keyword.IBM_notm}} responsibilities | Your responsibilities |
|----------|-----------------------|--------|
| Meet security and compliance objectives | Provide a secure deployable architecture that complies with declared standards. For more information about data security, see [How do I know that my data is safe?](/docs/overview?topic=overview-security).
| Verify configuration changes | | Understand the effects on the security and compliance posture of any user-initiated changes to the default configuration. Run {{site.data.keyword.compliance_long}} checks if needed to ensure that the deployable architecture remains in compliance. |
{: row-headers}
{: caption="Responsibilities for security and regulation compliance" caption-side="bottom"}
{: summary="The rows are read from left to right. The first column describes the task that the customer or IBM might be responsibility for. The second column describes {{site.data.keyword.IBM_notm}} responsibilities for that task. The third column describes your responsibilities as the customer for that task."}

For more information about the general security and regulation compliance responsibilities when you use deployable architectures, see [Security and regulation compliance](/docs/secure-enterprise?topic=secure-enterprise-responsibilities-deployable-architectures#security-compliance-da).

## Disaster recovery
{: #disaster-recovery}

Disaster recovery includes tasks such as providing dependencies on disaster recovery sites, creating disaster recovery environments, data and configuration backup, replicating data and configuration to the disaster recovery environment, and failover on disaster events.

| Task | {{site.data.keyword.IBM_notm}} responsibilities | Your responsibilities |
|----------|-----------------------|--------|
| Enure availability of {{site.data.keyword.appconfig_short}} components | See [{{site.data.keyword.IBM_notm}} responsibilities](/docs/app-configuration?topic=app-configuration-ac-responsibilities#ac-disaster-recovery) when using {{site.data.keyword.appconfig_short}}. | See [your responsibilities](/docs/app-configuration?topic=app-configuration-ac-responsibilities#ac-disaster-recovery) when using {{site.data.keyword.appconfig_short}}. |
| Back up and restore {{site.data.keyword.contdelivery_short}} toolchain data | See [{{site.data.keyword.IBM_notm}} responsibilities](/docs/ContinuousDelivery?topic=ContinuousDelivery-responsibilities-cd#disaster-recovery) when using {{site.data.keyword.contdelivery_short}}. | See [your responsibilities](/docs/ContinuousDelivery?topic=ContinuousDelivery-responsibilities-cd#disaster-recovery) when using {{site.data.keyword.contdelivery_short}}. |
| Ensure availability of {{site.data.keyword.en_short}} components | See [{{site.data.keyword.IBM_notm}} responsibilities](/docs/event-notifications?topic=event-notifications-en-responsibilities#en-disaster-recovery) when using {{site.data.keyword.en_short}}. | See [your responsibilities](/docs/event-notifications?topic=event-notifications-en-responsibilities#en-disaster-recovery) when using {{site.data.keyword.en_short}}. |
{: row-headers}
{: caption="Responsibilities for disaster recovery" caption-side="top"}
{: summary="The rows are read from left to right. The first column describes the task that the customer or IBM might be responsibility for. The second column describes {{site.data.keyword.IBM_notm}} responsibilities for that task. The third column describes your responsibilities as the customer for that task."}

For more information about the general disaster recovery responsibilities when you use deployable architectures, see [Disaster recovery](/docs/secure-enterprise?topic=secure-enterprise-responsibilities-deployable-architectures#disaster-recovery-da).
