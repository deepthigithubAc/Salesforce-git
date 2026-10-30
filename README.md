# Salesforce-git

 
hi Shaw, Aman..PFB questions asked in the interview - How to communicate between components in LWC
1.	Publish , subscribe parameters in LWC
2.	Apex design pattern
3.	Integration , ways and 1000 lead records coming from data loader how we can send 1000 lead records to external system , what is the approach
4.	Platform Events (Parameters)
5.	Publish subscribe model in LWC , what are parameters
6.	How to publish and subscribe events in class
7.	What is replay id , UUID
8.	Write a trigger where if the sum of the amount of all Opportunity Line Items is more than 5000, provide an additional discount of 10% and deduct the discount amount from total amount on opportunity. And display on Opportunity detail page where field name Total Amount(Custom field) after discount.
9.	Named credentials – what is outbound network connection
10.	Integration – REST API Methods


=================================================================
1. Explain how we pass data in LWC.
11.	Different Parameters in Custom Event
12.	How we can handle error in LWC
13.	How you can establish Integration with REST API
14.	async wait and promise
15.	different methods of promise 
16.	named credential vs connected app
17.	Have you worked on CPQ
18.	Write a trigger where if the sum of the amount of all Opportunity Line Items is more than 5000, provide an additional discount of 10% and deduct the discount amount from total amount on opportunity. And display on Opportunity detail page where field name Total Amount(Custom field) after discount



difference between wire and connectedCallBack
Can we perform DML operations in wire and connectedCallBack
we have comp A and Comp B and comp C can we handle to call comp c to comp A directly?
Write a SOQL query to retrieve all accounts with more than 10 contacts
Write an Apex Trigger to prevent inserting duplicate Account records based on the Account.Name field.

-----------------------------------------------------------------------------------------------------------------
I have done with my interview, Please find the below questions covered in interview
1.introduce Ur self
2.howmany clouds you have worked on
3.How frequently you will write code
4.Communication between the components
5.A-B-C---How you will communicate from C to A and Why you use bubbles,  composed?
by default what is the value of bubbles and composed
6.EMP API? what are the parameters will use in this
7.LMS and parameters in LMS
8.Experience cloud
9.If you are on the Contact record page and, in the Related section, there are Tasks. At the bottom of the page, we have a custom LWC that displays data in a data table. Whenever a new Task is created, the datatable in the LWC is not updating automatically and only shows the latest data after a page refresh. How can we update the datatable without refreshing the page?
10.CPQ related questions like product feature and options
 
======================================================================


1.introduce yourself
2. exp in which cloud
3.exp in datable lwc
4.what is context variable used in trigger.undelete and trigger.delete
5.exp in experience cloud
6.exp in Cpq
7.if lead i have passed entire data with help of future method from trigger how to do it not full 200 records
8.default size of batch what is min size and max size in batch ?
9. what are design pattern in apex ?
10.explain singleton design pattern?
 
1.	cloud experience?
2.	standard fields in platform event , what are -1 and -2 values in that
3.	bubbles, composed
4.	multiple try is allowed? multiple catch is allowed?
5.	how to get data from apex to lwc ?
6.	promise, await async differences
7.	wire and imperative difference
8.	UUID , replay ID
9.	Write a trigger where if the sum of the amount of all Opportunity Line Items is more than 5000, provide an additional discount of 10% and deduct the discount amount from total amount on opportunity. And display on Opportunity detail page where field name Total Amount(Custom field) after discount
 1. Custom permission.
2.Assingement Rule.
3.Batch vs future vs Queue.
4.Field level security
5.LWC lifecycle
6.Promiss
7.Component A->B->C how to pass data C ->A.
8.Outbound & Inbound Integration.
9.Security model & with sharing without sharing.
10.Query Accounts that have Contacts and Opportunities.







