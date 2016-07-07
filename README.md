# AWS Hands-on Labs 1 to 6 - CloudAcademy

To begin with, the cloud academy website was visited and walked through the labs for AWS Certified Solutions Architect - Associate. The first 6 labs were completed sequentially understanding and designing distributed applications and systems on the AWS platform. 

Lab 1: Create Your First Amazon EC2 Instance (Linux)

To work in this lab an account was created in [Amazon Web Services][1] and then launched an EC2 instance. PUTTY needed to be installed for the experiment since an SSH client was necessary to convert the format of the key pair that was created and downloaded to authorize the instance. After successfully launching the instance was tested on the command line with its metadata and other useful commands such as security-group, hostname, ami-id, openssh-key etc.

Lab 2: Create Your First Amazon EC2 Instance (Windows)

Similar steps were followed to create a EC2 intance for Windows using AWS. Unlike on linux instance the instance was tested on Internet Explorer web browser of the built-in Remote Desktop Client.

Lab 3: Managing Instance Volumes Using EBS

This lab enabled learning to manage the storage space of your EC2 instance using Amazon EBS. When creating the EC2 instance an additional EBS volume was added to storage to achieve this. The choose the volume size, the volume type (Magnetic disk, SSD, or Provisioned IOPS), the termination policy, and an optional snapshot that will be restored during the creation process were given upon creation. Attaching and detaching volumes were experimented.

Lab 4: Create Your First Amazon S3 Bucket

This lab session allowed to understand AWS's secure, durable, and highly-scalable object storage which allows to store and retrieve any amount of data from anywhere on the web.

An S3 bucket was created from the Mangement Console giving it a name and was played around by createing and deleting folders and uploading images and changing properties of it.

Lab 5: Create an EBS-Backed Linux AMI

This dealt with creating a customized OS image through an Amazon Machine Image (AMI). nginX webserver had to be installed in addition for the experiment.

During this lab, a webserver EC2 instance was set up starting from a Linux AMI, and then generated a new AMI.

Lab 6: Create Your First Amazon RDS Database

An RDS Subnet Group was created by giving it a name for future use followed by the creation of a database cluster using RDS with MySQL selecting as the database engine. New rules were added to a VPC Security Group specifying the port, source, protocol and type.

Then the EC2 instance was launched and the remote shell was connected to using SSH commands. A connection to RDS was established using the Endpoint URL provided in the DB instance in AWS and a database was created. Queries were tested in tested and the DB instance was then deleted without creating a final snapshot to end the experiment.

**The complete demonstration of the lab experiments can be found in the link below**

[AWS Hands-on Labs 1 to 6 - CloudAcademy][2]


  [1]: http://aws.amazon.com/
  [2]: https://www.youtube.com/playlist?list=PL9bq521oLFulm5MeGf9FSl2hvpZ6zC6qc
