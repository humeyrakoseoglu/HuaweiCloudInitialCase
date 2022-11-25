# Huawei Cloud Technical Case ☁ 


## Case: Communicate VPCs Each Other

You are expected to set up a network structure by using HUAWEI CLOUD’s basic services. This application will consist of VPC, VPC-Peering, ECS and RDS. 

### Step 1. Create three VPCs with different IP pool.
<img src="https://user-images.githubusercontent.com/71442681/204025525-69480359-a13a-4c44-a28f-df7df2d449d7.png" width="850" height="350">

### Step 2. Create a Secuirty Group and allow this security group for every incoming request.
<img src="https://user-images.githubusercontent.com/71442681/204025757-aa2e61cc-901d-4c15-92b8-9c2492495f95.png" width="850" height="350">

### Step 4. Create two ECS’, one in 1. VPC one in 2. VPC
<img src="https://user-images.githubusercontent.com/71442681/204026383-54791368-776c-4f47-a4c4-4b521b841961.png" width="850" height="350">

### Step 5. Create database (use RDS for mysql) in 3.VPC
<img src="https://user-images.githubusercontent.com/71442681/204027274-829aba12-ab34-4862-8749-7e7048ec4dea.png" width="850" height="350">

### Step 6. Use “Remote Login” for ECS’ and try to ping other ECS and RDS.
I tried. Could not ping at this step. It's taken to the next step.

### Step 7. Create VPC-Peering between 1.VPC-2.VPC, 1.VPC-3.VPC and 2.VPC-3.VPC
<img src="https://user-images.githubusercontent.com/71442681/204027720-b0df1b3b-dd24-47b3-95e9-ed4e3c85fc82.png" width="850" height="350">

### Step 8. Add routing rules to use VPC-Peerings.
<img src="https://user-images.githubusercontent.com/71442681/204027946-e9830c83-9534-4234-b926-86c488533e21.png" width="850" height="350">

### Step 9. Use “Remote Login” for ECS’ and try to ping other ECS and RDS again.
<img src="https://user-images.githubusercontent.com/71442681/204029800-fb71b88a-d17b-4fe7-a216-fda078b39f10.png" width="850" height="350">
</br>
<img src="https://user-images.githubusercontent.com/71442681/204029610-ba8d55df-3bb4-4bdf-8bed-4444f64e3885.png" width="850" height="350">

