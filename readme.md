<h1 align="center">
  <br>
  <img src="HoneywellLogo.png" width="500">
  <br>
VoiceConsole Next Generation - Rest API Automation Testing
  <br>
</h1>

<h4 align="center">This project is dedicated to develop and execute Automation Testing for API Implemented for Voice Console Next Generation.</h4>

<p align="center">
  <a href="#sparkles-key-features">Key Features</a> •
  <a href="#package-packages">Packages</a> •
  <a href="#engine-setup">Setup</a> •
</p>

## ✨ Key Features

- **Rest API Automation Framework** - The rest API Automation The original source can be found [here](https://bitbucket.honeywell.com/projects/VEST/repos/restapiautomation/browse)

## 📦 Packages

- **newman**

# ⚙️ Setup

To clone and run this application, you'll need the following:

- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org/en/download/)

To clone the repository should go to: [RestAPIAutomation](https://bitbucket.honeywell.com/projects/VEST/repos/restapiautomation/browse)
1. Go to the Clone Tab and copy the link provided
2. Open the terminal in your local machine and execute
```cmd
# Clone this repository
git clone [Link Provided]
```
3. Install all the Packages, Dev Dependencies and Dependencies needed
```cmd
npm install
```
# 🧪 ✨✅ Run Suite (Standalone API Module)

In order to run and specific test automated API module, in the `package.json` are allocated the scripts needed to run that specific module.
Example:
To run Roles Module, based on the scripts should be

#### Terminal

To check whether all requirements needed are installed to run the framework
```cmd
npm run roles
```

This command will execute the *Roles* Module  and once the test execution is done, **Newman** will generate a report 

# 🧪🔎 🧾✨ Reports

The framework is prepared to generate reports in 2 different formats; *.json* and *.html* each one with their respective dependency

To make sure to genereate the correct report, check the report flag of each script in the **pakage.json**

For **html** file will be

```cmd
-r htmlextra --reporter-htmlextra-export ./API/reports/html/*.html
```

For **json** will be

```cmd
-r json-summary --reporter-summary-json-export ./API/reports/json/*.json
```