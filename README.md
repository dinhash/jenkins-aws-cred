# jenkins-aws-cred
Repo consists info on integration issue on jenkins and aws credentials

When obtained an error while executing aws cli commands as jenkins as "Jenkins unable to locate credentials"


Issue:
  The AWS credentials are not configured for the jenkins user

Perform following steps:
  1 - Switch user to root
  $sudo su root
  
  2 - Switch user to jenkins (user that which jenkins uses to execute shell)
  $sudo su jenkins
  
  3 - Configure aws credentials
  $aws configure