1)I have two Salesforce users, User A and User B, who have access to an account with 100 records. When they log in, User A sees 20 records while User B sees 40 records. What could be the reason for this difference?
2)I want to share User A's account record with Users B and C based on ownership. How can I do this?
3)I want to share access of User A's account record with six or seven other users. How can I do that?
4)I have a manager who can access subordinate account records. How can I restrict the access to view these records?
5)I have an Account with a field named "ContactEmail" and a related Contact that has a "ContactEmail" checkbox. Whenever a Contact record is inserted, updated, deleted, or undeleted and the checkbox is checked, I want to update the associated Account's "ContactEmail" field with the Contact's email. Additionally, whenever the Account's "ContactEmail" field is updated, that specific value should be updated to the primary Contact's email field.
6)how to bypass validation for a user?
7)Suppose I have 1000 users, and I can't bypass the validation using custom permissions. How can I achieve this?
8)What are the main differences between custom settings and custom metadata?
9)How can recursion in a trigger be handled without using a Boolean variable?
10)explain decorates in lwc?
11)difference between visual force page, aura and lwc?
12) is lwc one way or two way binding?
13)Can you explain event propagation in LWC, including the bubbling and capturing phases?
14)How can data be passed in LWC between parent and child components, child to parent components, and unrelated components?

1)I have two Salesforce users, User A and User B, who have access to an account with 100 records. When they log in, User A sees 20 records while User B sees 40 records. What could be the reason for this difference?
2)I want to share User A's account record with Users B and C based on ownership. How can I do this?
3)I want to share access of User A's account record with six or seven other users. How can I do that?
4)I have a manager who can access subordinate account records. How can I restrict the access to view these records?
5)I have an Account with a field named "ContactEmail" and a related Contact that has a "ContactEmail" checkbox. Whenever a Contact record is inserted, updated, deleted, or undeleted and the checkbox is checked, I want to update the associated Account's "ContactEmail" field with the Contact's email. Additionally, whenever the Account's "ContactEmail" field is updated, that specific value should be updated to the primary Contact's email field.
6)how to bypass validation for a user?
7)Suppose I have 1000 users, and I can't bypass the validation using custom permissions. How can I achieve this?
8)What are the main differences between custom settings and custom metadata?
9)How can recursion in a trigger be handled without using a Boolean variable?
10)explain decorates in lwc?
11)difference between visual force page, aura and lwc?
12) is lwc one way or two way binding?
13)Can you explain event propagation in LWC, including the bubbling and capturing phases?
14)How can data be passed in LWC between parent and child components, child to parent components, and unrelated components?

1)Please write SOQL which will retrieve all the information from below object where Organization Name = "Global Payments"
Organization__c : Organization Name, Company Information, Revenue
Project : Name, Budget, Organization__c
Timesheet : Name, Approval,Project__c


2)Need to write a trigger for the below scenario
Pancard__C custom object which is having master detailn with COntact
when user tries to create more than one pancard for contact then through an error.

3) Some other basic SOQL Queries

4) If we get any errors in the flow is there any specific place to store those errors.

5) In a batch class on opportunity if some records failed to process then need to send an email to the opportunity owner with failed records details how to do that?

6) some trigger scenarios and context variables
7) some other basic questions on flows and its types
8) How to handle the errors in LWC
9) Life cycle hooks in LWC
10) difference between connected app and named credentials

11) if there is any error in call out then what are the steps need to look into?
12) Some other basic questions on admin
13)How to bypass recursive trigger.
 
 
 
- If a user has Read access in their profile and the OWD is set to Public Read/Write, what level of record access will they have?
- Is it possible to restrict access to records via the role hierarchy in Salesforce?
- Can we define a class as private in Apex?
- Can we call a @future method from a Batch Apex class, and what is the default batch size?
- Is it allowed to invoke a @future method from another @future method?
- Can we call a @future method from an Apex Trigger, and is it considered a best practice?
- How can one Batch Apex class invoke another Batch Apex class?
- How do you send an email to a manager regarding failed records from a Batch Apex execution?
- What are static methods in Apex, and in what scenarios should we use them?
- How do you invoke an Apex class from a Flow, and why might a specific Apex class not be appearing in the Flow's action list?
- In a parent-to-child trigger scenario, how can we ensure only one unique Contact is linked to an Account, and raise a validation error if more than one    exists?
- What are the ways to pass data from a parent record to its related child records?
- What are the lifecycle hooks in Lightning Web Components (LWC), and why are they important?
- How can data be passed from a child component to its grandparent component in LWC?
- What is the difference between renderedCallback() and connectedCallback() in LWC?
- What are the best practices for handling errors in Salesforce Flows?

