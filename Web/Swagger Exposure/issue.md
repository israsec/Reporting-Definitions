We discovered an exposed Swagger definition for the application's API. While this in and of itself may not constitute a vulnerability, it may help an attacker enumerate potential weaknesses in the API. This is essentially, giving an attacker a head start on attacking your API. If the API is meant to be publicly accessible  (for example for the integration of 3rd party app) then exposing the Swagger is necessary and does not represent a vulnerability.  
If however, the API does not need to be exposed for functionality, the best practice is to close access to the Swagger documentation. 