# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

For App Service: It has high availability, auto-scaling and support of both Linux and Windows environments. The cost would be always paying for the service plan, even if the services or application isn’t running. But it has continuous deployment model by using GitHub, Azure DevOps, or any Git repo. However, it has limited access to the host server so user unable to control the underlying OS or install software on the server.Since the costs, scalability and availability for this CMS deployed through the App Service is reasonable. Sicne user can pay less when no none is using the service and the reduced compute requirements of this app are not expensive. continous deployment through GitHub workflows on Azure portal makes the updating this app much more easiler. 

For VM: It allows user for full access and control of it and support both Linus and Windows. It can be grouped to provide high availability, scalability, and redundancy. And it allows for more customization of the app's capability while the cost, scalability, and availability for a CMS app deployed through a VM are also reasonable. However, it more expensive but still lower up-fornt cost compared to purchase and maintaining hardware. 

For the choice of mine would be App Service. Since this project is more lightweight to be well-suited to App Service over VM, it won't approach the size limit for App Service very easily. Additionally, App Services cost less than VMs do. Lastly, since the ability to scale quickly is less of a concern, we don't need to factor that into the analysis.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

APP Service:
When the CMS app needed to be updated to allow for more compute capability like video playing or images editing which may require more hardware, the costs could rise quickly. Meanwhile if there is any functionality desired which not supported by Azure could be a roadblock. Being unable to control the underlying software on the
server could also cause significant issues that could break your app.

VM:
If this CMS became more popular, it could become more expensive due to requiring more hardware/compute power. New developer coming onboard would requires to understandthe details the VM has been customized which may make the onboarding process longer. Also, if the CMS needed more compute capability, it could also become significantly more expensive.

## URL to this App Service:
## http://cms-article.azurewebsites.net/