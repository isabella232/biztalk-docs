# [Microsoft BizTalk Adapter for Oracle Database documentation](microsoft-biztalk-adapter-for-oracle-database-documentation.md)
## [Get started](get-started-with-the-oracle-database-adapter.md)
### [Understand the BizTalk Adapter for Oracle Database](understand-the-biztalk-adapter-for-oracle-database.md)
#### [Overview of BizTalk Adapter for Oracle Database](overview-of-biztalk-adapter-for-oracle-database.md)
##### [Connect to Oracle Database using the adapter](connect-to-oracle-database-using-the-adapter.md)
##### [Browse, search, and get Oracle Database metadata](browse-search-and-get-oracle-database-metadata.md)
##### [View the supported operations](what-operations-are-supported-by-the-oracle-database-adapter.md)
###### [Insert, update, delete, and select operations](insert-update-delete-and-select-operations-on-oracle-tables-and-views.md)
###### [Operations on tables and views that contain LOB data](operations-on-tables-and-views-that-contain-lob-data-in-oracle-database.md)
###### [Operations on functions and stored procedures](operations-on-functions-and-stored-procedures-in-oracle-database.md)
###### [Operations on Functions and Procedures with REF CURSOR Parameters](ref-cursor-parameters-in-oracle-database-adapter.md)
###### [Operations on Functions and Procedures with RECORD Types](operations-on-functions-and-procedures-with-record-types-in-oracle-database.md)
###### [Operations on Tables With BFILE Data Types](operations-on-tables-with-bfile-data-types-in-oracle-database.md)
###### [Operations on Synonyms](operations-on-synonyms-in-oracle-database.md)
###### [SQLEXECUTE Operation](sqlexecute-operation-in-oracle-database.md)
###### [Run Composite Operations in Oracle Database](run-composite-operations-in-oracle-database.md)
###### [Support for Receiving Polling-based Data-changed Messages](support-for-receiving-polling-based-data-changed-messages-in-oracle-database.md)
###### [Receive Database Change Notifications](receive-oracle-database-change-notifications.md)
###### [Support for Oracle User-Defined Types](support-for-oracle-user-defined-types-in-oracle-database.md)
##### [Handle transactions with the adapter](handle-transactions-with-the-oracle-database-adapter.md)
##### [Streaming support for LOB data types](streaming-support-for-lob-data-types-in-oracle-database.md)
##### [Features for adapter clients](features-for-oracle-database-adapter-clients.md)
#### [Key Features of the adapter](key-features-in-biztalk-adapter-for-oracle-database.md)
#### [Limitations of the adapter](limitations-of-biztalk-adapter-for-oracle-database.md)
### [Tutorial: Migrate BizTalk Projects](tutorial-migrate-biztalk-projects-to-the-oracle-database-adapter.md)
#### [Step 1: Modify the vPrev BizTalk Project](step-1-modify-the-vprev-biztalk-project-in-oracle-database.md)
#### [Step 2: Configure the orchestration in BizTalk Server Administration console](step-2-configure-an-orchestration-to-use-the-oracle-db-adapter-in-biztalk.md)
#### [Step 3: Test the migrated application](step-3-test-the-migrated-application-to-oracle-database-adapter.md)
## [Architecture overview](architecture-overview-of-the-biztalk-adapter-for-oracle-database.md)
## [Secure your Oracle Database applications](secure-your-oracle-database-applications.md)
### [Security between the Oracle Database and the adapter](security-between-the-oracle-database-and-the-adapter.md)
### [Security with the adapter and BizTalk Server](security-with-the-oracle-database-adapter-and-biztalk-server.md)
### [Secure programming with the adapter](secure-programming-with-the-oracle-database-adapter.md)
### [Security best practices](best-practices-to-secure-the-oracle-database-adapter.md)
## [Develop your Oracle Database applications](develop-your-oracle-database-applications.md)
### [Create a connection to the Oracle Database](create-a-connection-to-the-oracle-database.md)
#### [Configure the Oracle client](configure-the-oracle-client-for-the-oracle-database-adapter.md)
#### [Create the connection URI](create-the-oracle-database-connection-uri.md)
#### [Connect using Windows Authentication](connect-to-the-oracle-database-using-windows-authentication.md)
### [Get metadata for Oracle DB operations in Visual Studio](get-metadata-for-oracle-database-operations-in-visual-studio.md)
#### [Connect to Oracle Database in Visual Studio](connect-to-oracle-database-in-visual-studio.md)
##### [Connect  using the Consume Adapter Service](connect-to-oracle-database-in-visual-studio-using-the-consume-adapter-service.md)
##### [Connect using the Add Adapter Metadata Wizard](connect-to-oracle-database-in-visual-studio-using-add-adapter-metadata-wizard.md)
##### [Connect using the Add Adapter Service Reference](connect-to-the-oracle-db-in-visual-studio-using-the-add-adapter-service.md)
#### [Browse, search, and get metadata for Oracle DB operations](browse-search-and-get-metadata-for-oracle-database-operations.md)
#### [Metadata Node IDs](metadata-node-ids3.md)
### [Working with the binding properties](read-about-the-oracle-database-adapter-binding-properties.md)
### [Streaming large object data types](streaming-large-object-data-types-in-oracle-database-adapter.md)
### [Receive polling-based data-changed messages](receive-polling-based-data-changed-messages-in-oracle-database-adapter.md)
### [Develop BizTalk applications using the Oracle DB adapter](develop-biztalk-applications-using-the-oracle-database-adapter.md)
#### [Create strong-name key file, and learn the tools](prerequisites-to-create-oracle-database-applications.md)
#### [Building blocks to create BizTalk applications](building-blocks-to-develop-biztalk-applications-with-oracle-database.md)
##### [Add the adapter to BizTalk Server Administration](adding-the-oracle-database-adapter-to-biztalk-server-administration-console.md)
##### [Enter the connection URI](configure-the-connection-uri-for-the-oracle-database-adapter.md)
##### [Enter the sign in credentials](configure-the-sign-in-credentials-for-the-oracle-database.md)
##### [Enter the binding properties](configure-the-binding-properties-for-oracle-database.md)
##### [Enter the SOAP action](configure-the-soap-action-for-oracle-database.md)
##### [Manually create a physical port binding to the adapter](manually-configure-a-physical-port-binding-to-the-oracle-database-adapter.md)
###### [Configure a port using the WCF-custom adapter](configure-a-port-using-the-wcf-custom-adapter-and-oracle-database-adapter.md)
###### [Configure a port using the WCF-OracleDB adapter](configure-a-port-using-the-wcf-oracledb-adapter.md)
##### [Configure a physical port binding using a port binding file](configure-a-physical-port-binding-using-a-port-binding-file-to-oracle-database.md)
##### [Configure dynamic ports](configure-dynamic-ports-in-the-oracle-database-adapter.md)
##### [Reuse adapter bindings](reuse-oracle-database-adapter-bindings.md)
#### [Insert, update, delete, or select operations](insert-update-delete-select-operations-using-biztalk-server-with-oracle-db.md)
#### [Run operations on tables with large object data types](run-operations-on-tables-with-large-object-data-types-in-oracle-database.md)
#### [Invoke functions and procedures](invoke-functions-and-procedures-in-oracle-database-using-biztalk-server.md)
#### [Invoke overloaded functions and procedures](run-overloaded-functions-and-procedures-in-oracle-database-using-biztalk-server.md)
#### [Invoke functions and procedures with REF CURSORS](run-functions-and-procedures-with-ref-cursors-in-oracle-db-using-biztalk-server.md)
#### [Invoke functions and procedures with RECORD Types](run-functions-and-procedures-with-record-types-in-oracle-db-with-biztalk-server.md)
#### [Run operations on tables with BFILE data types](run-operations-on-tables-with-bfile-data-types-in-oracle-db-using-biztalk.md)
#### [Run SQLEXECUTE operation](run-sqlexecute-operation-in-oracle-database-using-biztalk-server.md)
#### [Poll Oracle DB using BizTalk Server](poll-oracle-database-using-biztalk-server.md)
##### [Poll using SELECT statement](poll-oracle-database-using-the-select-statement.md)
##### [Poll using stored procedures, functions, or packaged procedures and functions](poll-oracle-db-using-stored-procedures-functions-or-packaged-procedures.md)
#### [Run composite operations](run-composite-operations-on-oracle-database-using-biztalk-server.md)
#### [Receive database change notifications](receive-oracle-database-change-notifications-using-biztalk-server.md)
##### [Before you begin](before-you-receive-database-change-notifications-using-the-oracle-db-adapter.md)
##### [Process notification messages](process-notification-messages-to-run-specific-tasks-in-oracle-db-using-biztalk.md)
##### [Receive database change notifications incrementally using BizTalk Server](receive-oracle-database-change-notifications-incrementally-using-biztalk-server.md)
##### [Receive database change notifications on multiple receive locations](receive-oracle-database-change-notifications-on-multiple-receive-locations.md)
##### [Receive database change notifications after a receive location breakdown](receive-oracle-database-change-notifications-after-a-receive-location-breakdown.md)
### [Develop applications using the WCF Service Model](develop-oracle-database-applications-using-the-wcf-service-model.md)
#### [Overview of the WCF service model with the adapter](overview-of-the-wcf-service-model-with-the-oracle-database-adapter.md)
#### [Metadata and the WCF Service Model](metadata-and-the-wcf-service-model-with-oracle-database.md)
#### [Generate a WCF client or a WCF service contract for solution artifacts](create-a-wcf-client-or-wcf-service-contract-for-oracle-db-solution-artifacts.md)
#### [Configure a client binding](configure-a-client-binding-for-the-oracle-database.md)
#### [Insert, update, delete, or select operations](insert-update-delete-select-operations-in-oracle-db-using-a-wcf-service.md)
#### [Run operations on tables with large data types](run-operations-on-tables-with-large-data-types-in-oracle-db-using-a-wcf-service.md)
#### [Invoke functions and procedures](invoke-functions-and-procedures-in-oracle-database-using-the-wcf-service-model.md)
#### [Run operations using REF CURSORS](run-operations-using-ref-cursors-in-oracle-database-using-the-wcf-service-model.md)
#### [Run operations using RECORD types](using-record-types-in-oracle-database-using-the-wcf-service-model.md)
#### [Run SQLEXECUTE operation](run-sqlexecute-operation-in-oracle-database-using-the-wcf-service-model.md)
#### [Receive polling-based data-changed messages](receive-polling-based-data-changed-messages-in-oracle-db-using-a-wcf-service.md)
#### [Receive database change notifications](receive-oracle-database-change-notifications-using-the-wcf-service-model1.md)
### [Develop applications using the WCF Channel Model](develop-oracle-database-applications-using-the-wcf-channel-model.md)
#### [Overview of the WCF channel model with the adapter](overview-of-the-wcf-channel-model-with-the-oracle-database-adapter.md)
#### [Create a channel](create-a-channel-using-oracle-database.md)
#### [Invoke operations](invoke-operations-on-the-oracle-database-using-the-wcf-channel-model.md)
#### [Run SQLEXECUTE operation](run-a-sqlexecute-operation-in-oracle-database-using-the-wcf-channel-model.md)
#### [Run an Insert operation](run-an-insert-operation-in-oracle-database-using-the-wcf-channel-model.md)
#### [Invoke a function](invoke-a-function-in-oracle-database-using-the-wcf-channel-model.md)
#### [Receive polling-based data-changed messages](receive-polling-based-data-changed-messages-in-oracle-db-using-a-wcf-channel.md)
#### [Streaming LOB data types](streaming-oracle-database-lob-data-types-using-the-wcf-channel-model.md)
### [Get metadata programmatically](get-metadata-programmatically-from-the-oracle-database.md)
#### [Get metadata using WS-Metadata exchange](get-metadata-using-ws-metadata-exchange-in-oracle-database.md)
#### [Get metadata using IMetadataRetrievalContract](get-metadata-in-oracle-database-using-imetadataretrievalcontract.md)
### [Use the Oracle DB adapter with SharePoint](use-the-oracle-database-adapter-with-sharepoint.md)
### [Samples](samples-for-the-oracle-database-adapter.md)
### [Configure transaction isolation level and transaction timeout](configure-transaction-isolation-level-and-transaction-timeout-with-oracle-db.md)
### [Use svcutil.exe](use-the-servicemodel-metadata-utility-with-the-oracle-db-adapter-in-biztalk.md)
## [Messages and Message Schemas for BizTalk Adapter for Oracle Database](messages-and-message-schemas-for-biztalk-adapter-for-oracle-database.md)
### [Basic Oracle Data Types](basic-oracle-data-types1.md)
### [Message Schemas for the Basic Insert, Update, Delete, and Select Operations on Tables and Views](message-schemas-for-insert-update-delete-and-select-on-tables-and-views.md)
### [Message Schemas for Special LOB Operations](message-schemas-for-special-lob-operations2.md)
### [Message Schemas for Functions and Procedures](message-schemas-for-functions-and-procedures.md)
### [Message Schemas for REF CURSORS](message-schemas-for-ref-cursors.md)
### [Message Schemas for RECORD Types](message-schemas-for-record-types.md)
### [Message Schemas for the SQLEXECUTE Operation](message-schemas-for-the-sqlexecute-operation.md)
### [Message Schemas for the Polling Operations](message-schemas-for-the-polling-operations2.md)
### [Message Schemas for the Composite Operation](message-schemas-for-the-composite-operation2.md)
### [Message Schemas for the Notification Operation](message-schemas-for-the-notification-operation1.md)
## [Troubleshoot](troubleshoot-the-oracle-database-adapter.md)
### [Diagnostic tracing and message logging](diagnostic-tracing-and-message-logging-for-the-oracle-database-adapter.md)
### [Troubleshoot installation issues](troubleshoot-installation-issues-with-the-oracle-database-adapter.md)
### [Troubleshoot operational issues](troubleshoot-operational-issues-with-the-oracle-database-adapter.md)
### [Troubleshoot performance issues](troubleshoot-performance-issues-with-the-oracle-database-adapter.md)
### [Use performance counters](use-performance-counters-with-the-oracle-database-adapter.md)
### [Exceptions and error handling](exceptions-and-error-handling-with-the-oracle-database-adapter.md)
## [Terms and definitions](glossary3.md)
## [API namespace reference](/dotnet/api/?view=bts-oracle-db)