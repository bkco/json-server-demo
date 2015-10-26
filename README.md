json-server-demo
====
Node.js server providing a REST api. Run options are:

1.	json-server db.json			
2.	json-server generate.js

View data:
curl -X GET -H "Content-Type: application/json" http://localhost:3000/people

Static resources can be served from a "public" directory on the server e.g HTML5 projects.

