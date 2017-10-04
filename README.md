# ansible-role-aws-cloud
ansible-role-aws-cloud


#### EC2 Instance Spec
ec2_os: centos7
ec2_security_group: toolbox
ec2_exact_count: 1
ec2_boot_disk_volume_size: 30

ec2_instance_tags:
  Name: toolbox
  Class: frontend
  Version: static
  Environment: staging

ec2_security_ports:
  - 22
  - 80
  - 443
