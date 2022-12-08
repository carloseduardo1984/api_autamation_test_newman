# Mod4w5

## api_autamation_test_newman
===============================================


Guidence:

Do the Export files about the Postman Collection and environment as JSON format.
https://www.postman.com/qadreamteam2022/workspace/e7467091-c662-40e6-83a9-678f20813eb5/overview 


To install  newman in to Vscode > npm install -g newman  newman-reporter-htmlextra   

Tö run > newman run example.postman_collection.json -e workspace.postman_globals.json

To run with html report > newman run example.postman_collection.json -e workspace.postman_globals.json -r htmlextra --reporter-htmlextra-export testResults/htmlreport.html

( Tip for Actions setup: https://crontab.guru/) 
