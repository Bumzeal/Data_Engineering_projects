ETL with AWS GLUE

Step 1 - Add Source

  Set up an S3 bucket called "etl-awsglue-bucket and upload a csv file

![image](https://github.com/Bumzeal/Data_Engineering_projects/assets/78567274/f7942039-35e0-43ab-9bf9-1125a82f9531)

step 2 - Create a Postgres Instance

Create a Free Tier PostgreSQL RDS instance, ensuring it has the following attributes: Version: PostgreSQL 12.5-R1. 
Under DB instance class, select the Burstable classes radio button > db.t2.micro. Under Connectivity, 
use default VPC & Security group settings. Make sure that the instance is publicly accessible by selecting the appropriate radio button.
Use a SQL Client to connect to the RDS database. If you have forgotten how to do so, you may use this resource for reference. Create a database called BookCatalog.

![image](https://github.com/Bumzeal/Data_Engineering_projects/assets/78567274/ab21b60a-911f-4777-a381-ce306c40e478)
Use a SQL Client to connect to the RDS database. If you have forgotten how to do so, you may use this resource for reference. Create a database called BookCatalog.

![image](https://github.com/Bumzeal/Data_Engineering_projects/assets/78567274/39ea4412-28c1-43a1-8cc4-ff15df07f46d)

Create a database called BookCatalog. Create a table in the database using the 
![image](https://github.com/Bumzeal/Data_Engineering_projects/assets/78567274/f9e16e97-608d-4826-9d03-cb9c40a06129)

Step 3: Create a VPC Endpoint to access your S3 bucket
Back to exercise overview In the AWS console, go to Services and navigate to VPC, which can be found under the Networking & Content Delivery section. In the navigation pane found on the left, click on Endpoints. Click on Create Endpoint.

![image](https://github.com/Bumzeal/Data_Engineering_projects/assets/78567274/6b924416-8966-4ec1-b5ae-6710331aa5f3)

Step 4: Add AWS Glue classifier for the source data
Back to exercise overview An AWS Glue classifier determines the schema of data sources in our pipeline. There are two choices when creating a classifier; we either write our own or select from a catalogue of pre-built versions. For this exercise, we will use the latter. Here we need to refer to our CSV data in the S3 bucket so that Glue knows where to look for our data. In the management console, click on Services and navigate to AWS Glue under Analytics. In the navigation bar on your left, click on Classifiers. Click on Add classifier.

![image](https://github.com/Bumzeal/Data_Engineering_projects/assets/78567274/5370ce41-fdd3-4b0a-8f3f-1a31b523fc72)

![image](https://github.com/Bumzeal/Data_Engineering_projects/assets/78567274/be1d4cf5-1fc6-4749-a1d9-0015f05f8bf6)



