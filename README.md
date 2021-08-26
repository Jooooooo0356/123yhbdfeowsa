# 123yhbdfeowsa

please add below values in the lambda_function.py

1. subnetid
2. acccountid
3. iamrole
  

  
-------------------------------------------------------------------------------------------------------------------------
How would you perform upgrade software deployed and minimise downtime
1.	Test the software after the upgrade too see any potential error is happened during and after the updates
2.	After the testing is done, create an second pipeline for the software upgrade (create new instances).
3.	Try to direct requests to the new instances from old version software
4.	After confirming everything is fine, all the requests have sent to new instance, terminate the old version instances.

How would you monitor this installation 
1.	monitor the performance during the upgrade
2.	Use Jenkins to see all the installation log, if failed, the job will be stopped. 
3.	Test after the installtion

How would you ensure security of this deployment 
1.	Set your deployment within your network (private network)

