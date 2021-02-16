# Template for electron.js app with an auto updator

> This example was made using the following article [this medium article](https://medium.com/@johndyer24/creating-and-deploying-an-auto-updating-electron-app-for-mac-and-windows-using-electron-builder-6a3982c0cee6)

## Project description

Creating a working template for an electron app with a working updator, for anyone to clone and use right away!

## Prerequisite:

> 1. Download [Node.js](https://nodejs.org/en/download/)
> 2. Download [Git-Bash](https://git-scm.com/downloads)
> 3. Download Yarn as global dependancy using the command npm install --global yarn
> 4. Need to have a [GitHub](https://github.com) account.
> 5. create an access token using your github account [Access Tokne](https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token).

## Build

> 1. Create your own repository to push your releases on. 
> 2. Clone the repository in your directory using the following command: 
    git clone https://github.com/Majd-Yahia/electron-auto-update-example.
> 3. Run command: npm init
> 4. Create an Enviroment variable using command: 
    [Environment]::SetEnvironmentVariable("GH_TOKEN","Your-Token","User").

> 5. Tweak the following sections in package.json: 
    >> name: replace it with your own project name or leave it as it is.
    >> version: set it back to 1.0.0 or to what ever version you want.
    >> description: replace with what descripes best your app.
    >> repository-url: https://github.com/Your_GitHub_Name/Your_Repository.git
    >> Also under build section you can change appID, productName, icon.

Now you are ready to, push the changes to your repository, then run the command npm run deploy.
> When its finished, you will find your deployable app in the repository in the release section, click on it, you will find your version 1.0.0 or what ever you have wrote it, stage it so it becomes the current release of your app.

Now make go back to your package.json and change the version to 1.0.1 or higher than what you wrote, push and deploy the app and dont forget to make it the current release.

## Test

Under releases click on the old release download the .exe file and run it, you should get a prompt message saying it needs an update.
All done!

## Todo

> 1. Adding Reactjs to the project.
> 2. Enhance the updator for better visuals.

## License
[MIT](https://opensource.org/licenses/mit-license)
