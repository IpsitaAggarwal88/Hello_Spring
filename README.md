# Hello_Spring

Playbook:
- to compile the application: go to the root folder of the app (the one where /src and POM file are) and type "mvn package".
- to run: in the same folder, type java -jar target\gs-rest-service-0.1.0.jar
- to test:
  - 1. make sure you have the VSCode rest client installed.
  - 2. Open testRequest.rest
  - Above the GET you will see "Send Request" link. Click it to send the request to your app, in the other window you will see the response
- to debug: simply press F5 in your VSCode. First time it will open the "launch.json" file; don't edit it, just close and press F5 again. VSCode should compile and start app for you, and you can set breakpoints etc.

next steps: great stuff!! Now, try to create a service Hello(param), Autowire this service to the controller using a bean and run the entire thing
