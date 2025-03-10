            

 <p>
    <img src="https://avatars.githubusercontent.com/u/6844498?s=200&v=4" height="20">
    <b>A GitHub Stack</b> to develop, preview, and deploy an Express(Node.js) website to Azure App service in seconds.
  
</p>


## Why should you use this GitHub template?
You can spin up your own Express(Node.js) website in seconds. Deployment happens on an Azure App Service.

The stack also sets up a proper Github CI/CD environment by taing care of the following things
1. Branch Naming convention - You can use any branch prefixed with "dev" as your development environment. 
2. Branch Protection Setting - Developers working on this branch can work freely and push changes without a PR and a code reviewer. This facilitates quick development. 
3. Enable Security alerts - A workflow will be setup for you to enable Dependabot alerts to detect vulnerabilities.
4. CodeQL Security Analysis - Discover vulnerabilities across a codebase with CodeQL, our industry-leading semantic code analysis engine

Note: Once you create a repo out of this stack, you can find your website deployed at <azure_app_name>.azurewebsites.net.

## What are the inputs to pass while setting up the template?
```
# Name of the Azure App which has been configured to host the website
- AZURE_APP_NAME

# Azure Publish profile
- AZURE_WEBAPP_PUBLISH_PROFILE
```

#### Github apps installed with this template
```None```

## How to get AZURE_WEBAPP_PUBLISH_PROFILE? 🔑
```
Login to your Azure Portal -> Open the Azure App Service -> Get publish profile
```
Check [this](https://docs.microsoft.com/en-us/visualstudio/azure/how-to-get-publish-profile-from-azure-app-service?view=vs-2022) out for more details on getting Publish Profile.

**Note**: You will have to create a Web app in your Azure Subscription and pass its name and publish profile as input. This stack will deploy the new repo code to your Azure Web app. Checkout this [Azure Documentation](https://docs.microsoft.com/en-us/azure/app-service/) to learn more about creating Azure App Service
## App hosted URL would be: ✈️

You can readily find the URL where your repo hosts the application in the `Development` environment. Or manually you can find your website deployed at <azure_app_name>.azurewebsites.net. 
```
Example: APP_NAME input by user is: sample-app
Hosted URL: https://sample-app.azurewebsites.net 
```

## How to setup local development server?
```
# to start a local development environment, and view in browser.
npm install
npm start
open http://localhost:3000 

# to run tests
npm test

# to generate a production build
npm build
```

## Learn more 

### ExpressJS
Visit [Expressjs.com](https://expressjs.com) to view the full documentation.

### Azure Cloud
Learn more about [Azure](https://docs.microsoft.com/en-us/azure) from the official site.


## Other Useful links

#### Security guide
Please see our guide lines for reporting issues related to [security.md](/.github/stacks/security.md).

#### Contributor guide
Please see our guide lines for [contributing.md](/.github/stacks/contributing.md).

## Contributors 
- Trilok Ramakrishna ([@3loka](https://twitter.com/3loka))
