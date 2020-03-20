# SymptomGard
SymptomGard is a public health map.

## Architecture: 
Generalization: [Frontend] <-> [API] <-> [Backend] 
* Application frontend is a web site
* Application Programming Interface (API)
* Datastore Backend

## Data Flow
### Inputs:
* Health-Survey-Form to API to Datastore
* User-Credential-Form to API to Datastore

### Outputs:
* Datastore to API to Symptom-Map
* Datastore to API to User-Credentials-Form

## Security
* SSL
* Encryption at rest
* Encryption in transit

## Keys (.env)

LB-GOOGLE-MAP-KEY=\<your-google-key\>

LB-API-KEY=\<found-on-User-Credential-Form\>


