---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

IPrintConnectorCollectionWithReferencesPage connectors = graphClient.print().printers("{printerId}").connectors()
	.buildRequest()
	.get();

```