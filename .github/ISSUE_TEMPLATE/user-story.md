---
name: User Story
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

**As a** Service Provider. 
 **I need** the service to be deployed in the cloud
 **So that** I can scale capacity with user demand 
   
 ### Details and Assumptions
 * Database still needs to be provisioned
 * App needs to be pushed and connected to the database
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given service provider is logged into their account 
 When the service provider selects "Save to Cloud" and enters valid data  
 Then the data is securely stored in the cloud and accessible upon login
 ```
