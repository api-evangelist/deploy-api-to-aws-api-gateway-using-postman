# Deploy API to AWS API Gateway Using Postman

This is a Postman collection for deploying an API to AWS API Gateway. It pulls the OpenAPI for any API you are managing within Postman, adds vendor extensions to the OpenAPI, creates an AWS DynamoDB table, publishes the OpenAPI to the AWS API Gateway, then deploys the API--then also generating a usage plan and API key to secure the API. Currently the collection is a ten step process, but will be changing regularly to provide the most granular and flexible approach to deploying a simple API to AWS from Postman.

- **Documentation:** [https://documenter.getpostman.com/view/35240/SWLce9Vf?version=latest](https://documenter.getpostman.com/view/35240/SWLce9Vf?version=latest)
- **Collection:** [deploy-api-to-aws-api-gateway-using-postman.json](deploy-api-to-aws-api-gateway-using-postman.json)
- **Environment:** [deploy-api-to-aws-api-gateway-using-postman-environment.json](deploy-api-to-aws-api-gateway-using-postman-environment.json)

If you have any requests for new API governance rules, find bugs, or have questions about how it works feel free to submit as a GitHub issue, and I'll work to consider as I move this API governance Postman collection forward.
