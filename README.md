# ec2instancestartifstopped   
# contact me at nehrusani@gmail.com for any python or aws lambda support.
Start AWS EC2 instance if stopped by cloudwatch

Pre-requisite:  

A. AWS using SNS service create one topic and it will give you ARN number and define it in       https://github.com/nehrusani/ec2instancestartifstopped/blob/master/AWSLambda2startEC2instance
B. AWS Lambda service and define python 3.7
C. And create tag in ec2 instance and associate each instance with that tag as mentioned below:
   Tagname:  LambdaStartInstnace
   Tagvalue: Enabled
As this tag would be used by my above mentioned lambda code to check only those instance having following instance state. So that if you create any test instnace and you want to play with it will not touch those instnace.   


