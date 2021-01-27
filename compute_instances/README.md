# App Engine Standard

<b>Constraints</b>

- Can't write to local files
- Timeout is set to 60 seconds

# App Engine Flexible

- No constraints like app engine standard
- No timeout value
- The application is deployed at container

# API Management
<b> Cloud Endpoints </b>

- This is to support the API management and configuration.
- This supports applications running in compute engine, kubernetes engine and app engine flexible.

<b> APIGEE Edge</b>
- Supports Analytics


Cloud Functions
- HTTP Trigger
- Storage Event Trigger
- PubSub trigger

<b>The command to make an HTTP call to cloud function. This function will be triggered like a web hook for each http call</b>
curl https://us-central1-crud-302820.cloudfunctions.net/HelloHTTP -H "Authorization: bearer $(gcloud auth print-identity-token)"
