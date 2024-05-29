# Total Utility Connections

<details>
<summary>Index</summary>

1. [Dictionary](#dictionary)
2. [Infrastructure](#infrastructure)
3. [Useful Notes](#useful-notes)
</details>

<details>
<summary>Dictionary</summary>

- **Variations**: A term given to a change to the project that is outside of the scope of the agreed contracted works.
- **Revisions**: A change given to a particular page/content
- **Customers**: A client. Who we sell the project to.
- **End-Customers**: Sometimes the end customer will be different to the customer/client. The customer/client could be working on behalf of multiple end customers.
- **Post Acceptance Form**: A form that is used 'Post Acceptance' (i.e after the customer has accepted the contract) that is used to collect the informations that is required by us to complete the project.
- **Tables**: A page with a table that links to multiple screens/bits of info.
- **Database Tables**: Tables in SQL
- **Phases**: Think of them as sub-projects that can have info that is different from other phases
- **Infrastructure**: a specific phase that doesn't have plots but has infrastucture for the rest of the project (gas pipe and electric cables etc)
</details>

<details>
<summary>Infrastructure</summary>
  
[List your organization's projects here]
</details>

<details>
<summary>CI/CD And Branching</summary>
</details>

<details>
<summary>Code Standards</summary>
</details>

<details>
<summary>Useful Notes</summary>

### 29/05/2024 - 10:00am - Work requests with Mark
Work request has to be allocated only to those who are qualified and the work type e.g. electricty only project cant raise a gas job- May not include just yet
Looking at the data capture side first
Current work instruction doesnt say who the operative is (the guy doing the job)
Work is booked per team, different users should be able to be allocated to a team. 
When booking the team must check who if any of the team members are qualified
The work request should go to the person(s) who is qualified for the job within the team
Test Forms - Must be submitted in a specific format
Work requests have pdf drawings - the guy on site has to edit the drawing and draw the as laid they need to be able to access the relevant drawings uploaded against
the project instead of needing to upload a new pdf for each.
What drawing do they need? where do we store it against the project?
Notification when a work request is completed - notify relevant person. 
We want the PC to set up the work request first, then the people on site have to fill it in based on the set up
10% tolerance on what got laid (under and over)
Eventually this has to check against the budget
For some jobs (electricity) people also have to be authorized and not just qualified
Need to have a status of completion, (3/12 done) 
Team dashboard? 
As-Laid drawings could be the same drawing for different sections give them an option same as a previous uploads and then they choose which one, makes the same link to that
upload
Have the system look at test values and check if it is between the estimated normal values if not flag it for the completions person and whoever is entering the data
Do we need to add project status?
Work request should have a summary based on what has been selected for the job
Flowchart template in process documents

### 23/05/2024 - 10:50am - Catch up on paif
commercial is fake everything in domestic - domestic people live there

Paif Component
portal side for paif component checks isCustomer and passes read only is false
staff side read only is true
if making json file set it as embedded resource in the properties



### 14/05/2024 - 16:09pm - Question wording
Add tooltip in customer pov for PAIF Card to explain what it is to customer?
Add Site name to start if paif form title
'Your' for each of the paif questions e.g. 'Your Design Details'
Do we want tooltips for each section to give more info in the paif form?
full turnkey and commercial gas - some fields wont be required but may be (legal, landowner,)
Legal contact tooltip to state who we want
Site Start Date - when they themselves started on site
First Connection Plot Date - their first connection
Anticipated Energization Date 
on add project - when clicking water for utility choose self lay or nav
Add message at bottom if they query the proposal that their business developent manager will be in contact
Electric -> Electricity
Move the 'can you please confirm' to below the master questions
'Is the Site Boundary Correct?' - Always show this question 
If the boundary is wrong they need to upload a drawing to show the correct boundaries
Remove question 'Are the routes correct?'
Address question - 'Is the Site Address Correct'?
Is the number of Gas Service connections correct?
Minimum Call of is one question not individual utility 'Are the minimum call offs acceptable?'
Only use capital letters for the 3 utilities e.g. Electricity
Is the gas load correct - only commercial
Have housing schedule cost question first
have tooltips for some of the questions e.g. housing schedule (this could make money changes)
Add in What3Words in add project



### 10/05/2024 - 12:08pm - Meeting with Cath, Rhys and Kyle
Add who is the sales person for each project
Add Status to proposal confirmation
Have you read and reviewed the proposal and are happy it is correct? if no then show the other questions
Other notes text box at bottom
Show project owners on customer perspective for their project
Different types of water
Solicitor and landowner for gas as well as electric
Housing Type & Housing Schedules

Mixed proposal - number plots which have different utilites e.g. 200 plots but only 100 have gas

Later On
Timeline of project (workflow)
Additional drawings such as Draft

### 16/04/2024 - 11:26am - V1 requirements
### Needed Enquiry Types 
Turnkey 
Ev 
Mixed 
Battery
Domestic 
Commercial 

Gas - Taylor 
Electric - Kyle

- [ ] Remove connections manager 
- [ ] Make the edit highlight grey 
- [ ] Button in create new project to say customer and end-customer same 
- [ ] Rename accounts to customer accounts on Projects page 
- [ ] Highlight changes betweeen PAIFs 
- [ ] Highlight changes in email 
- [ ] Log who created the project
- [ ] CustomerPOV - Hide the word 'Phases' in project info show site name
- [ ] Text standards get sent with send form (proposal drawing & letter they accept)

Questions To think about?
How do we communicate the PAIF document is live so multiple people might change it? Could it be an initial email or a call out box. 

How do we chase this with 

Can we start we have staged data entry, info we need to get started?

AUDITING? Tracking emails 

Next Catch Up on Wednesday 24/04/2024

### 16/04/2024 - Meeting with Rhys and Cath
Mixed use utility
Asset value portals - evc? 
EVC separate to commercial and domestic
Will soon get rid of connections manager
Put utilities at the start - owners only show if they select that utility?
Tell us who created the project
change the yellow highlight on edit to a nice grey
End customer can be the same they have to check a box or something
In customer info have the table say Customer Account instead of just Account
Send form should pull client and end customer if they are different - If sending to client and end customer, different email to explain theyre both filling it out?
Emails history / message history
Have some sort of project status - notifies specific paf sections depending on whats needed next?
CustomerPOV - Hide the word 'Phases' in project info show site name
Text standards get sent with send form (proposal drawing & letter they accept)
Project status - stages with sub stages


### 12/04/2024 - Testing with users notes
1. Make ammendment button after submitting paif takes to all projects rather than that specific one
2. Maybe have astriks or some indentifying for the user that for that section to be all completed they have to fill in the whole section
3. Form status in PAIF table is showing in progress but in project info its submitted?
4. If the client and end customer are different do we want to get the customer accounts for both? and then if they are the same we do a check so we dont get them twice
5. Customer POV - instead of saying 'create' for ammendment say 'edit'
6. Customer has the possibility to change (client)
7. plot to postals? mpan mprn? Only part a Project Coordinator needs
8. Leah suggested edit button for our side "just in case" (Don't think Mark will like this one but let's put it in for review)
9. Address line 2 should be optional 

### 04/042024 15:11 - Taylor's Big Ideas
Asked Taylor about the current set of questions he mentioned that:
1. There are times custom fields are needed to meet niche project requirements 
2. With the current PAIF spec would we handle part of the post-acceptance process in the portal and then the rest in email? Is this more confusing than just email? The missing post-acceptance
questions that Leah gave in her document, are things like if Electric is needed in a High-Rise then we need X (which we currently don't have anything for, this would require changes to create project process and post acceptance form itself)    
3. A quick fix could be include "critical fields" with a create custom question field that the designers could put together (Critical fields being information which is basically always needed, there is alot of information that is needed sometimes)
4. Design can make a PAIF template for us hopefully with a flow diagram for some of the logic they use when putting together a PAIF
Bonus: Also looked at Affinity's portal

### 04/04/2024 08:35 - Archie's PAFological notes
Implementing versioning (without the approve deny system)
  - [ ] Version number increase on form submit and set form to submitted
  - [ ] Little message about submitting the form (this will notify us) 
  - [ ] Test that forms with multiple versions can all be accessed from View Versions button 
  - [ ] Finish PAF view in phases (status and updated fields)
  - [ ] Make old versions of Customer PAF read-only for customer too (maybe give a warning that its an outdated version)
  - [ ] Chase up who needs to be email on PAF submission
  - [ ] Find out about our release timeline and what features need to be in for release?

### 03/04/2024 11:47 - Questions about PAIF
Do we need to include questions which depend on circumstances (if applicable questions) such as Electric being HV or LV or having a Substation? (how important is it)
Do we need the option to have custom questions should every possible question be covered based on the information within the project/ optional by clicking on the question?
Can the project be completed based on the questions/information we are retrieving currently?
What information should be collected in the Infrastructure stage and would any of this overlap into the phases? (if so shall we not include it in the phase or show the information thats been inputted in the infrastructure in the phase as well)

### 03/04/2024 10:01 - Individual component permissions per page
When I say 'Who' I Mean what Roles/Staff level
- [ ] Phase info - Who can delete utilities? (deleting doesnt delete from database but we make them think it does) Director/ITAdmin
- [ ] Infrastructure Info - Who can delete utilities? (deleting doesnt delete from database but we make them think it does)
- [ ] Customer Info - Who can Add Customer Account? (Which the customer can login with, Who can Edit Customer Accounts? (The name and email), Who can reset customer account passwords?
- [ ] Users List - Who can see the page? Who can make new users?(IT, HR and Director) Who can Edit Users? Who can reset Users Passwords? (IT,HR, Director)


### 28/03/2024 - 16:50 - Jack's notes to self
Find out permissions for individual components on each page, who can and can't use specific buttons or see certain fields.
Add User allocation in each project, e.g. project coordinators, lead designer. For now just make a dummy email for each role rather than creating people logins for now.

### 28/03/2024 - 16:32 - Big Confrontation with the Design Team (GONE WRONG!!!)
We asked Rob about the data we need for Turnkey because we didn't have anything for mains disconnects. Rob had a few thoughts on fields that were missing. We then asked Design (mainly Leah) what she thought about the rest, she sent us the PAIF template email they use at the minute and we're missing quite a bit in comparison. For example they have sections like If there is a substation on site give us this information or if the project is HV or LV.  
![image](https://github.com/tucltd/.github/assets/157698519/eb844b4f-0076-4f3c-9af5-fe311e0f60e7)


### 28/03/2024 13:47 - Who has permission for each page? (Roles for each page as a whole not individual sections on a page)
- [x] Login - AllowAnonymous 
- [x] Portal Login - AllowAnonymous
- [x] Forgot Password - AllowAnonymous
- [x] Portal Forgot Password - AllowAnonymous
- [x] Password Reset - AllowAnonymous
- [x] Portal Password Reset - AllowAnonymous
- [x] Home - Staff
- [x] Projects - Staff
- [x] Project info - Staff 
- [x] Phase info - Staff
- [x] Infrastructure Info - Staff
- [x] Customer List - Staff
- [x] Customer Info - Staff
- [x] PAF Form Page Users - Staff
- [x] PAF Form Page Customers - Customer
- [x] Portal Home Page - Customer
- [x] Portal Project Info - Customer
- [x] Portal Change Password - Customer
- [ ] Users List - Staff + Who??
Bonus - Make ItAdmin only
- [x] Calendar
- [x] Leave Control


### 19/03/2024 16:45 - Emails
- [x] User welcome, tell them their password and tell them to change it
- [x] Same as above but for customers
- [x] Notify Customers their password reset
- [x] Forgot Password function
- [x] Tidy Up Forgot Password and make it look nice
- [ ] Email customer when PAF created
- [ ] Email Us when they submit PAF - Add selection to who we want on the project to handle it (look at current Add Project system minus tendering engineer. We will need roles for this)
  Extra
- [x] Users Table gets All Users, we want to get all users without a CustomerId
- [x] Check when creating CustomerAccount that the email isnt already in use (use code from creating Users)


### 19/03/2024 09:06 - Jack's To Do List
- [x] Customer POV projects table - Everyone can see a project that they are linked to at any stage
- [x] Customer POV PAF Forms for Infrastructure and Phases - If First Customer, can see all Infrastructure and phases PAF's. Else, only show the parts where they are the end customer
- [ ] tooltip for add project to explain who and what each customer is?
- [x] Paf form icon needs alignment infrastructure & Phases tables CustomerPOV

### 15/03/2024 10:56 - Jack's To Do List
- [x] Infastructure table 

- [x] add multiphase bool to project table

- [x] multiphase yes no in create project

- [x] To be able to change whether project is multiphase or not after its created

- [x] Add Phase in projectInfo should not work if set to non multiphase, have a tool tip if hovered to tell user project must be multi phase to add phases

- [x] Complete Infrastructure Repository and Service Layers

- [x] Add 'Infrastructure' to AddProjectDialog

- [x] Display infrastructure in project info

- [x] Infrastructue Info page Navigation

- [x] Add service to get phaseId using project number and phase number

- [x] infrastructure info page fix (gets infrastructure based on projectId)

- [x]  int InfrastructureCustomerId = Customers.FirstOrDefault(c => c.CustomerName == Infrastructure.SelectedCustomerId)?.Id ?? 0; If 0, customer doesnt exist so dont let them create


### 15/03/2024 9:58 - Notes and thoughts on how to maybe bring salvation to the system
We need an infastructure table - What information would this contain and what does it feed the other phases, it's own acceptance form?

Can switch from multi phase site and single phase site at any point

if switched from multi to single, phases need to be 'Abandoned'. Boolean in phases table for abandoned?

What information do we need in the infastructure table?

### 14/03/2024 13:09 - More questions with Mark :)
Phase 0/ Infrastrucutre Phase could be a common phase shared amongst all phases (like a parent phase the rest feed off). 

Do we need an infrastructure layer for projects that are handled by a contractor? If so, Infastructure table?
If single phase site, infastructure and phase 1 is combined into 1. If multi-phase, infastructure phase and multiple phases. Need to be able to switch to multi phase site later on?

Functionality to be able to break a project into phases at a later date, will they still need a paf form?

Can phases and projects both have over head variations which affect all children of them? 

Mark also introduced the idea of an Enabling Contractor (don't know if this is relevant at all) 

Can individual phases be put on hold?

### 12/03/2024 9:10 - To do list and Questions for PAF Form

- [ ] Do we want PAF forms to have both versions and variations (regarding the database)
- [ ] If variation how do we want to store and identify it within db tables
- [ ] What do we want the message to be for the customer if they update a field such as CAD plan? e.g. 'this could cause a new variation are you sure you want to continue?'
- [ ] What fields would cause a variation?
- [ ] Do we want approve and approve with new variation option?
- [ ] Do we want the customer to have to request a variation or do we want to 'force' the customer and tell them there is a variation? Do we want the customer to have to approve the variation
- [ ] Split into different types of variations/Ammendments? (Cost / Design / Design with Cost) (Design Ammendment instead of variation but cost is cost variation?
- [ ] If a new variation is created, how do we notify the customer? e.g. email saying a new variation for project xxxxx has been created and one of our team members will be in contact

File Uploads should only overwrite a file in azure with a new version if the file has previously been approved
Individual approve or deny for files + status tags for uploaded blob files

### 11/03/2024 10:36 - Made the mistake of asking more questions to Phil

Revisions are now variations
On PAF update if the change is significant i.e. affects design work then this will create a variation because design work may have to be redone changing project timelines.

Variation = New Form (big change 5 new houses add to plot - job is different now)

Version = any section updated (silly little change i.e. solicitor phone number changed)

### 8/03/2024 - Jacky's questions for Ross

End Customers and Contractors, who fills in the PAIF and who do we give accounts to?
need end customer field in project table, contractors can have multiple clients with projects Both need to login

can a project have more than 1 customer and 1 end customer?
projects can have 1 customer and multiple end customers
projects can have multiple PAF forms

Can have 2 enquiry types do we need to worry about commercial domestic

Add isGasDom/Com/elec/wat to project table & second enquiry type

be able to add and remove utilities after project is created

Form builder should be Send form where user selects customer account(s) they want to notify via email. Keep select options on form sender, should the selections be linked to the project table? (if gas commercial is selected in project table it is already ticked in form, if then unticked it is removed from the project table) pre populate from database but unticking doesnt remove it

are we including turnkey? can it be turnkey and another enquiry type? only turn key
fibre? yes

Can the PAIF go on hold? or just the project - just project
Last Updated and by who for Customer POV projects table - status, last updated, change 'Projects' to 'Post Acceptance Forms'

Approve and Deny PAIF?

</details>
