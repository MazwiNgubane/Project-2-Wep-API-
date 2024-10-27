# Project
## web API

### Overview
The NWU Tech Trends API allows users to manage telemetry data for automation systems, tracking time saved, and associating it with projects and clients. This API supports CRUD operations on projects, clients, and telemetry records.

#### Base URL
even though it will display an 500 error which is the Error that indicate that the is a problem with the server, and it is because  of the fact that my credits in Azure portal subscription are used up
https://cmpg323-project2-3033657020240807133509.azurewebsites.net
#### Endpoints
##### JobTelemetries
###### get All Job Telemetry Records
- EndPiont: '/JobTelemetelemetries'
- Method: 'GET'
- Description: Retrieve alist all teletry records
- Parameters:

###### get Job Telemetry Record by ID
- EndPiont: '/JobTelemetries/{id}'
- Method: 'GET'
- Description: Retrieve  a single JobTeletry record by it ID
- Parameters: 'id' (requied): The ID of the JobTelementries record

###### get Job Telemetry Record by ID
- EndPiont: '/JobTelemetries/{id}'
- Method: 'GET'
- Description: Retrieve  a single JobTeletry record by it ID
- Parameters: 'id' (requied): The ID of the JobTelementries record

  ###### Create new Job Telemetry
- EndPiont: '/JobTelemetries'
- Method: 'POST'
- Description: Create a new Job Telementry 
- Body:
  "id": 0,
  "proccesId": "string",
  "jobId": "string",
  "queueId": "string",
  "stepDescription": "string",
  "humanTime": 0,
  "uniqueReference": "string",
  "uniqueReferenceType": "string",
  "businessFunction": "string",
  "geography": "string",
  "excludeFromTimeSaving": true,
  "additionalInfo": "string",
  "entryDate": "2024-08-11T04:23:36.901Z"
  

  ###### Updates JobTelementries 
- EndPiont: '/JobTelemetries/{id}'
- Method: 'PUT'
- Description: update JobTelementry record by ID
- Parameters: 'id' (requied): The ID of the JobTelementries record
- body
  "id": 0,
  "proccesId": "string",
  "jobId": "string",
  "queueId": "string",
  "stepDescription": "string",
  "humanTime": 0,
  "uniqueReference": "string",
  "uniqueReferenceType": "string",
  "businessFunction": "string",
  "geography": "string",
  "excludeFromTimeSaving": true,
  "additionalInfo": "string",
  "entryDate": "2024-08-11T08:57:34.489Z"

  ###### Delete Job Telemetry Record by its ID
- EndPiont: '/JobTelemetries/{id}'
- Method: 'DELETE'
- Description: Delete JobTeletry record by its ID
- Parameters: 'id' (requied): The ID of the Processes record



  ##### Processes
###### get All Processes Records
- EndPiont: '/Processes'
- Method: 'GET'
- Description: Retrieve alist all Processes records
- Parameters:

###### get Job Processes Record by ID
- EndPiont: '/Processes/{id}'
- Method: 'GET'
- Description: Retrieve  a single Processes record by it ID
- Parameters: 'id' (requied): The ID of the Processes record

###### get Job Processes Record by ID
- EndPiont: '/Processes/{id}'
- Method: 'GET'
- Description: Retrieve  a single Processes record by it ID
- Parameters: 'id' (requied): The ID of the Processes record

  ###### Create new Proces
- EndPiont: '/Processes'
- Method: 'POST'
- Description: Create a new Proces 
- Body:
  "processId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "processName": "string",
  "processType": "string",
  "isFramework": true,
  "requiresDefaultConfig": true,
  "submitter": "string",
  "dateSubmitted": "2024-08-11T09:07:03.292Z",
  "processConfigUrl": "string",
  "reportUrl": "string",
  "projectId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "defaultGeography": "string",
  "defaultBusinessFunction": "string",
  "platform": "string"
  

  ###### Updates Processes
- EndPiont: '/Processes/{id}'
- Method: 'PUT'
- Description: update Processes record by ID
- Parameters: 'id' (requied): The ID of the Processes record
- body
  "processId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "processName": "string",
  "processType": "string",
  "isFramework": true,
  "requiresDefaultConfig": true,
  "submitter": "string",
  "dateSubmitted": "2024-08-11T09:09:20.174Z",
  "processConfigUrl": "string",
  "reportUrl": "string",
  "projectId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "defaultGeography": "string",
  "defaultBusinessFunction": "string",
  "platform": "string"

  ###### Delete Processes Record by its ID
- EndPiont: '/Processes/{id}'
- Method: 'DELETE'
- Description: Delete Process record by its ID
- Parameters: 'id' (requied): The ID of the Processes record

 #####  Projects
###### get All  Projects Records
- EndPiont: '/ Projects'
- Method: 'GET'
- Description: Retrieve alist all  Projects records
- Parameters:

###### get Projects Record by ID
- EndPiont: '/ Projects/{id}'
- Method: 'GET'
- Description: Retrieve  a single  Projects record by it ID
- Parameters: 'id' (requied): The ID of the  Projects record

