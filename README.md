## Amazon Comprehend Immersion Day-Deevanshu
A Comprehend Immersion Day provides our customers with hands-on experience with Amazon Comprehend demonstrating how they can build natural language processing (NLP) use cases, and is specifically designed to help us accelerate a customer opportunity.

Comprehend Immersion Days leverage a modular content format, allowing you to select from ready-made presentations and labs and adapt your curriculum to your customer’s needs.

After attending a Comprehend Immersion Day, customers would be able to leverage the service to extract insights and relationships in text. They will be able to address a number of use cases around extraction of entities and key phrases, detecting sentiment and syntax, detecting and redacting personally identifiable information (PII) using NLP, train Comprehend to detect entities specific to their business or to classify documents to assign classes that are relevant to their use cases.

## AWS Accounts

For a Comprehend Immersion Day, you need to use your own AWS accounts. In that case:

* use a AWS account that is not running production systems.
* Any accounts should be created a minimum of three days ahead of time. It takes time for new accounts to be completely ready, payment methods to be confirmed, and limits to be set.



## Lab Setup
Deploy a cloud formation template that will perform much of the initial setup work for you. In a another browser window or tab, login to your AWS account. Once you have done that, open the link below by clicking Launch Stack button in a new tab to start the process of deploying  the items you need via CloudFormatoin.

This CloudFormation template will complete the following:
1. Create a SageMaker Role
2. Create a SageMaker Notebook instance
3. Clone this repo codebase onto the Notebook instance.
## Follow below steps to deploy cloudformation template
1. Download stack (https://comprehend-immersionday.workshop.aws/code/prerequisites/comprehend-im-setup.yml)
2. Click Cloudformation console link https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/create/template
3. Select "Upload a template file"  and Choose the downloaded template "comprehend-im-setup.yml" as shown in below screenshot and click next.
![](createstack.PNG)
5. For stackname -> Enter "Comprehend Immersion day", scroll down and click next till you reach review. 
6. For capabilities, check the on Acknowledge box as shown below and click on "Create Stack" button.
![](createfinalstack.PNG)
8. Your Stack will be Create in Progress, In few minutes the status will change to "Craete Complete".
9. Once Status changes to "Create Complete", Go to Sagemaker Console Notebook Instance -> https://console.aws.amazon.com/sagemaker/home?region=us-east-1#/notebook-instances
10. A notebook has been created with all the lab code setup, Click on Open Jupyter as shown below:
![](comprehend-im-jupyter.PNG)
12. Click on folder amazon-comprehend-immersion-day->code and you will find the respective labs. Follow the lab instructions for each lab.
![](laboverview-comp-imday.PNG)




## Overview of the Labs

Find details on each lab here - https://comprehend-immersionday.workshop.aws/ 

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

