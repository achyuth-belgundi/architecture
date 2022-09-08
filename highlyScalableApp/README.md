Welcome to the idea on building highly scable app for one of the use cases that we are quite familiar with Seasonal Time bound Activities within Enterprise.


Here I talk about Appraisal which is yearly event and time bound to complete by multiple users within Workflow.
Quite often we need to scale the application depending on the load that comes in last few days of Submission timeline.

<b>This use case is similar to Tax filing as well.</b>


The application aims to break down the traffic of users that come onto Monolith App and divert them to individual micro services.
This not only distributes the traffic of users but also helps in scaling up/down respective service where the load is high.


I have identified following functional components in a typical Appraisal:
- Goals & Objectives (G&Os based on role, seniority etc.)
- Appraisal Review Form (Comments, Attachments etc.)
- Workflow (the manager(s) who finalizes the appraisal rating)

I have identified following technical components covering both Frontend (Mobile & Web) and Backend:

**Appraisal Form**

  - Frontend
  
**Goals & Objectives:**

    ![image](https://user-images.githubusercontent.com/61909185/189197098-50aa1267-7625-4687-b5ac-3612a63748cc.png)

  - Micro Frontend

  - Backend Service (API)
**Workflow**

   ![image](https://user-images.githubusercontent.com/61909185/189194838-05042669-795c-4717-ac8a-d1a79943d63f.png)
    
  - Micro Frontend
  
  - Backend Service (API)

**Appraisal Review Form**

   ![image](https://user-images.githubusercontent.com/61909185/189197187-2b48371b-486b-4141-b861-9c3e1daa725c.png)

  - Micro Frontend
  
  - Backend Service (API)

**API Gateway**





**Application Architecture:**
    
   ![image](https://user-images.githubusercontent.com/61909185/189197558-69cd5b2d-9f30-4d39-9b14-b30e3e4f8e3a.png)