What is the difference between @api, @track, and @wire in LWC?
How do you pass data from parent to child and child to parent in LWC?
Explain lifecycle hooks in LWC
How do you share data between unrelated components in LWC?
Can you call multiple Apex methods in a single LWC? How do you manage it?
What is the difference between renderedCallback and connectedCallback?

1)I have two Salesforce users, User A and User B, who have access to an account with 100 records. When they log in, User A sees 20 records while User B sees 40 records. What could be the reason for this difference?
2)I want to share User A's account record with Users B and C based on ownership. How can I do this?
3)I want to share access of User A's account record with six or seven other users. How can I do that?
4)I have a manager who can access subordinate account records. How can I restrict the access to view these records?
 
 
Amit – 
User - Object
Department - Sales
CPQ - Premission Set

trigger allowPremission on User(after insert){
    Id psId = [Select Id,assigneeId from permissionSetAssignment where Name = 'CPQ'];
    List<permissionSetAssignment> pAU = new List<permissionSetAssignment>();
    for(User u: Trigger.new){
        permissionSetAssignment ps = new permissionSetAssignment();
        ps.AssigneeId = u.Id;
        ps.PermissionSetId = psId.Id;
        pAU.add(ps);
    }
    insert pAU;
}

1.Can we call Future apex from Batch apex and vice versa 
2.Can we call Future apex from Triggers 
3.Trigger scenario based coding question 
4.Trigger.old in after undelete context 
5.Trigger.newMap in after undelete context

Subhradeep Basu-
1. What you have done hands on in Salesforce CPQ ---> Asked him about te architecture and then process to create teh Quotes by using QLE, told the CPQ architecture , How we are using Pricebooks and adding it to Products. 
2. Diff between Product Option and Product Feature. --- ( He will trying to confuse here.) 
3. We are having product option but why we still use Product Bundle. 
4. What do you know by Revenue cloud. 
5. What is  Data Capture and how you have used it?  -- CDC 
6. Tell me the scenarios where you have used CDC & Platform Event. 
7.

Suppose there are a Trigger written on Lead object, I want to call a Future method from that and from that Future one Batch is calling and we need to do the Callout. Trigger is sending 1000 records at one but we need to process only 100 records at once. Data Loader is used here to load the data.

Told him the ebelow approaches -

1st Approch 
-------------- 
Data Loader ----> Trigger ---> Handler ---> Calling batch direct (not req Future as both Async) --> Passed 100 batch size ---> Execute() do the callout.

Problem > for each record callout will be done, easily reach the governor limit.

2nd Approch 
-----------

Data Loader ---> Trigger ---> Handler (Collecting the Lead IDs in List) --> Passing them to Queueable---> Loop the List--> after loop do the callout.

He was asking how we can maintain 200 records in each callout, told him , With limit we can manage that for first 200 records in queueable but next records I need to check how we can do that technically.


8. What Is UUID in Platform event. 
9. What is refresh EMP id? 
10. What is replay id. 
11. How we can call Child method from parent. 
12. Hiererchy-- A---> B ---c   , wanted to send data from C to A directly, how we can do --> Bubble event. 
14. How frequently you write code--> Told I am not memorizing the code , always using AI tools to get the code and then solve the issues..it will save our time. 

15 . Suppose there are few fields which we need to visible according Country value ---> Edit Page ---> component filter. 
16. He asked then we need to do something on LWC level how to do that. --> Import 2 HTML --> with ternery operator we can apply. 
17. There are separate style we need to use in diff components..how can we do that..--> I told him custom CSS. 
18. Asked if we can use multiple CSS file in one LWC --> I told not sure, never tried. 
    I gave him one solution --> We can upload 2 external CSS file into Static resource--> import both in JS and if we can use them in loadscript.But not sure. 

