# Deploy-a-High-Availability-Web-App-Using-Cloud-Formation
I deployed a high availability web server for a high availability web app using cloud formation. I created an Infrastructure as a code script that creates, deploys and give the possibility the auto delete the infrastructure and application.

### Diagram as a Service ###
![Second Project](https://user-images.githubusercontent.com/49678841/178487290-7888f583-674e-4a32-bc21-f8ec0766c301.png)

### Attached files ###

```
* Udagram App : Udagram App Code (Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function etc ...)
* Create.sh : Cloudformation create stack script. 
* Update.sh : Cloudformation update stack script.
* UdagramApp.yml: Udagram Project's CloudFormation script.
* UdagramServers.json : Udagram Project's CloudFormation script parameters. 
* Images-of-result-deploy : Screenshot the result of deploy.
```

### Connecting to the EC2 Instance via Bastion host for troubleshooting purpose ###
I made deployed Bastion Host as part of the resource to allow me connect to the instance for troubleshooting purpose in the private subnet using the SSH agent. This would allows me to connect to the other instance from the Bastion and also avoid stroing the private key on the Bastion Template. The SSH agent is a service that keeps track of the user identity keys.

