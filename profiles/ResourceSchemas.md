# All Profiles

> see https://aka.ms/autorest

``` yaml 
batch:
    output-folder: c:/work/github/azure-resource-manager-schemas/generated
    override-info:
      title: $(name)

    azureresourceschema: 
      note: This generates all the Azure Resource Schemas into the specified folder (merging as it goes)
``` 

## Specifications

This should include every single REST-API specification for every Azure Resource/Version this repository

``` yaml
batch:
    input-file: 
      - ../specification/customer-insights/resource-manager/Microsoft.CustomerInsights/2017-01-01/customer-insights.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/account.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/certificate.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/connection.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/connectionType.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/credential.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/definitions.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/dscCompilationJob.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/dscConfiguration.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/dscNode.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/dscNodeConfiguration.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/hybridRunbookWorkerGroup.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/job.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/jobSchedule.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/module.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/runbook.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/schedule.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/variable.json
      - ../specification/automation/resource-manager/Microsoft.Automation/2015-10-31/webhook.json
    
      - ../specification/advisor/resource-manager/Microsoft.Advisor/2016-07-12-preview/advisor.json
      - ../specification/advisor/resource-manager/Microsoft.Advisor/2017-03-31/advisor.json
      - ../specification/advisor/resource-manager/Microsoft.Advisor/2017-04-19/advisor.json
      - ../specification/analysisservices/resource-manager/Microsoft.AnalysisServices/2016-05-16/analysisservices.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-07-07/apimanagement.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-07-07/apimdeployment.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimanagement.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimapis.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimauthorizationservers.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimbackends.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimcertificates.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimdeployment.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimgroups.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimidentityprovider.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimloggers.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimnetworkstatus.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimopenidconnectproviders.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimproducts.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimproperties.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimquotas.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimreports.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimsubscriptions.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimtenant.json
      - ../specification/apimanagement/resource-manager/Microsoft.ApiManagement/2016-10-10/apimusers.json
      - ../specification/applicationinsights/resource-manager/microsoft.insights/2015-05-01/aiOperations_API.json
      - ../specification/applicationinsights/resource-manager/microsoft.insights/2015-05-01/components_API.json
      - ../specification/applicationinsights/resource-manager/microsoft.insights/2015-05-01/webTests_API.json
      - ../specification/applicationinsights/resource-manager/microsoft.insights/2015-05-01/componentContinuousExport_API.json
      - ../specification/applicationinsights/resource-manager/microsoft.insights/2015-05-01/componentFeaturesAndPricing_API.json
      - ../specification/applicationinsights/resource-manager/microsoft.insights/2015-05-01/componentApiKeys_API.json
      - ../specification/authorization/resource-manager/Microsoft.Authorization/2015-07-01/authorization.json
      - ../specification/batch/resource-manager/Microsoft.Batch/2015-12-01/BatchManagement.json
      - ../specification/batch/resource-manager/Microsoft.Batch/2017-01-01/BatchManagement.json
      - ../specification/batch/resource-manager/Microsoft.Batch/2017-05-01/BatchManagement.json
      - ../specification/billing/resource-manager/Microsoft.Billing/2017-02-27-preview/billing.json
      - ../specification/billing/resource-manager/Microsoft.Billing/2017-04-24-preview/billing.json
      - ../specification/cdn/resource-manager/Microsoft.Cdn/2015-06-01/cdn.json
      - ../specification/cdn/resource-manager/Microsoft.Cdn/2016-04-02/cdn.json
      - ../specification/cdn/resource-manager/Microsoft.Cdn/2016-10-02/cdn.json
      - ../specification/cognitiveservices/resource-manager/Microsoft.CognitiveServices/2016-02-01-preview/cognitiveservices.json
      - ../specification/cognitiveservices/resource-manager/Microsoft.CognitiveServices/2017-04-18/cognitiveservices.json
      - ../specification/commerce/resource-manager/Microsoft.Commerce/2015-06-01-preview/commerce.json
      - ../specification/compute/resource-manager/Microsoft.Compute/2015-06-15/compute.json
      - ../specification/compute/resource-manager/Microsoft.Compute/2016-03-30/compute.json
      - ../specification/compute/resource-manager/Microsoft.Compute/2016-04-30-preview/compute.json
      - ../specification/compute/resource-manager/Microsoft.Compute/2016-04-30-preview/disk.json
      - ../specification/compute/resource-manager/Microsoft.ContainerService/2015-11-01-preview/containerService.json
      - ../specification/compute/resource-manager/Microsoft.ContainerService/2016-03-30/containerService.json
      - ../specification/compute/resource-manager/Microsoft.ContainerService/2016-09-30/containerService.json
      - ../specification/compute/resource-manager/Microsoft.ContainerService/2017-01-31/containerService.json
      - ../specification/consumption/resource-manager/Microsoft.Consumption/2017-04-24-preview/consumption.json
      - ../specification/containerregistry/resource-manager/Microsoft.ContainerRegistry/2016-06-27-preview/containerregistry.json
      - ../specification/containerregistry/resource-manager/Microsoft.ContainerRegistry/2017-03-01/containerregistry.json
      - ../specification/containerregistry/resource-manager/Microsoft.ContainerRegistry/2017-06-01-preview/containerregistry.json
      
      - ../specification/datalake-analytics/resource-manager/Microsoft.DataLakeAnalytics/2015-10-01-preview/account.json
      - ../specification/datalake-analytics/resource-manager/Microsoft.DataLakeAnalytics/2015-10-01-preview/catalog.json
      - ../specification/datalake-analytics/resource-manager/Microsoft.DataLakeAnalytics/2015-11-01-preview/job.json
      - ../specification/datalake-analytics/resource-manager/Microsoft.DataLakeAnalytics/2016-03-20-preview/job.json
      - ../specification/datalake-analytics/resource-manager/Microsoft.DataLakeAnalytics/2016-11-01/account.json
      - ../specification/datalake-analytics/resource-manager/Microsoft.DataLakeAnalytics/2016-11-01/catalog.json
      - ../specification/datalake-analytics/resource-manager/Microsoft.DataLakeAnalytics/2016-11-01/job.json
      - ../specification/datalake-store/resource-manager/Microsoft.DataLakeStore/2015-10-01-preview/account.json
      - ../specification/datalake-store/resource-manager/Microsoft.DataLakeStore/2015-10-01-preview/filesystem.json
      - ../specification/datalake-store/resource-manager/Microsoft.DataLakeStore/2016-11-01/account.json
      - ../specification/datalake-store/resource-manager/Microsoft.DataLakeStore/2016-11-01/filesystem.json
      - ../specification/datamigration/resource-manager/Microsoft.DataMigration/2017-11-15-preview/datamigration.json
      - ../specification/datamigration/resource-manager/Microsoft.DataMigration/2018-03-15-preview/datamigration.json
      - ../specification/devtestlabs/resource-manager/Microsoft.DevTestLab/2015-05-21-preview/DTL.json
      - ../specification/devtestlabs/resource-manager/Microsoft.DevTestLab/2016-05-15/DTL.json
      - ../specification/dns/resource-manager/Microsoft.Network/2015-05-04-preview/dns.json
      - ../specification/dns/resource-manager/Microsoft.Network/2016-04-01/dns.json
      - ../specification/documentdb/resource-manager/Microsoft.DocumentDB/2015-04-08/documentdb.json
      - ../specification/eventhub/resource-manager/Microsoft.EventHub/2015-08-01/EventHub.json
      - ../specification/hdinsight/resource-manager/Microsoft.HDInsight/2015-03-01-preview/applications.json
      - ../specification/hdinsight/resource-manager/Microsoft.HDInsight/2015-03-01-preview/capabilities.json
      - ../specification/hdinsight/resource-manager/Microsoft.HDInsight/2015-03-01-preview/cluster.json
      - ../specification/hdinsight/resource-manager/Microsoft.HDInsight/2015-03-01-preview/configurations.json
      - ../specification/hdinsight/resource-manager/Microsoft.HDInsight/2015-03-01-preview/extensions.json
      - ../specification/hdinsight/resource-manager/Microsoft.HDInsight/2015-03-01-preview/operations.json
      - ../specification/hdinsight/resource-manager/Microsoft.HDInsight/2015-03-01-preview/scriptActions.json
      - ../specification/insights/resource-manager/microsoft.insights/2014-04-01/insightsClient_UsageMetrics.json
      - ../specification/insights/resource-manager/microsoft.insights/2015-04-01/insightsClient_EventCategories.json
      - ../specification/insights/resource-manager/microsoft.insights/2015-04-01/insightsClient_Events.json
      - ../specification/insights/resource-manager/microsoft.insights/2015-04-01/insightsClient_TenantEvents.json
      - ../specification/insights/resource-manager/microsoft.insights/2015-04-01/insightsManagementClient_Autoscale.json
      - ../specification/insights/resource-manager/microsoft.insights/2015-07-01/insightsManagementClient_DiagnosticsSettings.json
      - ../specification/insights/resource-manager/microsoft.insights/2016-03-01/insightsClient_MetricDefinitions.json
      - ../specification/insights/resource-manager/microsoft.insights/2016-03-01/insightsManagementClient_AlertRules.json
      - ../specification/insights/resource-manager/microsoft.insights/2016-03-01/insightsManagementClient_AlertRulesIncidents.json
      - ../specification/insights/resource-manager/microsoft.insights/2016-03-01/insightsManagementClient_LogProfiles.json
      - ../specification/insights/resource-manager/microsoft.insights/2016-09-01/insightsClient_Metrics.json
      - ../specification/intune/resource-manager/Microsoft.Intune/2015-01-14-preview/intune.json
      - ../specification/intune/resource-manager/Microsoft.Intune/2015-01-14-privatepreview/intune.json
      - ../specification/iothub/resource-manager/Microsoft.Devices/2016-02-03/iothub.json
      - ../specification/iothub/resource-manager/Microsoft.Devices/2017-01-19/iothub.json
      - ../specification/keyvault/resource-manager/Microsoft.KeyVault/2015-06-01/keyvault.json
      - ../specification/logic/resource-manager/Microsoft.Logic/2015-02-01-preview/logic.json
      - ../specification/logic/resource-manager/Microsoft.Logic/2015-08-01-preview/logic.json
      - ../specification/logic/resource-manager/Microsoft.Logic/2016-06-01/logic.json
      - ../specification/machinelearning/resource-manager/Microsoft.MachineLearning/2016-05-01-preview/commitmentPlans.json
      - ../specification/machinelearning/resource-manager/Microsoft.MachineLearning/2016-05-01-preview/webservices.json
      - ../specification/machinelearning/resource-manager/Microsoft.MachineLearning/2017-01-01/webservices.json
      - ../specification/mediaservices/resource-manager/Microsoft.Media/2015-10-01/media.json
      - ../specification/mobileengagement/resource-manager/Microsoft.MobileEngagement/2014-12-01/mobile-engagement.json
      - ../specification/monitor/resource-manager/microsoft.insights/2015-04-01/autoscale_API.json
      - ../specification/monitor/resource-manager/microsoft.insights/2015-07-01/serviceDiagnosticsSettings_API.json
      - ../specification/monitor/resource-manager/microsoft.insights/2016-03-01/alertRulesIncidents_API.json
      - ../specification/monitor/resource-manager/microsoft.insights/2016-03-01/alertRules_API.json
      - ../specification/monitor/resource-manager/microsoft.insights/2016-03-01/logProfiles_API.json
      - ../specification/monitor/resource-manager/microsoft.insights/2016-09-01/serviceDiagnosticsSettings_API.json
      - ../specification/monitor/resource-manager/microsoft.insights/2017-03-01-preview/activityLogAlerts_API.json
      - ../specification/monitor/resource-manager/microsoft.insights/2017-04-01/actionGroups_API.json
      - ../specification/monitor/resource-manager/microsoft.insights/2017-04-01/activityLogAlerts_API.json
      - ../specification/network/resource-manager/microsoft.Compute/2016-09-01/vmssNetworkInterface.json
      - ../specification/network/resource-manager/microsoft.Compute/2016-12-01/vmssNetworkInterface.json
      - ../specification/network/resource-manager/microsoft.Compute/2017-03-01/vmssNetworkInterface.json
      - ../specification/network/resource-manager/Microsoft.Network/2015-05-01-preview/network.json
      - ../specification/network/resource-manager/Microsoft.Network/2015-06-15/network.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-03-30/network.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-06-01/network.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-09-01/applicationGateway.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-09-01/checkDnsAvailability.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-09-01/expressRouteCircuit.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-09-01/loadBalancer.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-09-01/network.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-09-01/networkInterface.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-09-01/networkSecurityGroup.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-09-01/networkWatcher.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-09-01/publicIpAddress.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-09-01/routeTable.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-09-01/usage.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-09-01/virtualNetwork.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-09-01/virtualNetworkGateway.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-12-01/applicationGateway.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-12-01/checkDnsAvailability.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-12-01/expressRouteCircuit.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-12-01/loadBalancer.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-12-01/network.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-12-01/networkInterface.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-12-01/networkSecurityGroup.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-12-01/networkWatcher.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-12-01/publicIpAddress.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-12-01/routeFilter.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-12-01/routeTable.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-12-01/serviceCommunity.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-12-01/usage.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-12-01/virtualNetwork.json
      - ../specification/network/resource-manager/Microsoft.Network/2016-12-01/virtualNetworkGateway.json
      - ../specification/network/resource-manager/Microsoft.Network/2017-03-01/applicationGateway.json
      - ../specification/network/resource-manager/Microsoft.Network/2017-03-01/checkDnsAvailability.json
      - ../specification/network/resource-manager/Microsoft.Network/2017-03-01/expressRouteCircuit.json
      - ../specification/network/resource-manager/Microsoft.Network/2017-03-01/loadBalancer.json
      - ../specification/network/resource-manager/Microsoft.Network/2017-03-01/network.json
      - ../specification/network/resource-manager/Microsoft.Network/2017-03-01/networkInterface.json
      - ../specification/network/resource-manager/Microsoft.Network/2017-03-01/networkSecurityGroup.json
      - ../specification/network/resource-manager/Microsoft.Network/2017-03-01/networkWatcher.json
      - ../specification/network/resource-manager/Microsoft.Network/2017-03-01/publicIpAddress.json
      - ../specification/network/resource-manager/Microsoft.Network/2017-03-01/routeFilter.json
      - ../specification/network/resource-manager/Microsoft.Network/2017-03-01/routeTable.json
      - ../specification/network/resource-manager/Microsoft.Network/2017-03-01/serviceCommunity.json
      - ../specification/network/resource-manager/Microsoft.Network/2017-03-01/usage.json
      - ../specification/network/resource-manager/Microsoft.Network/2017-03-01/virtualNetwork.json
      - ../specification/network/resource-manager/Microsoft.Network/2017-03-01/virtualNetworkGateway.json
      - ../specification/notificationhubs/resource-manager/Microsoft.NotificationHubs/2014-09-01/notificationhubs.json
      - ../specification/notificationhubs/resource-manager/Microsoft.NotificationHubs/2016-03-01/notificationhubs.json
      - ../specification/notificationhubs/resource-manager/Microsoft.NotificationHubs/2017-04-01/notificationhubs.json
      - ../specification/operationalinsights/resource-manager/Microsoft.OperationalInsights/2015-03-20/OperationalInsights.json
      - ../specification/operationalinsights/resource-manager/Microsoft.OperationalInsights/2015-11-01-preview/OperationalInsights.json
      - ../specification/powerbiembedded/resource-manager/Microsoft.PowerBI/2016-01-29/powerbiembedded.json
      - ../specification/recoveryservices/resource-manager/Microsoft.RecoveryServices/2016-06-01/registeredidentities.json
      - ../specification/recoveryservices/resource-manager/Microsoft.RecoveryServices/2016-06-01/replicationusages.json
      - ../specification/recoveryservices/resource-manager/Microsoft.RecoveryServices/2016-06-01/vaults.json
      - ../specification/recoveryservices/resource-manager/Microsoft.RecoveryServices/2016-06-01/vaultusages.json
      - ../specification/recoveryservices/resource-manager/Microsoft.RecoveryServices/2016-12-01/backup.json
      - ../specification/recoveryservicesbackup/resource-manager/Microsoft.RecoveryServices/2016-06-01/recoveryservicesbackup.json
      - ../specification/recoveryservicesbackup/resource-manager/Microsoft.RecoveryServices/2016-06-01/registeredIdentities.json
      - ../specification/recoveryservicesbackup/resource-manager/Microsoft.RecoveryServices/2016-12-01/backupManagement.json
      - ../specification/redis/resource-manager/Microsoft.Cache/2015-08-01/redis.json
      - ../specification/redis/resource-manager/Microsoft.Cache/2016-04-01/redis.json
      - ../specification/relay/resource-manager/Microsoft.Relay/2016-07-01/relay.json
      - ../specification/resourcehealth/resource-manager/Microsoft.ResourceHealth/2015-01-01/resourcehealth.json
      - ../specification/resources/resource-manager/Microsoft.Authorization/2015-01-01/locks.json
      - ../specification/resources/resource-manager/Microsoft.Authorization/2015-10-01-preview/policy.json
      - ../specification/resources/resource-manager/Microsoft.Authorization/2016-04-01/policy.json
      - ../specification/resources/resource-manager/Microsoft.Authorization/2016-09-01/locks.json
      - ../specification/resources/resource-manager/Microsoft.Authorization/2016-12-01/policy.json
      - ../specification/resources/resource-manager/Microsoft.Features/2015-12-01/features.json
      - ../specification/resources/resource-manager/Microsoft.Resources/2015-11-01/resources.json
      - ../specification/resources/resource-manager/Microsoft.Resources/2015-11-01/subscriptions.json
      - ../specification/resources/resource-manager/Microsoft.Resources/2016-02-01/resources.json
      - ../specification/resources/resource-manager/Microsoft.Resources/2016-06-01/subscriptions.json
      - ../specification/resources/resource-manager/Microsoft.Resources/2016-07-01/resources.json
      - ../specification/resources/resource-manager/Microsoft.Resources/2016-09-01/links.json
      - ../specification/resources/resource-manager/Microsoft.Resources/2016-09-01/resources.json
      - ../specification/resources/resource-manager/Microsoft.Resources/2017-05-10/resources.json
      - ../specification/resources/resource-manager/Microsoft.Solutions/2016-09-01-preview/managedapplications.json
      - ../specification/scheduler/resource-manager/Microsoft.Scheduler/2014-08-01-preview/scheduler.json
      - ../specification/scheduler/resource-manager/Microsoft.Scheduler/2016-01-01/scheduler.json
      - ../specification/scheduler/resource-manager/Microsoft.Scheduler/2016-03-01/scheduler.json
      - ../specification/search/resource-manager/Microsoft.Search/2015-02-28/search.json
      - ../specification/search/resource-manager/Microsoft.Search/2015-08-19/search.json
      - ../specification/servermanagement/resource-manager/Microsoft.ServerManagement/2015-07-01-preview/servermanagement.json
      - ../specification/servermanagement/resource-manager/Microsoft.ServerManagement/2016-07-01-preview/servermanagement.json
      - ../specification/service-map/resource-manager/Microsoft.OperationalInsights/2015-11-01-preview/arm-service-map.json
      - ../specification/servicebus/resource-manager/Microsoft.ServiceBus/2015-08-01/servicebus.json
      - ../specification/servicefabric/resource-manager/Microsoft.ServiceFabric/2016-09-01/servicefabric.json
      - ../specification/sql/resource-manager/Microsoft.Sql/2014-04-01/backups.json
      - ../specification/sql/resource-manager/Microsoft.Sql/2014-04-01/capabilities.json
      - ../specification/sql/resource-manager/Microsoft.Sql/2014-04-01/databaseSecurityAlertPolicies.json
      - ../specification/sql/resource-manager/Microsoft.Sql/2014-04-01/firewallRules.json
      - ../specification/sql/resource-manager/Microsoft.Sql/2014-04-01/importExport.json
      - ../specification/sql/resource-manager/Microsoft.Sql/2014-04-01/operations.json
      - ../specification/sql/resource-manager/Microsoft.Sql/2014-04-01/replicationLinks.json
      - ../specification/sql/resource-manager/Microsoft.Sql/2014-04-01/serverAzureADAdministrators.json
      - ../specification/sql/resource-manager/Microsoft.Sql/2014-04-01/servers.json
      - ../specification/sql/resource-manager/Microsoft.Sql/2014-04-01/sql.core.json
      - ../specification/sql/resource-manager/Microsoft.Sql/2015-05-01-preview/blobAuditingPolicies.json
      - ../specification/sql/resource-manager/Microsoft.Sql/2015-05-01-preview/failoverGroups.json
      - ../specification/sql/resource-manager/Microsoft.Sql/2015-05-01-preview/virtualNetworkRules.json
      - ../specification/storage/resource-manager/Microsoft.Storage/2015-05-01-preview/storage.json
      - ../specification/storage/resource-manager/Microsoft.Storage/2015-06-15/storage.json
      - ../specification/storage/resource-manager/Microsoft.Storage/2016-01-01/storage.json
      - ../specification/storage/resource-manager/Microsoft.Storage/2016-05-01/storage.json
      - ../specification/storage/resource-manager/Microsoft.Storage/2016-12-01/storage.json
      - ../specification/storageimportexport/resource-manager/Microsoft.ImportExport/2016-11-01/storageimportexport.json
      - ../specification/storsimple8000series/resource-manager/Microsoft.StorSimple/2017-06-01/storsimple.json
      
      - ../specification/trafficmanager/resource-manager/Microsoft.Network/2015-11-01/trafficmanager.json
      - ../specification/trafficmanager/resource-manager/Microsoft.Network/2017-03-01/trafficmanager.json
      - ../specification/web/resource-manager/Microsoft.CertificateRegistration/2015-08-01/AppServiceCertificateOrders.json
      - ../specification/web/resource-manager/Microsoft.DomainRegistration/2015-04-01/Domains.json
      - ../specification/web/resource-manager/Microsoft.DomainRegistration/2015-04-01/TopLevelDomains.json
      - ../specification/web/resource-manager/Microsoft.Web/2015-08-01/service.json
      - ../specification/web/resource-manager/Microsoft.Web/2015-08-01-preview/logicAppsManagementClient.json
      - ../specification/web/resource-manager/Microsoft.Web/2016-03-01/Certificates.json
      - ../specification/web/resource-manager/Microsoft.Web/2016-03-01/DeletedWebApps.json
      - ../specification/web/resource-manager/Microsoft.Web/2016-03-01/Provider.json
      - ../specification/web/resource-manager/Microsoft.Web/2016-03-01/Recommendations.json
      - ../specification/web/resource-manager/Microsoft.Web/2016-03-01/ResourceProvider.json
      - ../specification/web/resource-manager/Microsoft.Web/2016-08-01/WebApps.json
      - ../specification/web/resource-manager/Microsoft.Web/2016-09-01/AppServiceEnvironments.json
      - ../specification/web/resource-manager/Microsoft.Web/2016-09-01/AppServicePlans.json
      
      # some invalid swagger
      # - ../specification/timeseriesinsights/resource-manager/Microsoft.TimeSeriesInsights/2017-02-28-preview/timeseriesinsights.json
```  