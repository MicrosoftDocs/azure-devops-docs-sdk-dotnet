## .NET SDK for Azure DevOps
[![Build Status](https://apidrop.visualstudio.com/Content%20CI/_apis/build/status/PROD/GitHub_MicrosoftDocs_azure-devops-docs-sdk-dotnet/9bc0bbde-bfc4-adc2-75d5-c487f466b459_master_Microsoft.VisualStudio.Services.ExtensionManagement.WebApi)](https://apidrop.visualstudio.com/Content%20CI/_build/latest?definitionId=1438)

This repository contains C# samples that show you how to integrate with Azure DevOps using our [public client libraries](https://www.nuget.org/profiles/nugetvss). 

## About our client libraries
For .NET developers, the primary (and highly recommended) way to integrate with Azure DevOps and Team Foundation Server is via our public .NET client libraries available on Nuget. [Microsoft.TeamFoundationServer.Client](https://www.nuget.org/packages/Microsoft.TeamFoundationServer.Client) is the most popular Nuget package and contains clients for interacting with work item tracking, Git, version control, build, release management and other services.

See the [Azure DevOps client library documentation](https://docs.microsoft.com/en-us/azure/devops/integrate/concepts/dotnet-client-libraries?view=vsts) for more details.

## Sample SDK Entry
Build.Definition Property

```
[System.Runtime.Serialization.DataMember(EmitDefaultValue=false)]
[set: System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)]
public Microsoft.TeamFoundation.Build.WebApi.DefinitionReference Definition { get; set; }
```
You can search for more Azure DevOps namespaces via the [.NET API Browser](https://docs.microsoft.com/en-us/dotnet/api/?term=azure).

## Microsoft Open Source Code of Conduct
This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Something missing from the SDK?
Let us know by opening an issue on the [Azure DevOps developer community](https://developercommunity.visualstudio.com/spaces/21/index.html).
