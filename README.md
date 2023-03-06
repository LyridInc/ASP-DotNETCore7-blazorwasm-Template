# ASP-DotNETCore7-blazorwasm-Template

## SAMPLE TEMPLATE
![hi](/dotnet5_asp.template/wwwroot/assets/img/lyrid_logo_large.png)
This template is for _language_ suitable for uploading to the Lyrid Platform.

## Prerequisites 
1. Register an account at [Lyrid Web Application](https://app.beta.lyrid.io/) 
2. Download our command line tool, [the lc](https://docs.lyrid.io/initialization)
3. Clone the repo 'git clone https://github.com/sample_here'

## Run locally with:
Test your application by building and running it with the following command:
```
dotnet restore .\dotnet5_asp.template\
dotnet run --project dotnet5_asp.template
```

### Edit 

## User can clone this repo, then Replace these variables in all files :
- YOUR_APP_NAME
- YOUR_MODULE_NAME
- YOUR_FUNCTION_NAME

## List of files :
- YOUR_APP_NAME -> .lyrid-definition.yml , Program.cs , entry.cs
- YOUR_MODULE_NAME -> .lyrid-definition.yml , Program.cs , entry.cs
- YOUR_FUNCTION_NAME -> .lyrid-definition.yml , Program.cs , entry.cs
- YOUR_APP_NAME.YOUR_MODULE_NAME.csproj <- replace the filename

To change your file information:
Open ```.lyrid-definition.YML``` file
Change ```name``` and ```module name``` to your choice and save.

### Start Coding!
Users can edit route url, settings, and views with custom APIs. 

### Submit to Lyrid 
Use our command line tool to easily upload your application to the cloud.
```
lc code submit
```

## Contact Us
Have any questions? We are here to help!
Email us at support@lyrid.io  

### Find us on social medias
- [Discord](https://discord.com/invite/xtCCtc9WAX)
- [LinkedIn](https://www.linkedin.com/company/lyrid/?viewAsMember=true)
- [Twitter](https://twitter.com/LyridInc)
- [Facebook](https://www.facebook.com/lyridinc)

<a href="https://app.lyrid.io/login?one-click-deploy=true&origin=github&repository-url=https://github.com/LyridInc/ASP-DotNETCore7-blazorwasm-Template.git&env=empty&project-type=ASP-DotNETCore7-blazorwasm&repo-name=ASP-DotNETCore7-blazorwasm-Template">
  <button>
    <img src="/dotnet5_asp.template/wwwroot/assets/svg/ocd_deploy_to_lyrid.svg" style="height: 50px; width:200px;"/>
  </button>
</a>