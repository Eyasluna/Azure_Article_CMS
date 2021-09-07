# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

For App Service: It has high availability, auto-scaling and support of both Linux and Windows environments. The cost would be always paying for the service plan, even if the services or application isn’t running. But it has continuous deployment model by using GitHub, Azure DevOps, or any Git repo. However, it has limited access to the host server so user unable to control the underlying OS or install software on the server.

For VM: It allows user for full access and control of it and support both Linus and Windows. It can be grouped to provide high availability, scalability, and redundancy. However, it more expensive but still lower up-fornt cost compared to purchase and maintaining hardware. 

For the choice of mine would be App Service. Since this project is more lightweight to be well-suited to App Service over VM, it won't approach the size limit for App Service very easily. Additionally, App Services cost less than VMs do. Lastly, since the ability to scale quickly is less of a concern, we don't need to factor that into the analysis.

## URL to this App Service:
## http://cms-article.azurewebsites.net/