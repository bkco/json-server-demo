json-server-demo
====
Node.js server providing a REST api. Run options are:

1.	json-server db.json			
2.	json-server generate.js

View data:
curl -X GET -H "Content-Type: application/json" http://localhost:3000/people

## Installation
    git clone https://github.com/bkco/json-server-demo/ json-server-demo

    npm install json-server
    npm install faker
    npm install lodash

## Serve Static Content

Static resources can be served from a "public" directory on the server e.g HTML5 projects.

cd json-server-demo  
mkdir public  
cd public  
ln -s  /path/to/code/project/* /location/of/json-server-demo/public/  