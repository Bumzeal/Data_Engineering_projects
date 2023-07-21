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

Create a database called BookCatalog.
![image](https://github.com/Bumzeal/Data_Engineering_projects/assets/78567274/f9e16e97-608d-4826-9d03-cb9c40a06129)