Rasbehari: 
1.There is relation A---> B ---c   , I want to call C to A directly. 
2.What are the default Templet in Experience Cloud. 
3.How many Quotes can relate one opportunity. 
4.I have Separate region, I want to show different field each region how we will do in LWC. 
5. Can we able to create multiple css file in LWC. 
6.In standard page we will create Task but there is LWC Data table how it refresh automatically without any hard refresh or url. 
7.What are the rules in omni channel in Salesforce. 
8.what is the difference between cpq and revenue cloud. 
9.Different between Product Option and Product Feature. 
10.What are the parameter we can pass in custom event. 
11.how many parameter we can pass in invocable method salesforce from flow to apex. 
12.how many invocable method we can write in apex 
13.What type parameter we can pass in invocable method salesforce, from flow to apex.
------------------------------------------------------------------------------
Rajesh:
How can you query a field from Object C when Object C is related through Object A → Object B → Object C in SOQL?
What are Custom Permissions in Salesforce, and how do they work? How are they assigned and used?
How many Validation Rules can be created on a single Salesforce object? Are there any limits or best practices?
What is the difference between Salesforce CPQ and Salesforce Revenue Cloud?

What are SOQL and SOSL? What are the key differences between them, and when would you use each one?
How many records can be assigned or owned by a single user in a Salesforce Production org? Are there any practical limitations?
How does communication work between Lightning Web Components (LWCs)?
Child-to-Parent communication
Parent-to-Child communication
Communication between sibling components
What are the Lifecycle Hooks in Lightning Web Components (LWC)? Explain each hook and its purpose.
 
 
 
 
 
1)Please write SOQL which will retrieve all the information from below object where Organization Name = "Global Payments"
Organization__c : Organization Name, Company Information, Revenue
Project : Name, Budget, Organization__c
Timesheet : Name, Approval,Project__c

2)Need to write a trigger for the below scenario
Pancard__C custom object which is having master detaild with Contact
when user tries to create more than one pancard for contact then through an error.
 
//Write an Apex Trigger to prevent inserting duplicate Account records based on the Account.Name field.
//Write a SOQL query to retrieve all accounts with more than 10 contacts
//Update all the related case to closed if parent case status closed.
 
 
I have an Account with a field named "ContactEmail" and a related Contact that has a "ContactEmail" checkbox. Whenever a Contact record is inserted, updated, deleted, or undeleted and the checkbox is checked, I want to update the associated Account's "ContactEmail" field with the Contact's email. Additionally, whenever the Account's "ContactEmail" field is updated, that specific value should be updated to the primary Contact's email field.
 
 
=======================================================================
 
what is the difference between Product Option and Product feature? Example: Washing Machine, what will be the Product Option and Product Feature
What is custom Permissions?
What is sObject Iterable in batch of Start Method?
If I want to use any varibale in Finish Method and I have declared at class level what specifire we have to use? What will be the type of the variable?
How many ways we can communicate between two components?
How frequently you code in your day to days activity
How many quote we can sync with the Opportunity in CPQ?
Ans: An Opportunity can contain multiple Quotes, but only one Quote (the Primary Quote) can be synced with the Opportunity at any given time
What if i make another quote as primary quote and try to syn what will happen to Opportunity line item
Ans:
If you make another Quote as the Primary Quote and then sync it to the Opportunity, Salesforce CPQ will replace the existing synced Opportunity Products (Opportunity Line Items) with the products from the newly synced Primary Quote. The Opportunity Amount will also be recalculated based on the newly synced quote.
write a SOQL query to retrieve all accounts with more than 10 contacts
 
 
 
