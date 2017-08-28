# AutoTag all EC2 instances.
Date: 2017-08-28

This CloudFormation templates is prepared to lunch as StackSets.

Configuration AutoTag all created EC2 instances with tag OWNER and value of aws account username, who crated an EC2.

Read more about StackSets:
https://aws.amazon.com/blogs/aws/use-cloudformation-stacksets-to-provision-resources-across-multiple-aws-accounts-and-regions/

How to:
1. Go to AWS console -> CloudFormation.
2. From the top left side menu click on CloudFormation and choose a StackSets
3. Deploy the configuration on account and regions you need to.

For details how to implement StackSets please read an link above.


Author:
Łukasz Dorosz (lukasz.dorosz@ttms.pl)
