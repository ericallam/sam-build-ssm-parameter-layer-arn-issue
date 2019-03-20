# sam-build-ssm-parameter-layer-arn-issue

Output of `sam build --debug`:

```
2019-03-20 14:52:10 Using SAM Template at /Users/eric/code/Solve/opensource/sam-build-ssm-parameter-layer-arn-issue/template.yml
2019-03-20 14:52:10 Changing event name from creating-client-class.iot-data to creating-client-class.iot-data-plane
2019-03-20 14:52:10 Changing event name from before-call.apigateway to before-call.api-gateway
2019-03-20 14:52:10 Changing event name from request-created.machinelearning.Predict to request-created.machine-learning.Predict
2019-03-20 14:52:10 Changing event name from before-parameter-build.autoscaling.CreateLaunchConfiguration to before-parameter-build.auto-scaling.CreateLaunchConfiguration
2019-03-20 14:52:10 Changing event name from before-parameter-build.route53 to before-parameter-build.route-53
2019-03-20 14:52:10 Changing event name from request-created.cloudsearchdomain.Search to request-created.cloudsearch-domain.Search
2019-03-20 14:52:10 Changing event name from docs.*.autoscaling.CreateLaunchConfiguration.complete-section to docs.*.auto-scaling.CreateLaunchConfiguration.complete-section
2019-03-20 14:52:10 Changing event name from before-parameter-build.logs.CreateExportTask to before-parameter-build.cloudwatch-logs.CreateExportTask
2019-03-20 14:52:10 Changing event name from docs.*.logs.CreateExportTask.complete-section to docs.*.cloudwatch-logs.CreateExportTask.complete-section
2019-03-20 14:52:10 Changing event name from before-parameter-build.cloudsearchdomain.Search to before-parameter-build.cloudsearch-domain.Search
2019-03-20 14:52:10 Changing event name from docs.*.cloudsearchdomain.Search.complete-section to docs.*.cloudsearch-domain.Search.complete-section
2019-03-20 14:52:10 Changing event name from creating-client-class.iot-data to creating-client-class.iot-data-plane
2019-03-20 14:52:10 Changing event name from before-call.apigateway to before-call.api-gateway
2019-03-20 14:52:10 Changing event name from request-created.machinelearning.Predict to request-created.machine-learning.Predict
2019-03-20 14:52:10 Changing event name from before-parameter-build.autoscaling.CreateLaunchConfiguration to before-parameter-build.auto-scaling.CreateLaunchConfiguration
2019-03-20 14:52:10 Changing event name from before-parameter-build.route53 to before-parameter-build.route-53
2019-03-20 14:52:10 Changing event name from request-created.cloudsearchdomain.Search to request-created.cloudsearch-domain.Search
2019-03-20 14:52:10 Changing event name from docs.*.autoscaling.CreateLaunchConfiguration.complete-section to docs.*.auto-scaling.CreateLaunchConfiguration.complete-section
2019-03-20 14:52:10 Changing event name from before-parameter-build.logs.CreateExportTask to before-parameter-build.cloudwatch-logs.CreateExportTask
2019-03-20 14:52:10 Changing event name from docs.*.logs.CreateExportTask.complete-section to docs.*.cloudwatch-logs.CreateExportTask.complete-section
2019-03-20 14:52:10 Changing event name from before-parameter-build.cloudsearchdomain.Search to before-parameter-build.cloudsearch-domain.Search
2019-03-20 14:52:10 Changing event name from docs.*.cloudsearchdomain.Search.complete-section to docs.*.cloudsearch-domain.Search.complete-section
2019-03-20 14:52:10 'build' command is called
2019-03-20 14:52:10 Collected default values for parameters: {'CustomSDKsLayerVersionArn': 'CustomSDKs/ARN'}
2019-03-20 14:52:10 1 resources found in the template
Error: CustomSDKs/ARN is an Invalid Layer Arn.
```