What are the mandatory attributes in datatable?
<lightning-datatable
key-field="Id"
data={data}
columns={columns}>
</lightning-datatable>
Suppose the data-table which you have on a page which gets invoke whenever the page gets loded. So you display some data in your datatable, in a component which is getting invoke initailly where do you think you pull data into your datatable is it wire or connectedCallback? what do you think?
Is the method cacheable for wire? Whats the default cacheable of the method? What will be happen if we write cacheable = true?
Ans: The default value of cacheable is false. When an Apex method is used with @wire, it must be explicitly annotated with @AuraEnabled(cacheable=true). Setting cacheable=true allows Salesforce to cache the response on the client side, improving performance and reducing unnecessary server calls. Since cached methods are expected to be read-only, they should not perform any DML operations.
what if the data is getting changed in the backend it will pull data from cache not from backend? How will you handle that? Suppose some records gets inserted into my database and I want to display in the datatable? How will you handle that?
What are the parameters we have in publish and subscribe?
what is the diff between promise method and async await?
What are the methods do we have in promise?
The most commonly used Promise methods are then(), catch(), and finally(). JavaScript also provides static methods such as Promise.all(), Promise.race(), Promise.allSettled(), Promise.any(), Promise.resolve(), and Promise.reject(). In LWC, we most frequently use then() and catch() while making imperative Apex calls
What are diff apex design pattern? Can you name some
In a try catch block can I have multiple try?
Can you have multiple catch blocks for one try?
Whenever opportunity stage is completed. Suppose there is a amount field in contact for all its related records suppose 10k records and this is happening using bulk API or dataloader. So dataloder we inserted the file 10k records and account gets updated how you will handle the situation? will it go to run into an error when you execute 10k opportunity in this case?
Whenever an Opportunity's Stage becomes 'Closed Won', you need to update a field on all related Contact records. Assume there are about 10,000 related contacts, and Opportunities are being updated through Data Loader/Bulk API. If 10,000 Opportunities are processed, will your solution run into governor limit errors? How would you handle it?
Can we call Scduler from future method?
Can we call future from batch apex?
Is there any other way to call future method from batch apex?
Suppose we're deploying a Scheduler Apex class to a target org. However, there is already a scheduled job in the target org that references the old version of the Scheduler class and is currently in a Pending state. Will the deployment fail? If so, how can we successfully deploy the Scheduler class?
DO you know how many types of discount we can apply in RCA?
 
 
 
How Quote to cash is diff from RCA?
What are all templates available when we create new experienced site
What is LWR?
I have 3 component A B and C. I want to dispatch the event from C and directly handle on A?
bubbles: true
Allows the event to travel up the component hierarchy.
composed: true
Allows the event to cross shadow DOM boundaries.
Without these properties, the event may stop at component B and never reach A.
Havw you worked with Platform Event? Have you created any Platform Event?
What are the standard fields that are available when you create any new platform event
When you create REST base API what are the diff scope available for select?
Do you know any apex design pattern. Can you name some? Any Integration design pattern
Why do we need to serialize and deserialize the request or response. What is the requirement of that?
When two systems communicate (Salesforce ↔ External System), they don't exchange Apex objects directly. They exchange data in formats like:
JSON
XML

So we need a way to convert between Apex objects and JSON/XML text.
Serialization is the process of converting Apex objects into JSON or XML format so that the data can be transmitted over a network or sent to another system. Deserialization is the reverse process, where JSON or XML data received from an external system is converted into Apex objects. We use serialization for outbound requests and deserialization for inbound responses because external systems cannot understand native Apex objects directly.
Serialization = Converting an Apex object into JSON/XML string.
Example:
AccountWrapper acc = new AccountWrapper();
acc.name = 'Acme';

String jsonBody = JSON.serialize(acc);
Result:
{
  "name": "Acme"
}

Before sending a request to an external system, Salesforce must convert Apex objects into a format the external system understands.
Apex Object → JSON → External System
 
Deserialization = Converting JSON/XML string into an Apex object.
Example:
{
  "name": "Acme"
}
Result:
AccountWrapper acc =
     (AccountWrapper)JSON.deserialize(
        responseBody,
        AccountWrapper.class
    );
After receiving data from another system, Salesforce needs to convert the JSON into Apex objects so it can process the data.
External System → JSON → Apex Object
 
