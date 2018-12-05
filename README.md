# Amazon EC2
Amazon Elastic Compute Cloud (Amazon EC2)
Create a amazon account 
On Amazon Console go to Amazon EC2

## Creating a Virtual Machine
On EC2 Dashboard -> Launch Instance
 - Step 1: Choose an Amazon Machine Image (AMI)
I select Amazon Linux AMI 2018.03.0 (HVM), SSD Volume Type 
 - Step 2: Choose an Instance Type
click on Review and Launch
 - Step 7: Review Instance Launch
Click on Launch
Create a new Key Pair download it and click in Lauch Instances
Done!!
a good video showing how (https://www.youtube.com/watch?v=SKM0BB0F02Q)

## Connect To Amazon EC2 With PuTTY On Windows
First download Putty.exe and puttygen.exe (https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)
Run puttygen.exe then click and Load -> choose your Key Pair -> save private Key
run Putty.exe insert ip add of your istance 
(On EC2 Dashboard -> Instances -> Connect -> item Connect to your instance using its Public DNS)
on Conection -> data inser the user "ec2-user"
on SSH ->Auth choose the .ppk file that u just create
return on sessio chose a name and save
Done!!



