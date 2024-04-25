# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.


Analyze, choose, and justify the appropriate resource option for deploying the app.

1. Costs:

VM (Virtual Machine):
Cost includes VM instance cost, OS license cost (if applicable), storage cost, and data transfer cost.
The cost is relatively higher compared to App Service due to the need to manage and maintain the infrastructure.
Cost can vary based on the VM size, storage, and data transfer.
App Service:
Cost is relatively lower compared to VM as it abstracts away the infrastructure management.
You are charged based on the plan you choose (Basic, Standard, Premium) and any additional resources like storage and data transfer.
With the right scaling strategy, you can optimize costs by only paying for what you use.
2. Scalability:

VM (Virtual Machine):
Vertical scaling (increasing VM size) or horizontal scaling (adding more VM instances) is possible but requires manual intervention.
Scalability is limited by the capacity of the VM or the number of VMs you can afford.
App Service:
Offers automatic scaling based on demand.
Horizontal scaling is seamless and managed by Azure.
Provides better scalability options compared to VMs, especially for applications with fluctuating traffic.
3. Availability:

VM (Virtual Machine):
You are responsible for configuring high availability if needed.
Availability depends on how well you configure and manage the VMs.
App Service:
Azure App Service offers built-in high availability.
Microsoft manages and ensures high availability of the platform, including automatic OS and runtime patches.
4. Workflow:

VM (Virtual Machine):
Requires more setup time for configuring VMs, installing necessary software, managing updates, and maintaining security.
DevOps and deployment processes are typically more involved.
App Service:
Provides easier deployment and management with integration into CI/CD pipelines.
Simplified deployment processes compared to VMs, enabling faster time-to-market.
Choice:

Considering the analysis above, for deploying the CMS app, the appropriate solution would be Azure App Service. Here's why:

Costs: App Service is generally more cost-effective than VMs due to its managed nature and pay-as-you-go pricing model.
Scalability: App Service offers automatic scaling, which is more efficient and seamless compared to managing VMs manually.
Availability: App Service provides built-in high availability, reducing the need for manual configuration and ensuring better uptime.
Workflow: App Service simplifies the deployment and management process, allowing for faster deployment and easier integration into CI/CD pipelines.
Overall, Azure App Service provides a more efficient, cost-effective, and easier-to-manage solution for deploying the CMS app compared to VMs.

Assess app changes that would change your decision
Changes in the application or business requirements could lead us to reconsider the decision to use Azure App Service. Such changes might include: Full Control Over OS and Middleware, Compliance with Legacy Systems, Custom Software Dependencies