when do we use deserialize at the time of response or request?
What is custom Permission
How SBQQ quote API and SBQQ Order API Work? Is it part of salesforce or part of RCA?
Can we call future from Scheduler?
Can we call future from batch? why we are call future in execute method not finish method?
A Future method can be called from either execute() or finish(). Typically we invoke it from execute() when the asynchronous processing is related to the current batch scope of records. We use finish() when we need to perform a post-processing activity after all batch chunks have completed, such as sending a summary email, launching another process, or performing cleanup operations.
On the Contact object, there is a custom checkbox field called IsPrimary__c. For any Account, only one Contact can be marked as Primary at a time. Whenever a new Contact is inserted or an existing Contact is updated with IsPrimary__c = true, all other Contacts related to the same Account should automatically be updated to IsPrimary__c = false. How would you implement this in Apex while ensuring the solution is bulkified?
 
 
 
 
- If a user has Read access in their profile and the OWD is set to Public Read/Write, what level of record access will they have?
- Is it possible to restrict access to records via the role hierarchy in Salesforce?
- Can we define a class as private in Apex?
- Can we call a @future method from a Batch Apex class, and what is the default batch size?
- Is it allowed to invoke a @future method from another @future method?
- Can we call a @future method from an Apex Trigger, and is it considered a best practice?
- How can one Batch Apex class invoke another Batch Apex class?
- How do you send an email to a manager regarding failed records from a Batch Apex execution?
- What are static methods in Apex, and in what scenarios should we use them?
- How do you invoke an Apex class from a Flow, and why might a specific Apex class not be appearing in the Flow's action list?
- In a parent-to-child trigger scenario, how can we ensure only one unique Contact is linked to an Account, and raise a validation error if more than one    exists?
- What are the ways to pass data from a parent record to its related child records?
- What are the lifecycle hooks in Lightning Web Components (LWC), and why are they important?
- How can data be passed from a child component to its grandparent component in LWC?
- What is the difference between renderedCallback() and connectedCallback() in LWC?
- What are the best practices for handling errors in Salesforce Flows?
 
What is the difference between @api, @track, and @wire in LWC?
How do you pass data from parent to child and child to parent in LWC?
Explain lifecycle hooks in LWC
How do you share data between unrelated components in LWC?
Can you call multiple Apex methods in a single LWC? How do you manage it?
What is the difference between renderedCallback and connectedCallback?
 
1)I have two Salesforce users, User A and User B, who have access to an account with 100 records. When they log in, User A sees 20 records while User B sees 40 records. What could be the reason for this difference?
2)I want to share User A's account record with Users B and C based on ownership. How can I do this?
3)I want to share access of User A's account record with six or seven other users. How can I do that?
4)I have a manager who can access subordinate account records. How can I restrict the access to view these records?
5)I have an Account with a field named "ContactEmail" and a related Contact that has a "ContactEmail" checkbox. Whenever a Contact record is inserted, updated, deleted, or undeleted and the checkbox is checked, I want to update the associated Account's "ContactEmail" field with the Contact's email. Additionally, whenever the Account's "ContactEmail" field is updated, that specific value should be updated to the primary Contact's email field.
 
1)Please write SOQL which will retrieve all the information from below object where Organization Name = "Global Payments"
Organization__c : Organization Name, Company Information, Revenue
Project : Name, Budget, Organization__c
Timesheet : Name, Approval,Project__c
 
2)Need to write a trigger for the below scenario
Pancard__C custom object which is having master detaild with Contact
when user tries to create more than one pancard for contact then through an error.


future
batch apex
asynchronous
queauble
integration
config part - profiles - owd security
lwc - parent to child, life cycle hooks
apex trigger for account contact, counting the number of contacts associated to account ?
1.	About manual sharing
2.	diff bet custom obj/metadata/cust setting
3.	salesforce order of execution
4.	how batch apex runs, what happens if few record from 1batch fails?
5.	what is cacheable=true means?
6.	how to call apex class in flows?
7.	What excatly means bulkification of code and why that needed?
8.	What is salesforce governer limits?
9.	Flexcard
10.	Objects relationships, when to use lookup and master details? use cases by example
11.	Scheduled triggered flow
12.	Diff between OS and flexcard
13.	What are clouds there in salesforce
14.	Standard obj and custom obj 
15.	Profiles and roles and permission sets Permission set group 
16.	Apex with sharing and without sharing 
17.	Apex by default runs in which mode? 
18.	before & after trigger
19.	diff bet flow & trigger

