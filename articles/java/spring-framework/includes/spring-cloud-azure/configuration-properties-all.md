---
ms.date: 04-26-2022
ms.author: v-yonghuiye
---

## List of configuration properties

> [!div class="mx-tdBreakAll"]
> |Property | Description|
> |---------|------------|
> |spring.cloud.azure.active-directory.app-id-uri | App ID URI which might be used in the "aud" claim of an id_token. |
> |spring.cloud.azure.active-directory.application-type | Type of the Azure AD application. |
> |spring.cloud.azure.active-directory.authenticate-additional-parameters | Add additional parameters to the Authorization URL. |
> |spring.cloud.azure.active-directory.authorization-clients | The OAuth2 authorization clients. |
> |spring.cloud.azure.active-directory.b2c.app-id-uri | App ID URI which might be used in the "aud" claim of a token. |
> |spring.cloud.azure.active-directory.b2c.authenticate-additional-parameters | Additional parameters for authentication. |
> |spring.cloud.azure.active-directory.b2c.authorization-clients | Specify client configuration. |
> |spring.cloud.azure.active-directory.b2c.base-uri | Azure AD B2C endpoint base uri. |
> |spring.cloud.azure.active-directory.b2c.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.active-directory.b2c.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.active-directory.b2c.enabled | Whether to enable Azure Active Directory B2C related auto-configuration. The default value is `false`. |
> |spring.cloud.azure.active-directory.b2c.jwt-connect-timeout | Connection Timeout for the JWKSet Remote URL call. |
> |spring.cloud.azure.active-directory.b2c.jwt-read-timeout | Read Timeout for the JWKSet Remote URL call. |
> |spring.cloud.azure.active-directory.b2c.jwt-size-limit | Size limit in Bytes of the JWKSet Remote URL call. |
> |spring.cloud.azure.active-directory.b2c.login-flow | Specify the primary sign-in flow key. The default value is `sign-up-or-sign-in`. |
> |spring.cloud.azure.active-directory.b2c.logout-success-url | Redirect url after logout. The default value is `http://localhost:8080/login`. |
> |spring.cloud.azure.active-directory.b2c.profile.tenant-id | Azure Tenant ID. |
> |spring.cloud.azure.active-directory.b2c.reply-url | Reply url after get authorization code. The default value is `{baseUrl}/login/oauth2/code/`. |
> |spring.cloud.azure.active-directory.b2c.user-flows | User flows. |
> |spring.cloud.azure.active-directory.b2c.user-name-attribute-name | User name attribute name. |
> |spring.cloud.azure.active-directory.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.active-directory.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.active-directory.enabled | Whether to enable Azure Active Directory related auto-configuration. The default value is `false`. |
> |spring.cloud.azure.active-directory.jwk-set-cache-lifespan | The lifespan of the cached JWK set before it expires, default is 5 minutes. The default value is `5m`. |
> |spring.cloud.azure.active-directory.jwk-set-cache-refresh-time | The refresh time of the cached JWK set before it expires, default is 5 minutes. The default value is `5m`. |
> |spring.cloud.azure.active-directory.jwt-connect-timeout | Connection Timeout for the JWKSet Remote URL call. |
> |spring.cloud.azure.active-directory.jwt-read-timeout | Read Timeout for the JWKSet Remote URL call. |
> |spring.cloud.azure.active-directory.jwt-size-limit | Size limit in Bytes of the JWKSet Remote URL call. |
> |spring.cloud.azure.active-directory.post-logout-redirect-uri | The redirect uri after logout. |
> |spring.cloud.azure.active-directory.profile.cloud-type | Name of the Azure cloud to connect to. Supported types are: AZURE, AZURE_CHINA, AZURE_GERMANY, AZURE_US_GOVERNMENT, OTHER. |
> |spring.cloud.azure.active-directory.profile.environment.active-directory-endpoint | Azure Active Directory endpoint. For example: https://login.microsoftonline.com/ |
> |spring.cloud.azure.active-directory.profile.environment.microsoft-graph-endpoint | Microsoft Graph endpoint. For example: https://graph.microsoft.com/ |
> |spring.cloud.azure.active-directory.profile.tenant-id | Azure Tenant ID. |
> |spring.cloud.azure.active-directory.redirect-uri-template | Redirection Endpoint: Used by the authorization server to return responses containing authorization credentials to the client via the resource owner user-agent. The default value is `{baseUrl}/login/oauth2/code/`. |
> |spring.cloud.azure.active-directory.resource-server.claim-to-authority-prefix-map | Configure which claim will be used to build GrantedAuthority, and prefix of the GrantedAuthority's string value. Default value is: "scp" -> "SCOPE_", "roles" -> "APPROLE_". |
> |spring.cloud.azure.active-directory.resource-server.principal-claim-name | Configure which claim in access token be returned in AuthenticatedPrincipal#getName. Default value is "sub". |
> |spring.cloud.azure.active-directory.session-stateless | If true activates the stateless auth filter Azure ADAppRoleStatelessAuthenticationFilter. The default is false which activates Azure ADAuthenticationFilter. The default value is `false`. |
> |spring.cloud.azure.active-directory.user-group.allowed-group-ids | The group ids can be used to construct GrantedAuthority. |
> |spring.cloud.azure.active-directory.user-group.allowed-group-names | The group names can be used to construct GrantedAuthority. |
> |spring.cloud.azure.active-directory.user-group.use-transitive-members | If "true", use "v1.0/me/transitiveMemberOf" to get members. Otherwise, use "v1.0/me/memberOf". The default value is `false`. |
> |spring.cloud.azure.active-directory.user-name-attribute | Decide which claim to be principal's name. |
> |spring.cloud.azure.appconfiguration.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.appconfiguration.client.connect-timeout | Amount of time the request attempts to connect to the remote host and the connection is resolved. |
> |spring.cloud.azure.appconfiguration.client.connection-idle-timeout | Amount of time before an idle connection. |
> |spring.cloud.azure.appconfiguration.client.headers | Comma-delimited list of headers applied to each request sent with client. |
> |spring.cloud.azure.appconfiguration.client.logging.allowed-header-names | Comma-delimited list of allowedlist headers that should be logged. |
> |spring.cloud.azure.appconfiguration.client.logging.allowed-query-param-names | Comma-delimited list of allowedlist query parameters. |
> |spring.cloud.azure.appconfiguration.client.logging.level | The level of detail to log on HTTP messages. |
> |spring.cloud.azure.appconfiguration.client.logging.pretty-print-body | Whether to pretty print the message bodies. |
> |spring.cloud.azure.appconfiguration.client.maximum-connection-pool-size | Maximum connection pool size used by the underlying HTTP client. |
> |spring.cloud.azure.appconfiguration.client.read-timeout | Amount of time used when reading the server response. |
> |spring.cloud.azure.appconfiguration.client.response-timeout | Amount of time used when waiting for a server to reply. |
> |spring.cloud.azure.appconfiguration.client.write-timeout | Amount of time each request being sent over the wire. |
> |spring.cloud.azure.appconfiguration.connection-string | Connection string of the Azure App Configuration instance. |
> |spring.cloud.azure.appconfiguration.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.appconfiguration.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.appconfiguration.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.appconfiguration.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.appconfiguration.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.appconfiguration.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.appconfiguration.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.appconfiguration.enabled | Whether an Azure Service is enabled. The default value is `true`. |
> |spring.cloud.azure.appconfiguration.endpoint | Endpoint of the Azure App Configuration instance. |
> |spring.cloud.azure.appconfiguration.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.appconfiguration.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.appconfiguration.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.appconfiguration.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.appconfiguration.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.appconfiguration.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.appconfiguration.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.appconfiguration.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.appconfiguration.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.appconfiguration.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.appconfiguration.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.appconfiguration.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.appconfiguration.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.appconfiguration.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.appconfiguration.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.appconfiguration.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.appconfiguration.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.appconfiguration.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.appconfiguration.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.appconfiguration.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.appconfiguration.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.appconfiguration.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.appconfiguration.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.appconfiguration.proxy.non-proxy-hosts | A list of hosts or CIDR to not use proxy HTTP/HTTPS connections through. |
> |spring.cloud.azure.appconfiguration.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.appconfiguration.proxy.port | The port of the proxy. |
> |spring.cloud.azure.appconfiguration.proxy.type | Type of the proxy. |
> |spring.cloud.azure.appconfiguration.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.appconfiguration.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.appconfiguration.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.appconfiguration.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.appconfiguration.retry.exponential.base-delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.appconfiguration.retry.exponential.max-delay | Maximum permissible amount of time between retry attempts. |
> |spring.cloud.azure.appconfiguration.retry.exponential.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.appconfiguration.retry.fixed.delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.appconfiguration.retry.fixed.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.appconfiguration.retry.mode | Retry backoff mode. |
> |spring.cloud.azure.appconfiguration.service-version | Version of the app configuration service to be used when making request. |
> |spring.cloud.azure.auto-create-resources | Whether to create Azure resources automatically. This is a legacy property. The default value is `false`. |
> |spring.cloud.azure.client-id | Client ID to use when performing service principal authentication with Azure. This is a legacy property. |
> |spring.cloud.azure.client-secret | Client secret to use when performing service principal authentication with Azure. This is a legacy property. |
> |spring.cloud.azure.client.amqp.transport-type | Transport type for AMQP-based client. |
> |spring.cloud.azure.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.client.http.connect-timeout | Amount of time the request attempts to connect to the remote host and the connection is resolved. |
> |spring.cloud.azure.client.http.connection-idle-timeout | Amount of time before an idle connection. |
> |spring.cloud.azure.client.http.headers | Comma-delimited list of headers applied to each request sent with client. |
> |spring.cloud.azure.client.http.logging.allowed-header-names | Comma-delimited list of allowedlist headers that should be logged. |
> |spring.cloud.azure.client.http.logging.allowed-query-param-names | Comma-delimited list of allowedlist query parameters. |
> |spring.cloud.azure.client.http.logging.level | The level of detail to log on HTTP messages. |
> |spring.cloud.azure.client.http.logging.pretty-print-body | Whether to pretty print the message bodies. |
> |spring.cloud.azure.client.http.maximum-connection-pool-size | Maximum connection pool size used by the underlying HTTP client. |
> |spring.cloud.azure.client.http.read-timeout | Amount of time used when reading the server response. |
> |spring.cloud.azure.client.http.response-timeout | Amount of time used when waiting for a server to reply. |
> |spring.cloud.azure.client.http.write-timeout | Amount of time each request being sent over the wire. |
> |spring.cloud.azure.compatibility-verifier.compatible-boot-versions | Comma-delimited list of Spring Boot versions that are compatible with current Spring Cloud Azure's version. |
> |spring.cloud.azure.compatibility-verifier.enabled | Whether to enable the Spring Cloud Azure compatibility verifier. The default value is `true`. |
> |spring.cloud.azure.cosmos.client-telemetry-enabled | Whether to enable client telemetry which will periodically collect database operations aggregation statistics, system information like cpu/memory and send it to Cosmos DB monitoring service, which will be helpful during debugging. |
> |spring.cloud.azure.cosmos.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.cosmos.connection-mode | Connection mode to be used by the client in the Azure Cosmos DB database service. |
> |spring.cloud.azure.cosmos.connection-sharing-across-clients-enabled | Whether to enable connections sharing across multiple Cosmos DB Clients. |
> |spring.cloud.azure.cosmos.consistency-level | Consistency level. The requested ConsistencyLevel must match or be weaker than that provisioned for the database account. |
> |spring.cloud.azure.cosmos.content-response-on-write-enabled | Whether to only return the headers and status code in Cosmos DB response in case of Create, Update and Delete operations on CosmosItem.  If set to false, service doesn't return payload in the response. |
> |spring.cloud.azure.cosmos.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.cosmos.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.cosmos.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.cosmos.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.cosmos.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.cosmos.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.cosmos.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.cosmos.database | Database name of the Cosmos DB. |
> |spring.cloud.azure.cosmos.direct-connection.connect-timeout | Connect timeout for direct client, represents timeout for establishing connections with an endpoint. |
> |spring.cloud.azure.cosmos.direct-connection.connection-endpoint-rediscovery-enabled | Whether to enable the direct TCP connection endpoint rediscovery. |
> |spring.cloud.azure.cosmos.direct-connection.idle-connection-timeout | Idle connection timeout for the direct client. Direct client doesn't close a single connection to an endpoint by default unless specified. |
> |spring.cloud.azure.cosmos.direct-connection.idle-endpoint-timeout | Idle endpoint timeout for the direct client. If there are no requests to a specific endpoint for idle endpoint timeout duration, direct client closes all connections to that endpoint to save resources and I/O cost. |
> |spring.cloud.azure.cosmos.direct-connection.max-connections-per-endpoint | Max connections per endpoint, represents the size of connection pool for a specific endpoint. |
> |spring.cloud.azure.cosmos.direct-connection.max-requests-per-connection | Max requests per connection, represents the number of requests that will be queued on a single connection for a specific endpoint. |
> |spring.cloud.azure.cosmos.direct-connection.network-request-timeout | Network request timeout interval (time to wait for response from network peer). |
> |spring.cloud.azure.cosmos.enabled | Whether an Azure Service is enabled. The default value is `true`. |
> |spring.cloud.azure.cosmos.endpoint | Endpoint of the Cosmos DB. |
> |spring.cloud.azure.cosmos.endpoint-discovery-enabled | Whether to enable endpoint discovery for geo-replicated database accounts. |
> |spring.cloud.azure.cosmos.gateway-connection.idle-connection-timeout | Timeout for an idle connection. After that time, the connection will be automatically closed. |
> |spring.cloud.azure.cosmos.gateway-connection.max-connection-pool-size | Size of the connection pool. |
> |spring.cloud.azure.cosmos.key | Key to authenticate for accessing the Cosmos DB. |
> |spring.cloud.azure.cosmos.multiple-write-regions-enabled | Whether to enable writes on any regions for geo-replicated database accounts in the Azure Cosmos DB service. |
> |spring.cloud.azure.cosmos.populate-query-metrics | Whether to populate diagnostics strings and query metrics. The default value is `false`. |
> |spring.cloud.azure.cosmos.preferred-regions | Preferred regions for geo-replicated database accounts. For example, "East US" as the preferred region. |
> |spring.cloud.azure.cosmos.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.cosmos.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.cosmos.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.cosmos.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.cosmos.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.cosmos.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.cosmos.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.cosmos.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.cosmos.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.cosmos.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.cosmos.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.cosmos.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.cosmos.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.cosmos.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.cosmos.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.cosmos.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.cosmos.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.cosmos.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.cosmos.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.cosmos.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.cosmos.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.cosmos.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.cosmos.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.cosmos.proxy.non-proxy-hosts | A list of hosts or CIDR to not use proxy HTTP/HTTPS connections through. |
> |spring.cloud.azure.cosmos.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.cosmos.proxy.port | The port of the proxy. |
> |spring.cloud.azure.cosmos.proxy.type | Type of the proxy. |
> |spring.cloud.azure.cosmos.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.cosmos.read-requests-fallback-enabled | Whether to allow for reads to go to multiple regions configured on an account of Azure Cosmos DB service. |
> |spring.cloud.azure.cosmos.resource-token | Resource token to authenticate for accessing the Cosmos DB. |
> |spring.cloud.azure.cosmos.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.cosmos.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.cosmos.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.cosmos.session-capturing-override-enabled | Whether to enable session capturing. Session capturing is enabled by default for SESSION consistency level. |
> |spring.cloud.azure.cosmos.throttling-retry-options.max-retry-attempts-on-throttled-requests | Maximum number of retries in the case where the request fails because the service has applied rate limiting on the client. |
> |spring.cloud.azure.cosmos.throttling-retry-options.max-retry-wait-time | Maximum retry time in seconds. When a request fails due to a throttle error, the service sends back a response that contains a value indicating the client should not retry before the time period has elapsed (Retry-After). The MaxRetryWaitTime flag allows the application to set a maximum wait time for all retry attempts. If the cumulative wait time exceeds the MaxRetryWaitTime, the SDK will stop retrying and return the error to the application. |
> |spring.cloud.azure.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.environment | The Azure environment, such as global Azure or Azure China. This is a legacy property. |
> |spring.cloud.azure.eventhub.checkpoint-access-key | Storage account access key. This is a legacy property. |
> |spring.cloud.azure.eventhub.checkpoint-container | Name of the container. This is a legacy property. |
> |spring.cloud.azure.eventhub.checkpoint-storage-account | Name for the storage account. This is a legacy property. |
> |spring.cloud.azure.eventhub.connection-string | Connection string to connect to an event hub. This is a legacy property. |
> |spring.cloud.azure.eventhub.namespace | The namespace of an event hub. This is a legacy property. |
> |spring.cloud.azure.eventhubs.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.eventhubs.client.transport-type | Transport type for AMQP-based client. |
> |spring.cloud.azure.eventhubs.connection-string | Connection string to connect to an event hub. |
> |spring.cloud.azure.eventhubs.consumer.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.eventhubs.consumer.client.transport-type | Transport type for AMQP-based client. |
> |spring.cloud.azure.eventhubs.consumer.connection-string | Connection string to connect to an event hub. |
> |spring.cloud.azure.eventhubs.consumer.consumer-group | Name of the consumer group this consumer is associated with. |
> |spring.cloud.azure.eventhubs.consumer.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.eventhubs.consumer.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.eventhubs.consumer.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.eventhubs.consumer.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.eventhubs.consumer.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.eventhubs.consumer.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.eventhubs.consumer.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.eventhubs.consumer.custom-endpoint-address | A custom endpoint address when connecting to the Event Hubs service. This can be useful when your network does not allow connecting to the standard Azure Event Hubs endpoint address, but does allow connecting through an intermediary. For example: https://my.custom.endpoint.com:55300. |
> |spring.cloud.azure.eventhubs.consumer.domain-name | The domain name of an Event Hub namespace. The default value is `servicebus.windows.net`. |
> |spring.cloud.azure.eventhubs.consumer.enabled | Whether an Azure Service is enabled. The default value is `true`. |
> |spring.cloud.azure.eventhubs.consumer.event-hub-name | The name of an event hub. |
> |spring.cloud.azure.eventhubs.consumer.namespace | The namespace of an event hub, which is the prefix of the FQDN. A FQDN should be composed of &lt;NamespaceName&gt;.&lt;DomainName&gt; |
> |spring.cloud.azure.eventhubs.consumer.prefetch-count | The number of events the Event Hub consumer will actively receive and queue locally without regard to whether a receiving operation is currently active. |
> |spring.cloud.azure.eventhubs.consumer.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.eventhubs.consumer.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.eventhubs.consumer.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.eventhubs.consumer.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.eventhubs.consumer.proxy.authentication-type | Authentication type used against the proxy. |
> |spring.cloud.azure.eventhubs.consumer.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.eventhubs.consumer.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.eventhubs.consumer.proxy.port | The port of the proxy. |
> |spring.cloud.azure.eventhubs.consumer.proxy.type | Type of the proxy. |
> |spring.cloud.azure.eventhubs.consumer.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.eventhubs.consumer.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.eventhubs.consumer.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.eventhubs.consumer.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.eventhubs.consumer.retry.exponential.base-delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.eventhubs.consumer.retry.exponential.max-delay | Maximum permissible amount of time between retry attempts. |
> |spring.cloud.azure.eventhubs.consumer.retry.exponential.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.eventhubs.consumer.retry.fixed.delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.eventhubs.consumer.retry.fixed.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.eventhubs.consumer.retry.mode | Retry backoff mode. |
> |spring.cloud.azure.eventhubs.consumer.retry.try-timeout | Amount of time to wait until a timeout. |
> |spring.cloud.azure.eventhubs.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.eventhubs.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.eventhubs.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.eventhubs.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.eventhubs.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.eventhubs.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.eventhubs.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.eventhubs.custom-endpoint-address | A custom endpoint address when connecting to the Event Hubs service. This can be useful when your network does not allow connecting to the standard Azure Event Hubs endpoint address, but does allow connecting through an intermediary. For example: https://my.custom.endpoint.com:55300. |
> |spring.cloud.azure.eventhubs.domain-name | The domain name of an Event Hub namespace. The default value is `servicebus.windows.net`. |
> |spring.cloud.azure.eventhubs.enabled | Whether an Azure Service is enabled. The default value is `true`. |
> |spring.cloud.azure.eventhubs.event-hub-name | The name of an event hub. |
> |spring.cloud.azure.eventhubs.namespace | The namespace of an event hub, which is the prefix of the FQDN. A FQDN should be composed of &lt;NamespaceName&gt;.&lt;DomainName&gt; |
> |spring.cloud.azure.eventhubs.processor.batch.max-size | The maximum number of events that will be in the batch. |
> |spring.cloud.azure.eventhubs.processor.batch.max-wait-time | The max time duration to wait to receive an event before processing events. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.account-key | Storage account access key. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.account-name | Name for the storage account. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.blob-name | Name of the blob. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.client.connect-timeout | Amount of time the request attempts to connect to the remote host and the connection is resolved. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.client.connection-idle-timeout | Amount of time before an idle connection. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.client.headers | Comma-delimited list of headers applied to each request sent with client. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.client.logging.allowed-header-names | Comma-delimited list of allowedlist headers that should be logged. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.client.logging.allowed-query-param-names | Comma-delimited list of allowedlist query parameters. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.client.logging.level | The level of detail to log on HTTP messages. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.client.logging.pretty-print-body | Whether to pretty print the message bodies. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.client.maximum-connection-pool-size | Maximum connection pool size used by the underlying HTTP client. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.client.read-timeout | Amount of time used when reading the server response. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.client.response-timeout | Amount of time used when waiting for a server to reply. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.client.write-timeout | Amount of time each request being sent over the wire. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.connection-string | Connection string to connect to the service. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.container-name | Name of the container. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.create-container-if-not-exists | Whether to create the container if it does not exist. The default value is `false`. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.customer-provided-key | Customer provided key used to encrypt blob contents on the server. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.enabled | Whether an Azure Service is enabled. The default value is `true`. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.encryption-scope | Encryption scope used to encrypt blob contents on the server. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.endpoint | Endpoint for Azure Storage service. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.proxy.non-proxy-hosts | A list of hosts or CIDR to not use proxy HTTP/HTTPS connections through. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.proxy.port | The port of the proxy. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.proxy.type | Type of the proxy. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.retry.exponential.base-delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.retry.exponential.max-delay | Maximum permissible amount of time between retry attempts. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.retry.exponential.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.retry.fixed.delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.retry.fixed.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.retry.mode | Retry backoff mode. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.retry.secondary-host | Secondary Storage account to retry requests against. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.retry.try-timeout | Amount of time to wait until a timeout. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.sas-token | Shared access signatures (SAS) token used to authorize requests sent to the service. |
> |spring.cloud.azure.eventhubs.processor.checkpoint-store.service-version | Blob service version used when making API requests. |
> |spring.cloud.azure.eventhubs.processor.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.eventhubs.processor.client.transport-type | Transport type for AMQP-based client. |
> |spring.cloud.azure.eventhubs.processor.connection-string | Connection string to connect to an event hub. |
> |spring.cloud.azure.eventhubs.processor.consumer-group | Name of the consumer group this consumer is associated with. |
> |spring.cloud.azure.eventhubs.processor.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.eventhubs.processor.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.eventhubs.processor.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.eventhubs.processor.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.eventhubs.processor.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.eventhubs.processor.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.eventhubs.processor.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.eventhubs.processor.custom-endpoint-address | A custom endpoint address when connecting to the Event Hubs service. This can be useful when your network does not allow connecting to the standard Azure Event Hubs endpoint address, but does allow connecting through an intermediary. For example: https://my.custom.endpoint.com:55300. |
> |spring.cloud.azure.eventhubs.processor.domain-name | The domain name of an Event Hub namespace. The default value is `servicebus.windows.net`. |
> |spring.cloud.azure.eventhubs.processor.enabled | Whether an Azure Service is enabled. The default value is `true`. |
> |spring.cloud.azure.eventhubs.processor.event-hub-name | The name of an event hub. |
> |spring.cloud.azure.eventhubs.processor.initial-partition-event-position | Map event position to use for each partition if a checkpoint for the partition does not exist in CheckpointStore. |
> |spring.cloud.azure.eventhubs.processor.load-balancing.partition-ownership-expiration-interval | The time duration after which the ownership of partition expires. |
> |spring.cloud.azure.eventhubs.processor.load-balancing.strategy | The load balancing strategy for claiming partition ownership. |
> |spring.cloud.azure.eventhubs.processor.load-balancing.update-interval | The time interval between load balancing update cycles. |
> |spring.cloud.azure.eventhubs.processor.namespace | The namespace of an event hub, which is the prefix of the FQDN. A FQDN should be composed of &lt;NamespaceName&gt;.&lt;DomainName&gt; |
> |spring.cloud.azure.eventhubs.processor.prefetch-count | The number of events the Event Hub consumer will actively receive and queue locally without regard to whether a receiving operation is currently active. |
> |spring.cloud.azure.eventhubs.processor.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.eventhubs.processor.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.eventhubs.processor.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.eventhubs.processor.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.eventhubs.processor.proxy.authentication-type | Authentication type used against the proxy. |
> |spring.cloud.azure.eventhubs.processor.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.eventhubs.processor.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.eventhubs.processor.proxy.port | The port of the proxy. |
> |spring.cloud.azure.eventhubs.processor.proxy.type | Type of the proxy. |
> |spring.cloud.azure.eventhubs.processor.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.eventhubs.processor.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.eventhubs.processor.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.eventhubs.processor.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.eventhubs.processor.retry.exponential.base-delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.eventhubs.processor.retry.exponential.max-delay | Maximum permissible amount of time between retry attempts. |
> |spring.cloud.azure.eventhubs.processor.retry.exponential.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.eventhubs.processor.retry.fixed.delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.eventhubs.processor.retry.fixed.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.eventhubs.processor.retry.mode | Retry backoff mode. |
> |spring.cloud.azure.eventhubs.processor.retry.try-timeout | Amount of time to wait until a timeout. |
> |spring.cloud.azure.eventhubs.processor.track-last-enqueued-event-properties | Whether request information on the last enqueued event on its associated partition, and track that information as events are received. |
> |spring.cloud.azure.eventhubs.producer.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.eventhubs.producer.client.transport-type | Transport type for AMQP-based client. |
> |spring.cloud.azure.eventhubs.producer.connection-string | Connection string to connect to an event hub. |
> |spring.cloud.azure.eventhubs.producer.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.eventhubs.producer.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.eventhubs.producer.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.eventhubs.producer.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.eventhubs.producer.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.eventhubs.producer.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.eventhubs.producer.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.eventhubs.producer.custom-endpoint-address | A custom endpoint address when connecting to the Event Hubs service. This can be useful when your network does not allow connecting to the standard Azure Event Hubs endpoint address, but does allow connecting through an intermediary. For example: https://my.custom.endpoint.com:55300. |
> |spring.cloud.azure.eventhubs.producer.domain-name | The domain name of an Event Hub namespace. The default value is `servicebus.windows.net`. |
> |spring.cloud.azure.eventhubs.producer.enabled | Whether an Azure Service is enabled. The default value is `true`. |
> |spring.cloud.azure.eventhubs.producer.event-hub-name | The name of an event hub. |
> |spring.cloud.azure.eventhubs.producer.namespace | The namespace of an event hub, which is the prefix of the FQDN. A FQDN should be composed of &lt;NamespaceName&gt;.&lt;DomainName&gt; |
> |spring.cloud.azure.eventhubs.producer.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.eventhubs.producer.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.eventhubs.producer.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.eventhubs.producer.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.eventhubs.producer.proxy.authentication-type | Authentication type used against the proxy. |
> |spring.cloud.azure.eventhubs.producer.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.eventhubs.producer.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.eventhubs.producer.proxy.port | The port of the proxy. |
> |spring.cloud.azure.eventhubs.producer.proxy.type | Type of the proxy. |
> |spring.cloud.azure.eventhubs.producer.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.eventhubs.producer.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.eventhubs.producer.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.eventhubs.producer.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.eventhubs.producer.retry.exponential.base-delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.eventhubs.producer.retry.exponential.max-delay | Maximum permissible amount of time between retry attempts. |
> |spring.cloud.azure.eventhubs.producer.retry.exponential.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.eventhubs.producer.retry.fixed.delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.eventhubs.producer.retry.fixed.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.eventhubs.producer.retry.mode | Retry backoff mode. |
> |spring.cloud.azure.eventhubs.producer.retry.try-timeout | Amount of time to wait until a timeout. |
> |spring.cloud.azure.eventhubs.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.eventhubs.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.eventhubs.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.eventhubs.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.eventhubs.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.eventhubs.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.eventhubs.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.eventhubs.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.eventhubs.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.eventhubs.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.eventhubs.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.eventhubs.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.eventhubs.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.eventhubs.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.eventhubs.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.eventhubs.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.eventhubs.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.eventhubs.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.eventhubs.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.eventhubs.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.eventhubs.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.eventhubs.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.eventhubs.proxy.authentication-type | Authentication type used against the proxy. |
> |spring.cloud.azure.eventhubs.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.eventhubs.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.eventhubs.proxy.port | The port of the proxy. |
> |spring.cloud.azure.eventhubs.proxy.type | Type of the proxy. |
> |spring.cloud.azure.eventhubs.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.eventhubs.resource.name | Namespace of the event hub. |
> |spring.cloud.azure.eventhubs.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.eventhubs.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.eventhubs.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.eventhubs.retry.exponential.base-delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.eventhubs.retry.exponential.max-delay | Maximum permissible amount of time between retry attempts. |
> |spring.cloud.azure.eventhubs.retry.exponential.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.eventhubs.retry.fixed.delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.eventhubs.retry.fixed.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.eventhubs.retry.mode | Retry backoff mode. |
> |spring.cloud.azure.eventhubs.retry.try-timeout | Amount of time to wait until a timeout. |
> |spring.cloud.azure.eventhubs.shared-connection | Whether to share the same connection for producers or consumers. |
> |spring.cloud.azure.keyvault.certificate.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.keyvault.certificate.client.connect-timeout | Amount of time the request attempts to connect to the remote host and the connection is resolved. |
> |spring.cloud.azure.keyvault.certificate.client.connection-idle-timeout | Amount of time before an idle connection. |
> |spring.cloud.azure.keyvault.certificate.client.headers | Comma-delimited list of headers applied to each request sent with client. |
> |spring.cloud.azure.keyvault.certificate.client.logging.allowed-header-names | Comma-delimited list of allowedlist headers that should be logged. |
> |spring.cloud.azure.keyvault.certificate.client.logging.allowed-query-param-names | Comma-delimited list of allowedlist query parameters. |
> |spring.cloud.azure.keyvault.certificate.client.logging.level | The level of detail to log on HTTP messages. |
> |spring.cloud.azure.keyvault.certificate.client.logging.pretty-print-body | Whether to pretty print the message bodies. |
> |spring.cloud.azure.keyvault.certificate.client.maximum-connection-pool-size | Maximum connection pool size used by the underlying HTTP client. |
> |spring.cloud.azure.keyvault.certificate.client.read-timeout | Amount of time used when reading the server response. |
> |spring.cloud.azure.keyvault.certificate.client.response-timeout | Amount of time used when waiting for a server to reply. |
> |spring.cloud.azure.keyvault.certificate.client.write-timeout | Amount of time each request being sent over the wire. |
> |spring.cloud.azure.keyvault.certificate.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.keyvault.certificate.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.keyvault.certificate.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.keyvault.certificate.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.keyvault.certificate.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.keyvault.certificate.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.keyvault.certificate.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.keyvault.certificate.enabled | Whether an Azure Service is enabled. The default value is `true`. |
> |spring.cloud.azure.keyvault.certificate.endpoint | Azure Key Vault endpoint. |
> |spring.cloud.azure.keyvault.certificate.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.keyvault.certificate.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.keyvault.certificate.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.keyvault.certificate.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.keyvault.certificate.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.keyvault.certificate.proxy.non-proxy-hosts | A list of hosts or CIDR to not use proxy HTTP/HTTPS connections through. |
> |spring.cloud.azure.keyvault.certificate.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.keyvault.certificate.proxy.port | The port of the proxy. |
> |spring.cloud.azure.keyvault.certificate.proxy.type | Type of the proxy. |
> |spring.cloud.azure.keyvault.certificate.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.keyvault.certificate.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.keyvault.certificate.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.keyvault.certificate.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.keyvault.certificate.retry.exponential.base-delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.keyvault.certificate.retry.exponential.max-delay | Maximum permissible amount of time between retry attempts. |
> |spring.cloud.azure.keyvault.certificate.retry.exponential.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.keyvault.certificate.retry.fixed.delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.keyvault.certificate.retry.fixed.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.keyvault.certificate.retry.mode | Retry backoff mode. |
> |spring.cloud.azure.keyvault.certificate.service-version | The version of Azure Key Vault Certificate Service. |
> |spring.cloud.azure.keyvault.secret.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.keyvault.secret.client.connect-timeout | Amount of time the request attempts to connect to the remote host and the connection is resolved. |
> |spring.cloud.azure.keyvault.secret.client.connection-idle-timeout | Amount of time before an idle connection. |
> |spring.cloud.azure.keyvault.secret.client.headers | Comma-delimited list of headers applied to each request sent with client. |
> |spring.cloud.azure.keyvault.secret.client.logging.allowed-header-names | Comma-delimited list of allowedlist headers that should be logged. |
> |spring.cloud.azure.keyvault.secret.client.logging.allowed-query-param-names | Comma-delimited list of allowedlist query parameters. |
> |spring.cloud.azure.keyvault.secret.client.logging.level | The level of detail to log on HTTP messages. |
> |spring.cloud.azure.keyvault.secret.client.logging.pretty-print-body | Whether to pretty print the message bodies. |
> |spring.cloud.azure.keyvault.secret.client.maximum-connection-pool-size | Maximum connection pool size used by the underlying HTTP client. |
> |spring.cloud.azure.keyvault.secret.client.read-timeout | Amount of time used when reading the server response. |
> |spring.cloud.azure.keyvault.secret.client.response-timeout | Amount of time used when waiting for a server to reply. |
> |spring.cloud.azure.keyvault.secret.client.write-timeout | Amount of time each request being sent over the wire. |
> |spring.cloud.azure.keyvault.secret.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.keyvault.secret.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.keyvault.secret.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.keyvault.secret.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.keyvault.secret.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.keyvault.secret.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.keyvault.secret.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.keyvault.secret.enabled | Whether an Azure Service is enabled. The default value is `true`. |
> |spring.cloud.azure.keyvault.secret.endpoint | Azure Key Vault endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.keyvault.secret.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.keyvault.secret.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.keyvault.secret.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.keyvault.secret.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.keyvault.secret.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.keyvault.secret.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.keyvault.secret.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.keyvault.secret.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.keyvault.secret.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.keyvault.secret.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.keyvault.secret.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.keyvault.secret.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.keyvault.secret.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.keyvault.secret.property-source-enabled | Whether to enable the Key Vault property source. The default value is `true`. |
> |spring.cloud.azure.keyvault.secret.property-sources | Azure Key Vault property sources. |
> |spring.cloud.azure.keyvault.secret.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.keyvault.secret.proxy.non-proxy-hosts | A list of hosts or CIDR to not use proxy HTTP/HTTPS connections through. |
> |spring.cloud.azure.keyvault.secret.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.keyvault.secret.proxy.port | The port of the proxy. |
> |spring.cloud.azure.keyvault.secret.proxy.type | Type of the proxy. |
> |spring.cloud.azure.keyvault.secret.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.keyvault.secret.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.keyvault.secret.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.keyvault.secret.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.keyvault.secret.retry.exponential.base-delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.keyvault.secret.retry.exponential.max-delay | Maximum permissible amount of time between retry attempts. |
> |spring.cloud.azure.keyvault.secret.retry.exponential.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.keyvault.secret.retry.fixed.delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.keyvault.secret.retry.fixed.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.keyvault.secret.retry.mode | Retry backoff mode. |
> |spring.cloud.azure.keyvault.secret.service-version | Secret service version used when making API requests. |
> |spring.cloud.azure.msi-enabled | Whether managed identity is enabled. This is a legacy property. The default value is `false`. |
> |spring.cloud.azure.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.proxy.amqp.authentication-type | Authentication type used against the proxy. |
> |spring.cloud.azure.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.proxy.http.non-proxy-hosts | A list of hosts or CIDR to not use proxy HTTP/HTTPS connections through. |
> |spring.cloud.azure.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.proxy.port | The port of the proxy. |
> |spring.cloud.azure.proxy.type | Type of the proxy. |
> |spring.cloud.azure.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.redis.name | Name of the Azure Cache for Redis. |
> |spring.cloud.azure.redis.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.redis.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.redis.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.region | The region of an Azure resource. This is a legacy property. |
> |spring.cloud.azure.resource-group | The resource group holds an Azure resource. This is a legacy property. |
> |spring.cloud.azure.retry.amqp.try-timeout | How long to wait until a timeout. |
> |spring.cloud.azure.retry.exponential.base-delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.retry.exponential.max-delay | Maximum permissible amount of time between retry attempts. |
> |spring.cloud.azure.retry.exponential.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.retry.fixed.delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.retry.fixed.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.retry.mode | Retry backoff mode. |
> |spring.cloud.azure.servicebus.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.servicebus.client.transport-type | Transport type for AMQP-based client. |
> |spring.cloud.azure.servicebus.connection-string | Connection string to connect to a service bus. |
> |spring.cloud.azure.servicebus.consumer.auto-complete | Whether to enable auto-complete. The default value is `true`. |
> |spring.cloud.azure.servicebus.consumer.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.servicebus.consumer.client.transport-type | Transport type for AMQP-based client. |
> |spring.cloud.azure.servicebus.consumer.connection-string | Connection string to connect to a service bus. |
> |spring.cloud.azure.servicebus.consumer.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.servicebus.consumer.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.servicebus.consumer.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.servicebus.consumer.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.servicebus.consumer.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.servicebus.consumer.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.servicebus.consumer.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.servicebus.consumer.domain-name | The domain name of a Service Bus namespace. The default value is `servicebus.windows.net`. |
> |spring.cloud.azure.servicebus.consumer.enabled | Whether an Azure Service is enabled. The default value is `true`. |
> |spring.cloud.azure.servicebus.consumer.entity-name | The name of a Service Bus Queue or Topic. |
> |spring.cloud.azure.servicebus.consumer.entity-type | The type of Service Bus entity, which is a Queue or a Topic. |
> |spring.cloud.azure.servicebus.consumer.max-auto-lock-renew-duration | Amount of time to continue auto-renewing the lock. |
> |spring.cloud.azure.servicebus.consumer.namespace | The namespace of a service bus, which is the prefix of the FQDN. A FQDN should be composed of &lt;NamespaceName&gt;.&lt;DomainName&gt; |
> |spring.cloud.azure.servicebus.consumer.prefetch-count | Prefetch count of the consumer. |
> |spring.cloud.azure.servicebus.consumer.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.servicebus.consumer.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.servicebus.consumer.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.servicebus.consumer.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.servicebus.consumer.proxy.authentication-type | Authentication type used against the proxy. |
> |spring.cloud.azure.servicebus.consumer.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.servicebus.consumer.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.servicebus.consumer.proxy.port | The port of the proxy. |
> |spring.cloud.azure.servicebus.consumer.proxy.type | Type of the proxy. |
> |spring.cloud.azure.servicebus.consumer.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.servicebus.consumer.receive-mode | Mode for receiving messages. |
> |spring.cloud.azure.servicebus.consumer.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.servicebus.consumer.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.servicebus.consumer.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.servicebus.consumer.retry.exponential.base-delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.servicebus.consumer.retry.exponential.max-delay | Maximum permissible amount of time between retry attempts. |
> |spring.cloud.azure.servicebus.consumer.retry.exponential.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.servicebus.consumer.retry.fixed.delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.servicebus.consumer.retry.fixed.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.servicebus.consumer.retry.mode | Retry backoff mode. |
> |spring.cloud.azure.servicebus.consumer.retry.try-timeout | Amount of time to wait until a timeout. |
> |spring.cloud.azure.servicebus.consumer.session-enabled | Whether to enable session for the consumer. |
> |spring.cloud.azure.servicebus.consumer.sub-queue | Type of the SubQueue to connect to. |
> |spring.cloud.azure.servicebus.consumer.subscription-name | Name for a topic subscription. |
> |spring.cloud.azure.servicebus.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.servicebus.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.servicebus.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.servicebus.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.servicebus.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.servicebus.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.servicebus.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.servicebus.cross-entity-transactions | Whether to enable cross entity transaction on the connection to Service bus. |
> |spring.cloud.azure.servicebus.domain-name | The domain name of a Service Bus namespace. The default value is `servicebus.windows.net`. |
> |spring.cloud.azure.servicebus.enabled | Whether an Azure Service is enabled. The default value is `true`. |
> |spring.cloud.azure.servicebus.entity-name | The name of a Service Bus Queue or Topic. |
> |spring.cloud.azure.servicebus.entity-type | The type of Service Bus entity, which is a Queue or a Topic. |
> |spring.cloud.azure.servicebus.namespace | The namespace of a service bus, which is the prefix of the FQDN. A FQDN should be composed of &lt;NamespaceName&gt;.&lt;DomainName&gt; |
> |spring.cloud.azure.servicebus.processor.auto-complete | Whether to enable auto-complete. The default value is `true`. |
> |spring.cloud.azure.servicebus.processor.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.servicebus.processor.client.transport-type | Transport type for AMQP-based client. |
> |spring.cloud.azure.servicebus.processor.connection-string | Connection string to connect to a service bus. |
> |spring.cloud.azure.servicebus.processor.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.servicebus.processor.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.servicebus.processor.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.servicebus.processor.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.servicebus.processor.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.servicebus.processor.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.servicebus.processor.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.servicebus.processor.domain-name | The domain name of a Service Bus namespace. The default value is `servicebus.windows.net`. |
> |spring.cloud.azure.servicebus.processor.enabled | Whether an Azure Service is enabled. The default value is `true`. |
> |spring.cloud.azure.servicebus.processor.entity-name | The name of a Service Bus Queue or Topic. |
> |spring.cloud.azure.servicebus.processor.entity-type | The type of Service Bus entity, which is a Queue or a Topic. |
> |spring.cloud.azure.servicebus.processor.max-auto-lock-renew-duration | Amount of time to continue auto-renewing the lock. |
> |spring.cloud.azure.servicebus.processor.max-concurrent-calls | Max concurrent messages to process. |
> |spring.cloud.azure.servicebus.processor.max-concurrent-sessions | Maximum number of concurrent sessions to process at any given time. |
> |spring.cloud.azure.servicebus.processor.namespace | The namespace of a service bus, which is the prefix of the FQDN. A FQDN should be composed of &lt;NamespaceName&gt;.&lt;DomainName&gt; |
> |spring.cloud.azure.servicebus.processor.prefetch-count | Prefetch count of the consumer. |
> |spring.cloud.azure.servicebus.processor.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.servicebus.processor.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.servicebus.processor.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.servicebus.processor.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.servicebus.processor.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.servicebus.processor.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.servicebus.processor.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.servicebus.processor.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.servicebus.processor.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.servicebus.processor.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.servicebus.processor.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.servicebus.processor.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.servicebus.processor.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.servicebus.processor.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.servicebus.processor.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.servicebus.processor.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.servicebus.processor.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.servicebus.processor.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.servicebus.processor.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.servicebus.processor.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.servicebus.processor.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.servicebus.processor.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.servicebus.processor.proxy.authentication-type | Authentication type used against the proxy. |
> |spring.cloud.azure.servicebus.processor.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.servicebus.processor.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.servicebus.processor.proxy.port | The port of the proxy. |
> |spring.cloud.azure.servicebus.processor.proxy.type | Type of the proxy. |
> |spring.cloud.azure.servicebus.processor.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.servicebus.processor.receive-mode | Mode for receiving messages. |
> |spring.cloud.azure.servicebus.processor.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.servicebus.processor.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.servicebus.processor.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.servicebus.processor.retry.exponential.base-delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.servicebus.processor.retry.exponential.max-delay | Maximum permissible amount of time between retry attempts. |
> |spring.cloud.azure.servicebus.processor.retry.exponential.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.servicebus.processor.retry.fixed.delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.servicebus.processor.retry.fixed.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.servicebus.processor.retry.mode | Retry backoff mode. |
> |spring.cloud.azure.servicebus.processor.retry.try-timeout | Amount of time to wait until a timeout. |
> |spring.cloud.azure.servicebus.processor.session-enabled | Whether to enable session for the consumer. |
> |spring.cloud.azure.servicebus.processor.sub-queue | Type of the SubQueue to connect to. |
> |spring.cloud.azure.servicebus.processor.subscription-name | Name for a topic subscription. |
> |spring.cloud.azure.servicebus.producer.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.servicebus.producer.client.transport-type | Transport type for AMQP-based client. |
> |spring.cloud.azure.servicebus.producer.connection-string | Connection string to connect to a service bus. |
> |spring.cloud.azure.servicebus.producer.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.servicebus.producer.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.servicebus.producer.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.servicebus.producer.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.servicebus.producer.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.servicebus.producer.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.servicebus.producer.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.servicebus.producer.domain-name | The domain name of a Service Bus namespace. The default value is `servicebus.windows.net`. |
> |spring.cloud.azure.servicebus.producer.enabled | Whether an Azure Service is enabled. The default value is `true`. |
> |spring.cloud.azure.servicebus.producer.entity-name | The name of a Service Bus Queue or Topic. |
> |spring.cloud.azure.servicebus.producer.entity-type | The type of Service Bus entity, which is a Queue or a Topic. |
> |spring.cloud.azure.servicebus.producer.namespace | The namespace of a service bus, which is the prefix of the FQDN. A FQDN should be composed of &lt;NamespaceName&gt;.&lt;DomainName&gt; |
> |spring.cloud.azure.servicebus.producer.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.servicebus.producer.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.servicebus.producer.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.servicebus.producer.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.servicebus.producer.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.servicebus.producer.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.servicebus.producer.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.servicebus.producer.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.servicebus.producer.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.servicebus.producer.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.servicebus.producer.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.servicebus.producer.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.servicebus.producer.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.servicebus.producer.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.servicebus.producer.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.servicebus.producer.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.servicebus.producer.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.servicebus.producer.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.servicebus.producer.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.servicebus.producer.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.servicebus.producer.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.servicebus.producer.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.servicebus.producer.proxy.authentication-type | Authentication type used against the proxy. |
> |spring.cloud.azure.servicebus.producer.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.servicebus.producer.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.servicebus.producer.proxy.port | The port of the proxy. |
> |spring.cloud.azure.servicebus.producer.proxy.type | Type of the proxy. |
> |spring.cloud.azure.servicebus.producer.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.servicebus.producer.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.servicebus.producer.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.servicebus.producer.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.servicebus.producer.retry.exponential.base-delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.servicebus.producer.retry.exponential.max-delay | Maximum permissible amount of time between retry attempts. |
> |spring.cloud.azure.servicebus.producer.retry.exponential.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.servicebus.producer.retry.fixed.delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.servicebus.producer.retry.fixed.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.servicebus.producer.retry.mode | Retry backoff mode. |
> |spring.cloud.azure.servicebus.producer.retry.try-timeout | Amount of time to wait until a timeout. |
> |spring.cloud.azure.servicebus.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.servicebus.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.servicebus.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.servicebus.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.servicebus.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.servicebus.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.servicebus.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.servicebus.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.servicebus.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.servicebus.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.servicebus.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.servicebus.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.servicebus.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.servicebus.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.servicebus.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.servicebus.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.servicebus.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.servicebus.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.servicebus.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.servicebus.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.servicebus.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.servicebus.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.servicebus.proxy.authentication-type | Authentication type used against the proxy. |
> |spring.cloud.azure.servicebus.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.servicebus.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.servicebus.proxy.port | The port of the proxy. |
> |spring.cloud.azure.servicebus.proxy.type | Type of the proxy. |
> |spring.cloud.azure.servicebus.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.servicebus.resource.name | Namespace of the service bus. |
> |spring.cloud.azure.servicebus.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.servicebus.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.servicebus.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.servicebus.retry-options.delay | Amount of time to wait between retry attempts. This is a legacy property. |
> |spring.cloud.azure.servicebus.retry-options.maxDelay | Maximum permissible amount of time between retry attempts. This is a legacy property. |
> |spring.cloud.azure.servicebus.retry-options.maxRetries | The maximum number of attempts. This is a legacy property. |
> |spring.cloud.azure.servicebus.retry-options.retryMode | The type of approach to apply when calculating the delay between retry attempts. This is a legacy property. |
> |spring.cloud.azure.servicebus.retry-options.tryTimeout | Amount of time to wait until a timeout. This is a legacy property. |
> |spring.cloud.azure.servicebus.retry.exponential.base-delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.servicebus.retry.exponential.max-delay | Maximum permissible amount of time between retry attempts. |
> |spring.cloud.azure.servicebus.retry.exponential.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.servicebus.retry.fixed.delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.servicebus.retry.fixed.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.servicebus.retry.mode | Retry backoff mode. |
> |spring.cloud.azure.servicebus.retry.try-timeout | Amount of time to wait until a timeout. |
> |spring.cloud.azure.servicebus.transport-type | Transport type for AMQP-based client. This is a legacy property. |
> |spring.cloud.azure.storage.access-key | Storage account access key. This is a legacy property. |
> |spring.cloud.azure.storage.account | Name for the storage account. This is a legacy property. |
> |spring.cloud.azure.storage.blob.account-key | Storage account access key. |
> |spring.cloud.azure.storage.blob.account-name | Name for the storage account. |
> |spring.cloud.azure.storage.blob.blob-name | Name of the blob. |
> |spring.cloud.azure.storage.blob.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.storage.blob.client.connect-timeout | Amount of time the request attempts to connect to the remote host and the connection is resolved. |
> |spring.cloud.azure.storage.blob.client.connection-idle-timeout | Amount of time before an idle connection. |
> |spring.cloud.azure.storage.blob.client.headers | Comma-delimited list of headers applied to each request sent with client. |
> |spring.cloud.azure.storage.blob.client.logging.allowed-header-names | Comma-delimited list of allowedlist headers that should be logged. |
> |spring.cloud.azure.storage.blob.client.logging.allowed-query-param-names | Comma-delimited list of allowedlist query parameters. |
> |spring.cloud.azure.storage.blob.client.logging.level | The level of detail to log on HTTP messages. |
> |spring.cloud.azure.storage.blob.client.logging.pretty-print-body | Whether to pretty print the message bodies. |
> |spring.cloud.azure.storage.blob.client.maximum-connection-pool-size | Maximum connection pool size used by the underlying HTTP client. |
> |spring.cloud.azure.storage.blob.client.read-timeout | Amount of time used when reading the server response. |
> |spring.cloud.azure.storage.blob.client.response-timeout | Amount of time used when waiting for a server to reply. |
> |spring.cloud.azure.storage.blob.client.write-timeout | Amount of time each request being sent over the wire. |
> |spring.cloud.azure.storage.blob.connection-string | Connection string to connect to the service. |
> |spring.cloud.azure.storage.blob.container-name | Name of the container. |
> |spring.cloud.azure.storage.blob.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.storage.blob.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.storage.blob.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.storage.blob.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.storage.blob.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.storage.blob.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.storage.blob.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.storage.blob.customer-provided-key | Customer provided key used to encrypt blob contents on the server. |
> |spring.cloud.azure.storage.blob.enabled | Whether an Azure Service is enabled. The default value is `true`. |
> |spring.cloud.azure.storage.blob.encryption-scope | Encryption scope used to encrypt blob contents on the server. |
> |spring.cloud.azure.storage.blob.endpoint | Endpoint for Azure Storage service. |
> |spring.cloud.azure.storage.blob.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.storage.blob.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.storage.blob.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.storage.blob.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.storage.blob.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.storage.blob.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.storage.blob.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.storage.blob.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.storage.blob.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.storage.blob.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.storage.blob.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.storage.blob.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.storage.blob.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.storage.blob.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.storage.blob.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.storage.blob.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.storage.blob.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.storage.blob.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.storage.blob.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.storage.blob.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.storage.blob.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.storage.blob.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.storage.blob.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.storage.blob.proxy.non-proxy-hosts | A list of hosts or CIDR to not use proxy HTTP/HTTPS connections through. |
> |spring.cloud.azure.storage.blob.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.storage.blob.proxy.port | The port of the proxy. |
> |spring.cloud.azure.storage.blob.proxy.type | Type of the proxy. |
> |spring.cloud.azure.storage.blob.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.storage.blob.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.storage.blob.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.storage.blob.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.storage.blob.retry.exponential.base-delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.storage.blob.retry.exponential.max-delay | Maximum permissible amount of time between retry attempts. |
> |spring.cloud.azure.storage.blob.retry.exponential.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.storage.blob.retry.fixed.delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.storage.blob.retry.fixed.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.storage.blob.retry.mode | Retry backoff mode. |
> |spring.cloud.azure.storage.blob.retry.secondary-host | Secondary Storage account to retry requests against. |
> |spring.cloud.azure.storage.blob.retry.try-timeout | Amount of time to wait until a timeout. |
> |spring.cloud.azure.storage.blob.sas-token | Shared access signatures (SAS) token used to authorize requests sent to the service. |
> |spring.cloud.azure.storage.blob.service-version | Blob service version used when making API requests. |
> |spring.cloud.azure.storage.fileshare.account-key | Storage account access key. |
> |spring.cloud.azure.storage.fileshare.account-name | Name for the storage account. |
> |spring.cloud.azure.storage.fileshare.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.storage.fileshare.client.connect-timeout | Amount of time the request attempts to connect to the remote host and the connection is resolved. |
> |spring.cloud.azure.storage.fileshare.client.connection-idle-timeout | Amount of time before an idle connection. |
> |spring.cloud.azure.storage.fileshare.client.headers | Comma-delimited list of headers applied to each request sent with client. |
> |spring.cloud.azure.storage.fileshare.client.logging.allowed-header-names | Comma-delimited list of allowedlist headers that should be logged. |
> |spring.cloud.azure.storage.fileshare.client.logging.allowed-query-param-names | Comma-delimited list of allowedlist query parameters. |
> |spring.cloud.azure.storage.fileshare.client.logging.level | The level of detail to log on HTTP messages. |
> |spring.cloud.azure.storage.fileshare.client.logging.pretty-print-body | Whether to pretty print the message bodies. |
> |spring.cloud.azure.storage.fileshare.client.maximum-connection-pool-size | Maximum connection pool size used by the underlying HTTP client. |
> |spring.cloud.azure.storage.fileshare.client.read-timeout | Amount of time used when reading the server response. |
> |spring.cloud.azure.storage.fileshare.client.response-timeout | Amount of time used when waiting for a server to reply. |
> |spring.cloud.azure.storage.fileshare.client.write-timeout | Amount of time each request being sent over the wire. |
> |spring.cloud.azure.storage.fileshare.connection-string | Connection string to connect to the service. |
> |spring.cloud.azure.storage.fileshare.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.storage.fileshare.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.storage.fileshare.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.storage.fileshare.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.storage.fileshare.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.storage.fileshare.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.storage.fileshare.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.storage.fileshare.directory-path | Path to the directory. For instance, 'directory1/directory2'. |
> |spring.cloud.azure.storage.fileshare.enabled | Whether an Azure Service is enabled. The default value is `true`. |
> |spring.cloud.azure.storage.fileshare.endpoint | Endpoint for Azure Storage service. |
> |spring.cloud.azure.storage.fileshare.file-path | Path to the file. For instance, 'directory1/file1'. |
> |spring.cloud.azure.storage.fileshare.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.storage.fileshare.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.storage.fileshare.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.storage.fileshare.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.storage.fileshare.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.storage.fileshare.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.storage.fileshare.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.storage.fileshare.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.storage.fileshare.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.storage.fileshare.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.storage.fileshare.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.storage.fileshare.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.storage.fileshare.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.storage.fileshare.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.storage.fileshare.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.storage.fileshare.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.storage.fileshare.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.storage.fileshare.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.storage.fileshare.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.storage.fileshare.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.storage.fileshare.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.storage.fileshare.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.storage.fileshare.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.storage.fileshare.proxy.non-proxy-hosts | A list of hosts or CIDR to not use proxy HTTP/HTTPS connections through. |
> |spring.cloud.azure.storage.fileshare.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.storage.fileshare.proxy.port | The port of the proxy. |
> |spring.cloud.azure.storage.fileshare.proxy.type | Type of the proxy. |
> |spring.cloud.azure.storage.fileshare.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.storage.fileshare.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.storage.fileshare.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.storage.fileshare.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.storage.fileshare.retry.exponential.base-delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.storage.fileshare.retry.exponential.max-delay | Maximum permissible amount of time between retry attempts. |
> |spring.cloud.azure.storage.fileshare.retry.exponential.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.storage.fileshare.retry.fixed.delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.storage.fileshare.retry.fixed.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.storage.fileshare.retry.mode | Retry backoff mode. |
> |spring.cloud.azure.storage.fileshare.retry.secondary-host | Secondary Storage account to retry requests against. |
> |spring.cloud.azure.storage.fileshare.retry.try-timeout | Amount of time to wait until a timeout. |
> |spring.cloud.azure.storage.fileshare.sas-token | Shared access signatures (SAS) token used to authorize requests sent to the service. |
> |spring.cloud.azure.storage.fileshare.service-version | Share service version used when making API requests |
> |spring.cloud.azure.storage.fileshare.share-name | Name of the share. |
> |spring.cloud.azure.storage.queue.account-key | Storage account access key. |
> |spring.cloud.azure.storage.queue.account-name | Name for the storage account. |
> |spring.cloud.azure.storage.queue.client.application-id | Represents current application and is used for telemetry/monitoring purposes. |
> |spring.cloud.azure.storage.queue.client.connect-timeout | Amount of time the request attempts to connect to the remote host and the connection is resolved. |
> |spring.cloud.azure.storage.queue.client.connection-idle-timeout | Amount of time before an idle connection. |
> |spring.cloud.azure.storage.queue.client.headers | Comma-delimited list of headers applied to each request sent with client. |
> |spring.cloud.azure.storage.queue.client.logging.allowed-header-names | Comma-delimited list of allowedlist headers that should be logged. |
> |spring.cloud.azure.storage.queue.client.logging.allowed-query-param-names | Comma-delimited list of allowedlist query parameters. |
> |spring.cloud.azure.storage.queue.client.logging.level | The level of detail to log on HTTP messages. |
> |spring.cloud.azure.storage.queue.client.logging.pretty-print-body | Whether to pretty print the message bodies. |
> |spring.cloud.azure.storage.queue.client.maximum-connection-pool-size | Maximum connection pool size used by the underlying HTTP client. |
> |spring.cloud.azure.storage.queue.client.read-timeout | Amount of time used when reading the server response. |
> |spring.cloud.azure.storage.queue.client.response-timeout | Amount of time used when waiting for a server to reply. |
> |spring.cloud.azure.storage.queue.client.write-timeout | Amount of time each request being sent over the wire. |
> |spring.cloud.azure.storage.queue.connection-string | Connection string to connect to the service. |
> |spring.cloud.azure.storage.queue.credential.client-certificate-password | Password of the certificate file. |
> |spring.cloud.azure.storage.queue.credential.client-certificate-path | Path of a PEM certificate file to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.storage.queue.credential.client-id | Client ID to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.storage.queue.credential.client-secret | Client secret to use when performing service principal authentication with Azure. |
> |spring.cloud.azure.storage.queue.credential.managed-identity-enabled | Whether to enable managed identity to authenticate with Azure. If true and the client-id is set, will use the client ID as user assigned managed identity client ID. The default value is `false`. |
> |spring.cloud.azure.storage.queue.credential.password | Password to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.storage.queue.credential.username | Username to use when performing username/password authentication with Azure. |
> |spring.cloud.azure.storage.queue.enabled | Whether an Azure Service is enabled. The default value is `true`. |
> |spring.cloud.azure.storage.queue.endpoint | Endpoint for Azure Storage service. |
> |spring.cloud.azure.storage.queue.message-encoding | How queue message body is represented in HTTP requests and responses. |
> |spring.cloud.azure.storage.queue.profile.cloud-type | Name of the Azure cloud to connect to. |
> |spring.cloud.azure.storage.queue.profile.environment.active-directory-endpoint | The Azure Active Directory endpoint to connect to. |
> |spring.cloud.azure.storage.queue.profile.environment.active-directory-graph-api-version | The Azure Active Directory Graph API version. |
> |spring.cloud.azure.storage.queue.profile.environment.active-directory-graph-endpoint | The Azure Active Directory Graph endpoint. |
> |spring.cloud.azure.storage.queue.profile.environment.active-directory-resource-id | The Azure Active Directory resource ID. |
> |spring.cloud.azure.storage.queue.profile.environment.azure-application-insights-endpoint | The Azure Application Insights endpoint. |
> |spring.cloud.azure.storage.queue.profile.environment.azure-data-lake-analytics-catalog-and-job-endpoint-suffix | The Data Lake analytics catalog and job endpoint suffix. |
> |spring.cloud.azure.storage.queue.profile.environment.azure-data-lake-store-file-system-endpoint-suffix | The Data Lake storage file system endpoint suffix. |
> |spring.cloud.azure.storage.queue.profile.environment.azure-log-analytics-endpoint | The Azure Log Analytics endpoint. |
> |spring.cloud.azure.storage.queue.profile.environment.data-lake-endpoint-resource-id | The Data Lake endpoint. |
> |spring.cloud.azure.storage.queue.profile.environment.gallery-endpoint | The gallery endpoint. |
> |spring.cloud.azure.storage.queue.profile.environment.key-vault-dns-suffix | The Key Vault DNS suffix. |
> |spring.cloud.azure.storage.queue.profile.environment.management-endpoint | The management service endpoint. |
> |spring.cloud.azure.storage.queue.profile.environment.microsoft-graph-endpoint | The Microsoft Graph endpoint. |
> |spring.cloud.azure.storage.queue.profile.environment.portal | The management portal URL. |
> |spring.cloud.azure.storage.queue.profile.environment.publishing-profile | The publishing settings file URL. |
> |spring.cloud.azure.storage.queue.profile.environment.resource-manager-endpoint | The resource management endpoint. |
> |spring.cloud.azure.storage.queue.profile.environment.sql-management-endpoint | The SQL management endpoint. |
> |spring.cloud.azure.storage.queue.profile.environment.sql-server-hostname-suffix | The SQL Server hostname suffix. |
> |spring.cloud.azure.storage.queue.profile.environment.storage-endpoint-suffix | The Storage endpoint suffix. |
> |spring.cloud.azure.storage.queue.profile.subscription-id | Subscription ID to use when connecting to Azure resources. |
> |spring.cloud.azure.storage.queue.profile.tenant-id | Tenant ID for Azure resources. |
> |spring.cloud.azure.storage.queue.proxy.hostname | The host of the proxy. |
> |spring.cloud.azure.storage.queue.proxy.non-proxy-hosts | A list of hosts or CIDR to not use proxy HTTP/HTTPS connections through. |
> |spring.cloud.azure.storage.queue.proxy.password | Password used to authenticate with the proxy. |
> |spring.cloud.azure.storage.queue.proxy.port | The port of the proxy. |
> |spring.cloud.azure.storage.queue.proxy.type | Type of the proxy. |
> |spring.cloud.azure.storage.queue.proxy.username | Username used to authenticate with the proxy. |
> |spring.cloud.azure.storage.queue.queue-name | Name of the storage queue. |
> |spring.cloud.azure.storage.queue.resource.name | Name of the storage account. |
> |spring.cloud.azure.storage.queue.resource.region | The region of an Azure resource. |
> |spring.cloud.azure.storage.queue.resource.resource-group | The resource group holds an Azure resource. |
> |spring.cloud.azure.storage.queue.resource.resource-id | ID of an Azure resource. |
> |spring.cloud.azure.storage.queue.retry.exponential.base-delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.storage.queue.retry.exponential.max-delay | Maximum permissible amount of time between retry attempts. |
> |spring.cloud.azure.storage.queue.retry.exponential.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.storage.queue.retry.fixed.delay | Amount of time to wait between retry attempts. |
> |spring.cloud.azure.storage.queue.retry.fixed.max-retries | The maximum number of attempts. |
> |spring.cloud.azure.storage.queue.retry.mode | Retry backoff mode. |
> |spring.cloud.azure.storage.queue.retry.secondary-host | Secondary Storage account to retry requests against. |
> |spring.cloud.azure.storage.queue.retry.try-timeout | Amount of time to wait until a timeout. |
> |spring.cloud.azure.storage.queue.sas-token | Shared access signatures (SAS) token used to authorize requests sent to the service. |
> |spring.cloud.azure.storage.queue.service-version | Queue service version used when making API requests. |
> |spring.cloud.azure.storage.resource-group | Resource group the storage account belongs to. This is a legacy property. |
> |spring.cloud.azure.subscription-id | Subscription ID to use when connecting to Azure resources. This is a legacy property. |
> |spring.cloud.azure.tenant-id | Tenant ID for Azure resources. This is a legacy property. |
> |spring.jms.servicebus.connection-string | Connection string to connect to a Service Bus namespace. |
> |spring.jms.servicebus.idle-timeout | Connection idle timeout duration. The default value is `30m`. |
> |spring.jms.servicebus.listener.phase | The phase in which this container should be started and stopped. |
> |spring.jms.servicebus.listener.reply-pub-sub-domain | Whether the reply destination type is topic. Only works for the bean of topicJmsListenerContainerFactory. |
> |spring.jms.servicebus.listener.reply-qos-settings | The QosSettings to use when sending a reply. |
> |spring.jms.servicebus.listener.subscription-durable | Whether to make the subscription durable. Only works for the bean of topicJmsListenerContainerFactory. The default value is `true`. |
> |spring.jms.servicebus.listener.subscription-shared | Whether to make the subscription shared. Only works for the bean of topicJmsListenerContainerFactory. |
> |spring.jms.servicebus.password | Login password of the AMQP broker. |
> |spring.jms.servicebus.pool.block-if-full | Whether to block when a connection is requested and the pool is full. Set it to false to throw a 'JMSException' instead. |
> |spring.jms.servicebus.pool.block-if-full-timeout | Blocking period before throwing an exception if the pool is still full. |
> |spring.jms.servicebus.pool.enabled | Whether a JmsPoolConnectionFactory should be created, instead of a regular ConnectionFactory. |
> |spring.jms.servicebus.pool.idle-timeout | Connection idle timeout. |
> |spring.jms.servicebus.pool.max-connections | Maximum number of pooled connections. |
> |spring.jms.servicebus.pool.max-sessions-per-connection | Maximum number of pooled sessions per connection in the pool. |
> |spring.jms.servicebus.pool.time-between-expiration-check | Time to sleep between runs of the idle connection eviction thread. When negative, no idle connection eviction thread runs. |
> |spring.jms.servicebus.pool.use-anonymous-producers | Whether to use only one anonymous 'MessageProducer' instance. Set it to false to create one 'MessageProducer' every time one is required. |
> |spring.jms.servicebus.prefetch-policy.all | Fallback value for prefetch option in this Service Bus namespace. The default value is `0`. |
> |spring.jms.servicebus.prefetch-policy.durable-topic-prefetch | The number of prefetch for durable topic. The default value is `0`. |
> |spring.jms.servicebus.prefetch-policy.queue-browser-prefetch | The number of prefetch for queue browser. The default value is `0`. |
> |spring.jms.servicebus.prefetch-policy.queue-prefetch | The number of prefetch for queue. The default value is `0`. |
> |spring.jms.servicebus.prefetch-policy.topic-prefetch | The number of prefetch for topic. The default value is `0`. |
> |spring.jms.servicebus.pricing-tier | Pricing tier for a Service Bus namespace. |
> |spring.jms.servicebus.remote-url | URL of the AMQP broker. Auto-generated by default. The default value is `amqp://localhost:5672`. |
> |spring.jms.servicebus.topic-client-id | Service Bus topic client ID. Only works for the bean of topicJmsListenerContainerFactory. |
> |spring.jms.servicebus.username | Login user of the AMQP broker. |