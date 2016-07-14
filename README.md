# AlexaDomoticz
Using Alexa Skill to communicate to a lambda server. The lambda server sends HTTP requests to the domoticz server for calling events.
<br>
<br>
On AWS Lambda:<br>
-Copy/paste the code. Modify the username, password, IP address, and port to your location. If using HTTP instead of HTTPS, then make changes accordingly throughout the code.<br>
-Alexa Skills Kit (ASK) trigger<br>
-Runtime: Node.js<br>
<br>
Alexa Skills Kit: https://developer.amazon.com/edw/home.html#/skills/list<br>
-Invocation name: 'my home'<br>
-Interaction Model:<br>
    -Custom slot types<br>
      Type	Values	<br>
          LIST_OF_LIGHTS	living room | master bedroom | bedroom | hallway | office | all<br>
    -Sample utterances: see document<br>
    -Schema: see document<br>
-Configuration<br>
    -Endpoint: lambda ARN: arn:aws:lambda:us-east-1:XXXXXXX:function:Automation<br>
    
    
