---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

query_params = OutcomesRequestBuilder.OutcomesRequestBuilderGetQueryParameters(
		filter = "isof('microsoft.graph.educationFeedbackResourceOutcome')",
)

request_configuration = OutcomesRequestBuilder.OutcomesRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.education.classes.by_classe_id('educationClass-id').assignments.by_assignment_id('educationAssignment-id').submissions.by_submission_id('educationSubmission-id').outcomes.get(request_configuration = request_configuration)


```