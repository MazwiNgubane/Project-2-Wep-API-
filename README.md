# CMPG-323-Project-2-30336570
## web API

### Overview
The NWU Tech Trends API allows users to manage telemetry data for automation systems, tracking time saved, and associating it with projects and clients. This API supports CRUD operations on projects, clients, and telemetry records.

#### Base URL

#### Endpoints
##### Telemetry
####### get All Job Telemetry Records
- EndPiont: '/JobTelemetelemetries'
- Method: 'GET'
- Description: Retrieve alist all teletry records
- Parameters:

####### get Job Telemetry Record by ID
- EndPiont: '/JobTelemetries/{id}'
- Method: 'GET'
- Description: Retrieve  a single JobTeletry record by it ID
- Parameters: 'id' (requied): The ID of the JobTelementries record

####### get Job Telemetry Record by ID
- EndPiont: '/JobTelemetries/{id}'
- Method: 'GET'
- Description: Retrieve  a single JobTeletry record by it ID
- Parameters: 'id' (requied): The ID of the JobTelementries record

  ####### Create new Job Telemetry
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
  

  ####### get Job Telemetry Record by ID
- EndPiont: '/JobTelemetries/{id}'
- Method: 'GET'
- Description: Retrieve  a single JobTeletry record by it ID
- Parameters: 'id' (requied): The ID of the JobTelementries record
