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

* [Salesforce Platform Basics](https://trailhead.salesforce.com/content/learn/modules/starting_force_com)
    - [Create a Salesforce Object](https://trailhead.salesforce.com/content/learn/projects/customize-a-salesforce-object)
    - [Data Modeling Basics](https://trailhead.salesforce.com/content/learn/modules/data_modeling)
    - [Using Formulas and Validations](https://trailhead.salesforce.com/content/learn/modules/point_click_business_logic)
* [Salesforce Multi-tenant Concepts and Framework]()
    - [Multi-tenant Concept](https://trailhead.salesforce.com/content/learn/modules/starting_force_com/starting_understanding_arch)
    - [Lightning Experience Basics](https://trailhead.salesforce.com/content/learn/modules/lex_migration_introduction)
    - [Lightning Experience Features](https://trailhead.salesforce.com/content/learn/modules/lex_migration_whatsnew)
    - [Lightning Experience Customization](https://trailhead.salesforce.com/content/learn/modules/lex_customization?trail_id=lex_admin_implementation)
    - [Lightning Experience Development](https://trailhead.salesforce.com/content/learn/modules/lex_dev_overview?trail_id=lex_dev)
    
    - [Lightning App Builder](https://trailhead.salesforce.com/content/learn/modules/lightning_app_builder)
    - [What is the Lightning Component Framework?](https://developer.salesforce.com/docs/atlas.en-us.206.0.lightning.meta/lightning/intro_framework.html)


* [Model View Controller Architecture](https://shreysharma.com/mvc-architecture/)
    - [MVC Architecture in Salesforce](https://youtu.be/_n365oEeMwg)
* [Quick Start: Apex](https://trailhead.salesforce.com/content/learn/projects/quickstart-apex)
    - [Apex Basics and Database](https://trailhead.salesforce.com/content/learn/modules/apex_database)
    - [Database & .NET Basics](https://trailhead.salesforce.com/content/learn/modules/database_basics_dotnet)
    - [Data Security](https://trailhead.salesforce.com/content/learn/modules/data_security)
    - [Apex Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_intro_what_is_apex.htm)
    - Object Orientated Design with Apex
* [Governor Limits](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_gov_limits.htm)
    - [Per-Transaction Apex Limits](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_gov_limits.htm#in_topic_per_transaction_section)
    - [Set up Governor Limit Email Warnings](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_gov_limits_emails.htm)
    - [Running Apex Within Governor Execution Limits](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_limits_tips.htm)
    - Governor Limits Quiz


* [Clicks vs Code Scenarios](https://help.salesforce.com/s/articleView?id=sf.process_which_tool.htm&type=5)
    - [Flow Basics](https://trailhead.salesforce.com/content/learn/modules/flow-basics) 
    - Invoking Apex Code From Flows
    - Submitting a record for approval
    - Sendng an email alert
    - Launching another flow
    - Sending an outbound message
* [Salesforce Datamodeling](https://developer.salesforce.com/docs/atlas.en-us.object_reference.meta/object_reference/data_model.htm)
    - Samples
    - Samples
* [Salesforce Datamodeling Relationships]()
    - Samples
    - Samples
    - External Ids
    - Advanced Relationships
* [Importing and Exporting Data](https://trailhead.salesforce.com/content/learn/projects/import-and-export-with-data-management-tools)
    - [Data Loader](https://developer.salesforce.com/docs/atlas.en-us.dataLoader.meta/dataLoader/data_loader.htm)
* Important Apex Classes
    - [Schema Class](https://developer.salesforce.com/docs/atlas.en-us.apexref.meta/apexref/apex_methods_system_schema.htm)
    - [Database Class](https://developer.salesforce.com/docs/atlas.en-us.apexref.meta/apexref/apex_methods_system_database.htm)
    - [Metadata Class](https://developer.salesforce.com/docs/atlas.en-us.apexref.meta/apexref/apex_class_Metadata_Metadata.htm)
    - [System Class](https://developer.salesforce.com/docs/atlas.en-us.apexref.meta/apexref/apex_namespace_System.htm)
    - [SObject Class](https://developer.salesforce.com/docs/atlas.en-us.apexref.meta/apexref/apex_methods_system_sobject.htm)
    - Note the exam tests on how to use various important Apex classes the above are just some of the few.

* [Platform Events](https://trailhead.salesforce.com/content/learn/modules/platform_events_basics)
    - [Build an Instant Notification App](https://trailhead.salesforce.com/content/learn/projects/workshop-platform-events)

* [Dealing with Metadata](https://trailhead.salesforce.com/content/learn/modules/custom_metadata_types_dec)
    - [Programmatic Development with Custom Metadata Types](https://trailhead.salesforce.com/content/learn/modules/custom_metadata_types_adv)



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
