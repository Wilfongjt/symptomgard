# SymptomGard
SymptomGard is a public health map.  Uses a simple survey to collect symptoms and risk factors. Data is then displayed on a map.  

The seed of this idea comes from https://healthweather.us where data from internet connected thermometers is mapped and is helping predict the next hot spot for the covid virus. Of course, we can't create our own thermometer but we can create a survey to collect and map symptoms.  

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


