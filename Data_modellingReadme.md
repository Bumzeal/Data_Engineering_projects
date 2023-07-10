
# DATA MODELLING

## Creating and Loading Database into shell psql
+  Launch psql
+  Enter Required Postgres Details
+  Create a Database "DVDRENTAL1"
+  
## Step  2: Launch CMD
+ Entcd cd..
+ Repeat the above step
+ Enter cd "Program Files"
+ Enter cd PostgreSQL
+ Enter cd 15
+ Enter cd bin
+ enter pg_restore _U Postgres -d dvdrental1 "C:\Users\BUNMI\Desktop\dvdrental.tar"

![image](https://github.com/Bumzeal/Data_Engineering_projects/assets/78567274/7510ec65-e051-4f12-89fd-f70810c85dbf)

Step 3 Launch shell psql
+  Enter your Localhost details
+  Enter \c Dvdrental1 to switch into Dvdrental1 database
+  Enter \dt to check the tables in this Database

![image](https://github.com/Bumzeal/Data_Engineering_projects/assets/78567274/04b27494-780e-41ed-afb1-7c26fba0c36b)
