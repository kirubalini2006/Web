Step 1: Create a Static Web App
Search for "Static Web Apps" in the Azure Portal search bar and select it.
Click Create to start the creation process.
Step 2: Configure the Static Web App
In the Create Static Web App wizard, follow these steps:

Subscription: Select your Azure subscription (if you have multiple).
Resource Group:
Either select an existing resource group or click Create new to create a new one.
Name:
Choose a unique name for your Static Web App (this will be part of the URL). For example: my-static-web-app-2024.
The name must be globally unique as it will be part of the URL: https://<your-web-app-name>.azurewebsites.net.
Region:
Select a region that is closest to your users or where you want your app to be hosted.
Deployment Details:
Deployment Source: Choose GitHub (for automatic deployment via GitHub) or Local Git (if you prefer to deploy manually from your local system).
If using GitHub: You will be asked to authenticate with your GitHub account and choose the repository where your code is stored. If you don't have a repository, you can create one with your static website files.
If using Local Git: You will get a Git URL that you can push your code to.
Build Details:
Build Presets: Since this is a simple static app with no build steps, you can choose Custom. Alternatively, if using frameworks like React, Angular, or Vue, select the appropriate preset (e.g., React).
App Artifact Location: Set this to / (the root folder) since you don't have any build artifacts to specify for a simple static site.
Step 3: Review and Create
Review your settings.
Click Create to create your static web app.
