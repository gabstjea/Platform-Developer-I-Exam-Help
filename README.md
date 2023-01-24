# Platform-Developer-I-Exam-Help

This guide is meant to help individuals studying for the Platform Developer I Exam. This guide assumes the following:

- Familiar with Salesforce ecosystem.
- Have set up your trailhead account. 
- Have VSCode Salesforce Extensions
- Have the Salesforce CLI Installed
- Have JDK version 17(Recommended),11,or 8


The Guide contains the following:

- We have set up a developer org folder which contains code samples on building in Salesforce. 

- We have set up additional notes and topic explanations through code and diagrams.

- We have set up links to trailheads and other Salesforce documentation as you go through the repository to understand the material. 



## Pre-work

The exam is broken down to concepts by Salesforce. We have further broken the exam down to subtopics we feel are important to know to prepare for the exam. Understanding the concepts and how topics interact with each other will best prepare you for the exam. Doing while learning is always the best way to learn. 

We recommend on creating your own developer org and work on these topics locally on your machine. 

0. Create a Developer Org: [link](https://developer.salesforce.com/signup)

1. To clone this repository locally:

```bash
git clone https://github.com/gabstjea/Platform-Developer-I-Exam-Help.git
```

2. Once on the main branch create your git branch

```bash
git branch <my-branch-name>
```

3. Next checkout your created branch

```bash
git checkout <my-branch-name>
```

4. Now that you are on your own branch created. We can create our own Salesforce DX project.

```bash
sfdx force:project:create --projectname myDeveloperOrg --manifest
```

- The command above will create a Salesforce DX Project. Here is the link to additional information about the command: [link](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference_force_project.htm#cli_reference_force_project_create)

5. Now go inside the Salesforce DX project. When inside open up a new VSCode page. This will open up a new VSCode page so we can be at the root of the Salesforce DX project and the Salesforce extensions gets activated.

```bash
code .
```

6. Once the Salesforce extensions get activated we can connect to the developer org you created at step 0.


- ```COMMAND + SHIFT + P on MAC``` - will open Command Palette

- ```CTRL + SHIFT + P ON WINDOWS``` - will open Command Palette.

-  ```Type and select: SFDX: Authorize an Org```

- ```Select Project Default Login```

- ```Name Org Whatever you would like```

- ```Enter Org Credentials```


If you run until any issues authorizing an org to your local environment please refer to this trailhead: [link](https://trailhead.salesforce.com/content/learn/projects/quickstart-vscode-salesforce/use-vscode-for-salesforce#:~:text=S%20(macOS).-,Authenticate%20to%20Your%20Playground,default%20login%20URL%2C%20press%20Enter.)


## Developer Fundamentals: 23%

* [Salesforce Multi-tenant Concepts and Framework]()
* [Model View Controller Architecture]()
* [Lightning Component Framework]()
* [Governor Limits]()
* [Clicks vs Code Scenarios]()
* [Salesforce Datamodeling]()
* [Salesforce Datamodeling Relationships]()
* [Importing and Exporting Data]()
* [Important Apex Classes]()
* [Dealing with Metadata]()


## Process Automation and Logic: 30%
* [Flow Builder](./resources/ProcessAutomationAndLogic/Flow.txt)
* [SOQL](./resources/ProcessAutomationAndLogic/SOQL.txt)
* [SOSL](./resources/ProcessAutomationAndLogic/SOSL.txt)
* [DML](./resources/ProcessAutomationAndLogic/DML.txt)
* [Apex classes](./resources/ProcessAutomationAndLogic/ApexClasses.txt)
* [Apex triggers](./resources/ProcessAutomationAndLogic/ApexTriggers.txt)

## User Interface: 25%

* [Visualforce Pages]()
* [Lightning Component Frameworks]()
* [Data Security consideration when building UI]()
* [Lightning Components]()
* [Using Flows for UI]()
* [Aura Components]()
* [Lightning Web Components]()
* [Implementing Apex with different UI Salesforce frameworks]()


## Test, Debugging, and Deployment: 22%
* [Apex testing](./resources/TestAndDebugging/ApexTesting.txt)
* [Debug logs](./resources/TestAndDebugging/DebugLogs.txt)
* [Code Deployment](./resources/TestAndDebugging/Deployment.txt)