CERTIFICATIONS:
You can start with Admin, PD1
next is App Builder
to specialise in LwC -> JavaScript Developer
Agentforce is mandatory to have in current scenario
 
next level -> PD2
then you can try for cloud specific certifications like Sales Cloud, Service Cloud, Experience Cloud etc. based on the domain you are targeting for.
if you want to go on architect path then we have -> Data Architect, Sharing and Visibility Architect and more

 
 QUESTIONS:
1.	Configuration - Security Model, Automation Flow, Profile, Permission, Role
2.	Apex - SOQL, SOQL, , With Sharing and Without Sharing
3.	Trigger - All the events, context variable.
4.	Integration - REST and SOAP, Callout and callin 
5.	Test classes - @testSetup, Test.StartTest(), Test.StopTest(), System.runAs(), Test.isRunningTest(), Assert Class
6.	LWC- Parent child, child to parent relationship, Lightning Data Services, Wire, Imperative, Lightning Data table
7.	How to deploy component in Salesforce - sfdx , vscode, git


REFERENCE MATERIALS:

imp links:
LWC components link: https://developer.salesforce.com/docs/component-library/bundle/
udemy LWC: https://capgemini.udemy.com/course/zero-to-hero-in-lightning-web-components/learn/

TRAILHEADS:
1st trailhead: https://trailhead.salesforce.com/users/journeytosalesforce/trailmixes/your-journey-2-salesforce-learning-path
LAB: Custom Lightning Page Creator for Salesforce Apps
LWC: https://trailhead.salesforce.com/content/learn/superbadges/superbadge_lwc_specialist
basics: https://trailhead.salesforce.com/content/learn/modules/starting_force_com
integration apex : https://trailhead.salesforce.com/content/learn/modules/apex_integration_services
data security: https://trailhead.salesforce.com/content/learn/modules/data_security
apex testing: https://trailhead.salesforce.com/content/learn/modules/apex_testing
Triggers:
https://trailhead.salesforce.com/content/learn/modules/apex_triggers
SOQL SOSL:
https://trailhead.salesforce.com/content/learn/modules/apex_database check the units inside
Page Layout:
https://trailhead.salesforce.com/content/learn/modules/lex_customization?trail_id=force_com_admin_b…
https://trailhead.salesforce.com/content/learn/modules/lex_migration_customization
Apex Integration:
https://trailhead.salesforce.com/en/content/learn/modules/apex_integration_services
SFDX,VSCode,GIT:
https://trailhead.salesforce.com/en/content/learn/modules/sfdx_app_dev
https://trailhead.salesforce.com/content/learn/modules/git-and-git-hub-basics?trail_id=set-up-your-…
https://trailhead.salesforce.com/content/learn/projects/quickstart-vscode-salesforce?trail_id=set-u…
validation rules: https://trailhead.salesforce.com/content/learn/modules/validation-rules
flows: https://trailhead.salesforce.com/content/learn/trails/build-flows-with-flow-builder

https://trailhead.salesforce.com/content/learn/modules/apex_integration_services

Data security: https://trailhead.salesforce.com/content/learn/modules/data_security
https://www.youtube.com/watch?v=VgmR2x8_GUY&t=69s
https://www.youtube.com/watch?v=Xzm0EocL6KY&t=1052s

1st trailhead: https://trailhead.salesforce.com/users/journeytosalesforce/trailmixes/your-journey-2-salesforce-learning-path


salesforce basics : https://trailhead.salesforce.com/content/learn/modules/starting_force_com


https://www.crsinfosolutions.com/what-is-the-difference-between-salesforce-apex-and-java/

documentation: https://developer.salesforce.com/ - documentation
