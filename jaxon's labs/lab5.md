* NOTE: Deployment will take place in a namespace called **lab3**

### Create basic resources
- Create the specified Namespace
- Create a deployment nginx with 3 replicas
- Expose the deployment on port 80

### Create a CronJob for listing the EndPoints
1. Create a **serviceaccount** cronjob-sa
2. Create a Role that allows listing all the services and endpoints 
3. Link the Role with the created SA 
4. Create a CronJob that lists the endpoints in that namespace every minute and paste the output for the first pod created
5. After listing try to delete the 3 nginx pods ? again try to view the logs for the newly created pod for that cronJob what do you think happened ? 
