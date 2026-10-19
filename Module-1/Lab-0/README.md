| Deployment | Public IPv4 address | Connection method | Screenshot | Instance terminated? |
|------------|---------------------|-------------------|------------|----------------------|
| 1 | 3.90.186.104 | EC2 ConnecE | INSTANCE.1 (988F).png | Yes |
| 2 | 35.172.227.196  | EC2 Connect INSTANCE.2(BAB8).png | Yes |
| 3 | 54.159.46.172  | SSH | INSTANCE.3.SSH (DE81).png | Yes |


## Deployment 1 – MICRO
1. Launch instance from template
2. Select t3. micro Instance type
3. Confirm User Data in Advanced Details
4. Launch instance
5. Open Link
6. Connect
   - Wait for Status to pass checks
   - Connect
   - 1.9Gi memory
   - Default port 22 SSH from Security Group
7. Screenshot
## Terminate EC2 – Deployment 1
1. EC2 > Instances (running) > Instance State > Delete

## Deployment 2 – MICRO
1.	Launch instance from template
2.	Select t3. micro Instance type
3.	Confirm User Data in Advanced Details
4.	Launch instance
5.	Open Link
6.	Connect 
    -	Wait for Status to pass checks
    -	Connect 
    -	913 Mi memory
    -	Default port 22 SSH from Security Group
7.	Screenshot 
## Terminate EC2 – Deployment 2
1.	EC2 > Instances (running) > Instance State > Delete

## Deployment 3 – MICRO
1.	Launch instance from template
2.	Select t3. micro  Instance type
3.	Confirm User Data in Advanced Details
4.	Launch instance
5.	Open Link
6.	Connect 
     -	Wait for Status to pass checks
     -	Connect 
     -	3.7Gi memory
     -	USED WARRIOR-HOME-SECURITY GROUP for port 22 SSH from home i.p.
7.	Screenshot 
## Terminate EC2 – Deployment 3
1.	EC2 > Instances (running) > Instance State > Delete

## Summary
CPU is usage, but all three were 0% with 2 vCPUs. Each instance size was the same memory . All three had the same size disk and usage amount. Uptime was how long the instance was running. 

Each instance further helped me recall the process from Class 6 before my deployment last year . No errors were encountered. All  instances terminated and my instance remains available. 