###### get Projects Record by ID
- EndPiont: '/Projects/{id}'
- Method: 'GET'
- Description: Retrieve  a single  Projects record by it ID
- Parameters: 'id' (requied): The ID of the  Projects record

  ###### Create new  Projects
- EndPiont: '/ Projects'
- Method: 'POST'
- Description: Create a new Project 
- Body:
  "projectId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "projectName": "string",
  "projectDescription": "string",
  "projectCreationDate": "2024-08-11T09:18:47.719Z",
  "projectStatus": "string",
  "clientId": "3fa85f64-5717-4562-b3fc-2c963f66afa6"
  

  ###### Updates Projects
- EndPiont: '/Project/{id}'
- Method: 'PUT'
- Description: update Projects record by ID
- Parameters: 'id' (requied): The ID of the Processes record
- body
  
  "projectId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "projectName": "string",
  "projectDescription": "string",
  "projectCreationDate": "2024-08-11T09:17:30.009Z",
  "projectStatus": "string",
  "clientId": "3fa85f64-5717-4562-b3fc-2c963f66afa6"

  ###### Delete Project Record by its ID
- EndPiont: '/Project/{id}'
- Method: 'DELETE'
- Description: Delete Project record by its ID
- Parameters: 'id' (requied): The ID of the Project record

=======================

\
 #####  Clients
###### get All  Clients Records
- EndPiont: '/Clients'
- Method: 'GET'
- Description: Retrieve alist all  Clients records
- Parameters:

###### get   Clients Record by ID
- EndPiont: '/ Clients/{id}'
- Method: 'GET'
- Description: Retrieve  a single  Clients record by it ID
- Parameters: 'id' (requied): The ID of the  Clients record

###### get Clients Record by ID
- EndPiont: '/ Clients/{id}'
- Method: 'GET'
- Description: Retrieve  a single  Client record by it ID
- Parameters: 'id' (requied): The ID of the  Clients record

  ###### Create new  Clients
- EndPiont: '/ Clients'
- Method: 'POST'
- Description: Create a new Clients
- Body:
   "clientId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "clientName": "string",
  "primaryContactEmail": "string",
  "dateOnboarded": "2024-08-11T09:33:47.065Z"
  

  ###### Updates Clients
- EndPiont: '/Clients/{id}'
- Method: 'PUT'
- Description: update Projects record by ID
- Parameters: 'id' (requied): The ID of the Processes record
- body
  
  "clientId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "clientName": "string",
  "primaryContactEmail": "string",
  "dateOnboarded": "2024-08-11T09:34:14.932Z"

  ###### Delete Clients Record by its ID
- EndPiont: '/Clients/{id}'
- Method: 'DELETE'
- Description: Delete Clients record by its ID
- Parameters: 'id' (requied): The ID of the Clients record

#### Error Handling
200 OK: The request has succeeded.
201 Created: The request has succeeded and a new resource has been created as a result.
204 No Content: The server successfully processed the request, but is not returning any content.
400 Bad Request: The server could not understand the request due to invalid syntax.
401 Unauthorized: The client must authenticate itself to get the requested response.
403 Forbidden: The client does not have access rights to the content.
404 Not Found: The server cannot find the requested resource.
409 Conflict: The request conflicts with the current state of the server.
500 Internal Server Error: The server has encountered a situation it doesn't know how to handle.
503 Service Unavailable: The server is not ready to handle the request.

## Referencing 


(2004) What is an API? - application programming interface explained - AWS. Available at: https://aws.amazon.com/what-is/api/ (Accessed: 03 August 2024).

GeeksforGeeks (2024) What is an API (application programming interface), GeeksforGeeks. Available at: https://www.geeksforgeeks.org/what-is-an-api/ (Accessed: 03 August 2024). 

What is an API? - application programming interface explained - AWS. Available at: https://aws.amazon.com/what-is/api/ (Accessed: 03 August 2024). 

Azure Active Directory Authentication for SQL database: Azure (2021) YouTube. Available at: https://youtu.be/4tOpFnR35P0 (Accessed: 4 August 2024).


ASP.NET core web API .NET 6 2022 - 1. Create Project & Quick Tips (2022) YouTube. Available at: https://youtu.be/_8nLSsK5NDo?list=PL82C6-O4XrHdiS10BLh23x71ve9mQCln0 (Accessed: 6 August 2024).


aug CMPG323 Weekly Virtual class API controllers (2023) YouTube. Available at: https://youtu.be/kiSJGGy29fY (Accessed: 20 August 2023


ASP.NET Core - scaffolding with Entity Framework Core (database first approach) (2020) YouTube. Available at: https://youtu.be/SnU4Ulee_NI (Accessed: 4 August 2024).


Create an EF core model from database first (scaffold DB context) (2023) YouTube. Available at: https://youtu.be/SrEjoJ_G6tc (Accessed: 6 August 2024).

