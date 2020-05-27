# graph_tutorial
A graph tuorial using Python - extended to read Planner tasks

This is based on the sample from https://docs.microsoft.com/en-us/graph/tutorials/python
The file oauth_settings.yml is not included in the repo but should look like the following:

app_id: "YOUR_APP_ID_HERE"

app_secret: "YOUR_APP_PASSWORD_HERE"

redirect: "http://localhost:8000/callback"

scopes: "openid profile offline_access user.read calendars.read"

authority: "https://login.microsoftonline.com/common"

authorize_endpoint: "/oauth2/v2.0/authorize"

token_endpoint: "/oauth2/v2.0/token"
