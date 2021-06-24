# Integrate Azure functions with Azure KeyVault

## Intro

Hi everyone, today I'm going to show you how to integrate Azure Functions with Azure KeyVault, I'm going to try and keep it short and straight to the point, let's go.

## Demo

Alrighty, let's [create an azure function in visual code[], I'll click on the azure function extension, next I'll select the folder icon to create a new function project, select my current folder, and I'll leave all the default settings for now, they don't matter much for this video.

Okay, our function is now created, let's now talk about [What is local.settings.json] when we're working locally on a .NET function, this file is where we can store our environment variables. Keep in mind, that this file doesn't get push to production, for good reason. Functions have their own place to configure application settings in production, and to add to that security, we can use keyvault to store those secrets.

3. Deploy function to Azure
4. setting up KeyVault in the Azure Portal
5. Create a new secret in KeyVault via the Azure Portal
6. Configure Function settings in Azure Portal
7. Configure KeyVault Access policy
8.  How to update a KeyVault secret value

## Conclusion

and that's it. We've integrated Azure KeyVault with Azure Functions to better secure our application settings with secrets. Thank you for watching, stay tuned for some more Functions videos, see you in the next one. 

## Resources

- [Use Key Vault references for App Service and Azure Functions](https://docs.microsoft.com/azure/app-service/app-service-key-vault-references)
- [Azure Key Vault basic concepts](https://docs.microsoft.com/en-us/azure/key-vault/general/basic-concepts)