# Total Utility Connections

<details>
<summary>Index</summary>

1. [Dictionary](#dictionary)
2. [Infrastructure](#infrastructure)
3. [Useful Notes](#useful-notes)
</details>

<details>
<summary>Dictionary</summary>

- **Variations**: Definition of term 1.
- **Revisions**: Definition of term 2.
- **Customers**: Definition of term 3.
- **End-Customers**: Definition of term 3.
- **Post Acceptance Form**: Definition of term 3.
- **Tables**: Definition of term 3.
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

- [ ] Add service to get phaseId using project number and phase number

- [ ] Add service to get infrastructure using project number? May have a service that can be re used

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
