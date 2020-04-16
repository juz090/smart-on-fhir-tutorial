# Project Plan

**Author**: UnFHIR-able

## 1 Introduction

Our project, Pre-Visit Planning, involves developing a system that assists physicians in scheduling maintenance check ups for the patient based on factors such as age, gender, and current medical conditions. Our product will simplify the manual process by utilizing a FHIR-based service to automate patient information retrieval and decision making.

## 2 Process Description

1. Requirements Gathering
* Description: In this stage, we (the team) will need to gather requirements on the project, including expected output/deliverables, data needed, etc.
* Entrance Criteria: We will create a list of questions and schedule a meeting with Dr. Anderson. The questions should clarify many aspects of the project, and the problem we are trying to solve. 
* Exit Criteria: We will have detailed requirements for the project. If possible include stretch goals. Project Plan.md, Gantt chart, Powerpoint and video.
2. Mock UI 
* Description: In this stage, we will provide mocks of the project to Dr. Anderson. The purpose of this stage is to make sure we are on the same page as Dr. Anderson and to flush out as many one-sided assumptions as possible before development.
* Entrance Criteria: We will provide mocks of the product in any form (static webpage, Marvel mock, or paper drawings)
* Exit Criteria: The mock UI presented to and is approved by Dr. Anderson.
3. Resource gathering
* Description: In this stage, we will need to ensure that we have access to all resources necessary for project completion. This includes obtaining access to Cerner Sandbox, interaction with the FHIR data on the sandbox, etc..
* Entrance Criteria: We need Dr. Anderson to schedule an appointment with Emory IT for us so that we can talk to them about obtaining credentials for Emory FHIR sandbox
* Exit Criteria: We have received the credentials required and are able to make REST calls directly to the Emory FHIR sandbox
4. Prototype website - end-to-end testing
* Description: In this stage, we will create a very barebone webpage that interacts with all necessary resources. The purpose of this stage is to ensure that we are able to pass data throughout the system.
* Entrance Criteria: We need to have access to all required resources (step 3)
* Exit Criteria: We will need to connect all resources and ensure that we can obtain data end-to-end.
5. [Iteration 1] Present to Dr. Anderson
* Description: In this stage, we will clean up the prototype from step 4 to be more production friendly (remove hard coded variables, unnecessary code, cleaner UI… etc). We will then present this webpage to Dr. Anderson and walk him through the steps to use the webpage. We will then request feedback (what should be done differently)
* Entrance Criteria: We will have a prototype website that can access and pass data from end-to-end
* Exit Criteria: We will have feedback from Dr. Anderson about the utility/UI of our website to work off of for iteration 2 of presentations.
6. [Iteration 2] Present to Dr. Anderson
* Description: We will take the feedback from iteration 1 and present an updated website to Dr. Anderson.
* Entrance Criteria: We will have already received feedback from Dr. Anderson for the initial iteration of the product
* Exit Criteria: a refined, final product is produced and approved by Dr. Anderson
Stretch goal 1
## 3 Team

Roles:Project manager - Responsible for managing teams, client expectations, and the project as it goes through the development process.
* Back end developer - Utilizes Python to create a REST service that calls the FHIR APIs, as well as parse the responses into digestable formats. Responsible for implementing logic to recommend procedures based on obtained information about the patient
* Front end developer - Responsible for implementing the UI of the application using HTML/CSS and Javascript. Responsible for implementing logic that submits form data to the service layer, as well as parsing the service response and displaying information on the UI.
* QA - Responsible for the quality assurance of the app. Tests the happy path and rainy day scenarios for each feature. Logs any defects.

| Name  | Role  | 
|---|---|
|Daniel Gao |Project Manager |  
| Bowen Yang  |QA/ Developer   |  
| Junyi Zhao  | QA/ Developer  |  
|Ying Yu   | Developer  |   
| Yongquan Tan  | Developer  |   
| Frank Hu  |Developer   |    







