# awesome-cloudformation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Awesome curated list of AWS CloudFormation links

If you want to contribute to this list (please do), send me a pull request.

## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [AWS Documentation](#aws)
- [Articles](#articles)
- [Tools](#tools)
- [DSLs and Generators](#dsls)
- [Examples](#examples)
- [Comparing, Evaluating, Integrating with other Tools](#other-tools)

<!-- /MarkdownTOC -->

<a name="aws" />
## AWS Documentation

* [User Guide](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html) - AWS Official User Guide
* [API Reference](http://docs.aws.amazon.com/AWSCloudFormation/latest/APIReference/Welcome.html) - AWS Official API Reference

<a name="articles" />
## Articles

[Build Continuous Delivery Workflows for CloudFormation Stacks](https://aws.amazon.com/blogs/aws/codepipeline-update-build-continuous-delivery-workflows-for-cloudformation-stacks/) - 
describes how to setup a continuous delivery workflow for deploying CloudFormation Templates using CloudFormation.

[AWS Git-backed Static Website](https://alestic.com/2016/10/aws-git-backed-static-website/) -
Describes CloudFormation Template to deploy a static website with continous deployment.  Supports Hugo or plain html.

[Running AWS Lambda Functions in AWS CodePipeline using CloudFormation](https://stelligent.com/2016/02/08/aws-lambda-functions-aws-codepipeline-cloudformation/) -
Describes setting up an invoke action in a CodePipeline.

[Automating AWS CodeDeploy Provisioning in CloudFormation](https://stelligent.com/2016/01/15/automating-aws-codedeploy-provisioning-in-cloudformation/) -
Deploying a CodePipeline using CodeDeploy service configured by CloudFormation.

[Optional Parameters For Pre-existing Resources in AWS CloudFormation Templates](https://alestic.com/2016/11/aws-cloudformation-optional-resources/) -
How to construct CloudFormation templates that can create new resources or use pre-existing resources.

[CloudFormation To Build A CDN With (Free) Custom SSL](https://serverlesscode.com/post/acm-certificates-in-cloudformation/) -
How to use AWS Certificate Manager with CloudFormation and CloudFront.

<a name="tools" />
## Tools
[CFN Nag](https://github.com/stelligent/cfn_nag) - Linting tool for CloudFormation templates

<a name="dsls" />
## DSLs and Generators
[troposphere](https://github.com/cloudtools/troposphere) - Python library to create AWS CloudFormation descriptions

[cfndsl](https://github.com/stevenjack/cfndsl) - Ruby DSL for generating AWS CloudFormation templates

[CloudFormation Template Generator](https://github.com/MonsantoCo/cloudformation-template-generator) - 
A type-safe Scala DSL for generating CloudFormation templates

<a name="examples" />
## Examples

[AWS CloudFormation Template Collection](https://github.com/awslabs/aws-cloudformation-templates) - Officially supported 
and community contributed AWS sample templates.

[User Guide Sample Templates](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/cfn-sample-templates.html) -
Sample templates from the CloudFormation User Guide.

[Stelligent CloudFormation Templates](https://github.com/stelligent/cloudformation_templates) -
Impressive collection of templates from Stelligent.

[Continuous Deployment Reference Architecture] (https://github.com/awslabs/ecs-refarch-continuous-deployment) - Reference Architecture for creating a flexible and scalable deployment pipeline to Amazon ECS using AWS CodePipeline.  Demonstrates
a GitHub CodePipeline source and a PHP application with an ECS cluster and load balancer.

[Continuous Delivery Basic Walkthrough](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide//continuous-delivery-codepipeline-basic-walkthrough.html) -
CloudFormation userguide walkthrough of setting up a CodePipeline for Continuous delivery that uses a CloudFormation
stack to deploy a separate CloudFormation stack.

[aws-git-backed-static-website](https://github.com/alestic/aws-git-backed-static-website) -
CloudFormation Template configuring several AWS services to create a static website with Continuous deployment.
Uses CodeCommit, CodePipeline, Certificate Manager, Route 53, Lamda, CloudFront.  Uses CloudFormation Conditions.

[AWS API Gateway Developer Portal](https://github.com/awslabs/aws-api-gateway-developer-portal) - An example serverless application deployment with Cognito and Lambda configuration in CloudFormation.

[Serverless Image Resizing](https://github.com/awslabs/serverless-image-resizing) - An image resizing API deployed
with CloudFormation built on Lambda and API Gateway with S3.

[Startup Kit Serverless Workload](https://github.com/awslabs/startup-kit-serverless-workload) - An example serverless RESTful API, to be deployed via the AWS Serverless Application Model (SAM).

[Dromedary](https://github.com/stelligent/dromedary) -
Sample App to demonstrate a working CodePipeline featured in ARC307: Infrastructure as Code breakout session at 2015 AWS re:Invent.

[Dromedary Serverless](https://github.com/stelligent/dromedary-serverless) -
Serverless version of the Dromedary application.

<a name="other-tools" />
## Comparing, Evaluating, Integrating with other Tools
[Heat](https://wiki.openstack.org/wiki/Heat) - CloudFormation compatible Orchestration program for OpenStack.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Jeff Moore has waived all copyright and related or neighboring rights to this work.
