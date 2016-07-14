# AlexaDomoticz
Using Alexa Skill to communicate to a lambda server. The lambda server sends HTTP requests to the domoticz server for calling events.


On AWS Lambda:
-Copy/paste the code. Modify the username, password, IP address, and port to your location. If using HTTP instead of HTTPS, then make changes accordingly throughout the code.
-Alexa Skills Kit (ASK) trigger
-Runtime: Node.js

Alexa Skills Kit: https://developer.amazon.com/edw/home.html#/skills/list
-Invocation name: 'my home'
-Interaction Model:
    -Custom slot types
      Type	Values	
          LIST_OF_LIGHTS	living room | master bedroom | bedroom | hallway | office | all
    -Sample utterances: see document
    -Schema: see document
-Configuration
    -Endpoint: lambda ARN: arn:aws:lambda:us-east-1:XXXXXXX:function:Automation
    
    
