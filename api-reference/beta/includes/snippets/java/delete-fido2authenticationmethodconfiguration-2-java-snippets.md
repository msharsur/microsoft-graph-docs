---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

graphClient.policies().authenticationMethodsPolicy().authenticationMethodConfigurations("TemporaryAccessPass")
	.buildRequest()
	.delete();

```