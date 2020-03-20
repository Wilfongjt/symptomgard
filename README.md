# SymptomGard
SymptomGard is a public health map.

# Architecture: 
Generalization: [Frontend] <-> [API] <-> [Backend] 
* Application frontend is a web site
* Application Programming Interface (API)
* Data Store Backend

# Data Flow
## Inputs:
* Health-Survey-Form to API to Datastore
* User-Credential-Form to API to Datastore

## Outputs:
* Datastore to API to Symptom-Map
* Datastore to API to User-Credentials-Form

# Security
* SSL
* Encryption at rest
* Encryption in transit
