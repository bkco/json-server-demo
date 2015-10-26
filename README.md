json-server-demo
====
A nodejs server providing a REST api. Run as:
1.	json-server db.json			// loads json data
2.	json-server generate.js		// creates data on the fly

Access data:
curl -X GET -H "Content-Type: application/json" http://localhost:3000/people

