# Developer Kickstart Module 4: DML Operations

This repository is part of the Developer Kickstart Module 4 curriculum at Cloud Code Academy. It's designed to help beginner Salesforce developers learn and practice the fundamental operations of the Data Manipulation Language (DML) in Apex. The focus is on the Insert, Update, Upsert, and Delete operations, all of which are essential in manipulating Salesforce data.

## Goals of the Practice
Through this practice repository, you'll gain foundational knowledge about:
- Understanding the different types of DML operations in Apex (Insert, Update, Upsert, and Delete).
- How to use DML operations to create, update, and delete records in Salesforce.
- The structure and usage of Salesforce standard objects like Account, Contact, Opportunity, and Lead.
- How to handle bulk data operations in Apex.
- Understanding the concept of governor limits in Salesforce and how to write efficient, bulkified Apex code.

This foundational knowledge will prepare you for more advanced topics in Salesforce development, such as exception handling, asynchronous Apex, and trigger development. The curriculum includes practical examples with Salesforce standard objects to provide hands-on experience with DML operations.
## Note
Certain test methods related to the Book and Person classes are currently commented out and will need to be uncommented and deployed once the relevant classes are set up.

## Setup
[Setup Overview](https://learn.cloudcodeacademy.com/courses/salesforce-developer-kickstart-program/lectures/47317682)

## Setup Checklist
1. Create/Configure a trailhead playground or developer org to do your work throughout this program.
2. Install Visual Studio Code from [here](https://code.visualstudio.com/download).
3. Install Salesforce Extension Pack in Visual Studio Code. This can be done by searching 'Salesforce Extension Pack' in the Extensions view in VS Code and clicking Install.
4. Authorize your org in Visual Studio Code. Press `Ctrl/Cmd + Shift + P` to open the command palette and type 'SFDX: Authorize an Org', then press Enter. Follow the steps in the browser to log in to your org, then return to VS Code.
5. Save and deploy your changes into Salesforce from your local machine. This can be done through the command pallet or right-clicking the file you want to deploy and using the option `SFDX: Deploy this source to org`

## Getting Started
1. Navigate to the folder force-app/main/default/ and deploy the metadata to your Salesforce org. Right-click on the folder and select `SFDX: Deploy Source to Org`.
2. Review the files provided including the test class to understand the challenges.
3. Update the code and deploy it to your Salesforce org.
4. Run the test class to validate your code. Use `Ctrl/Cmd + Shift + P` to open the command palette and type 'SFDX: Run Apex Tests', then press Enter. You can also use `Run All Test` or `Run Test` on the test class.
5. Push your changes to your GitHub repository and submit the link to the assignment in the submission form in Slack.

## Resources

If you get stuck at any point, here are some resources that might help:

- [Apex Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_dev_guide.htm)
- [Salesforce Stack Exchange](https://salesforce.stackexchange.com/)
- [Visual Studio Code Documentation](https://code.visualstudio.com/docs)
- [Salesforce Extensions for Visual Studio Code](https://developer.salesforce.com/tools/vscode/)

And remember, programming is often about solving problems, so don't be afraid to use search engines to find answers to your questions.

Good luck with your learning journey in Salesforce development!
