# Deploying-Multi-tier-VPC-using-cloud-formation


Step 1: Login to your AWS Account & Create the AWS CloudFormation Stack

Login to your AWS account and type “AWS CloudFormation” into the search box to bring up the AWS CloudFormation console. Click on “With new resources (standard)”

Deployments through AWS CloudFormation are all done through a template and will be using a template for this project that will contain all the necessary script to our multi tier architecture.

Under the prerequisite tab select “Template is ready”

Under the Specify template tab, “Select upload a template file”. Please reference the attached yml file.

The template we will be using will deploy a Multi tier VPC(Virtual Private Cloud)

Click “Next” to move to specify stack details.

Step 2: Specify Stack Details

Once the template stack is uploaded it will pre-populate the stack details with everything needed to deploy our virtual private cloud infrastructure.
The stack configuration details are listed below in the screenshot.
For the stack name use: “WebApp1-VPC”
Leave all details and settings as is and click “Next”

Step 3: Configure Stack Options

Next up you can create tags to use for the deployment our stack.
For the key use “Owner” and for use your email as the “Value”. Click Next to move to the stack review page. This will be our last step before we can officially deploy our VPC.

Step 4: Review WebApp1-VPC

When you get to the review page accept the acknowledge statement. The acknowledgement statement states that it will create IAM resources for the deployment.
Click “Submit” which will start the deployment by AWS CloudFormation.

Step 5: Deployment in Progress

You can see the deployment progress by clicking on the events tab under our stack. The deployment events will show you in real time each and every resource that is being deployed along with their status.
The deployment time will take a few minutes before everything is successfully deployed.

Creation in progress. You can see the events taking place
Congratulations our VPC and all the necessary components needed for it to work has been officially deployed!


Web Application & Database Deployment
Step 1: Create a template for the web application and database deployment

Just like with our VPC configuration will be using a YAML template for the Web Application.

Select “Template is ready” under the Prerequisite tab

Select “Upload a template file” under the Specify template. (Here is the YAML template configuration file)

Click “Next” to move to the specify stack details

Step 2: Specify Stack Details

Choose the stack name for the stack. For this project I used “CloudFormationLab”.

The YAML configuration will pre-populate the parameters with our stack resources.

Step 3: Configure stack options

Next up you can create tags to use for the deployment our stack.

For the key use “Owner” and for use your email as the “Value”. Click Next to move to the stack review page. This will be our last step before we can officially deploy our VPC.

Step 4: Review CloudFormationLab

Accept the the AWS CloudFormation acknowledgement statement and click “Submit”

Step 5: Deployment in Progress

You can see the deployment progress by clicking on the events tab under our stack. The deployment events will show you in real time each and every resource that is being deployed along with their status.
The deployment time will take a few minutes before everything is successfully deployed.
