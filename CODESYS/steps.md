
Steps of the [tutorial OPC-UA server](https://node-opcua.github.io/tutorial/2015/07/05/weather-station.html#testing-the-rest-api):
+ create a https://rapidapi.com/ account
+ subscribe to the endpoint [Open Weather Map](https://rapidapi.com/community/api/open-weather-map/endpoints)
+ get the "X-RapidAPI-Key" header value
+ run `test_rapidapi_client.bat`
+ run `npm init`
+ run `npm install unirest --save`
+ run `npm install node-opcua --save` (found 29 low severity vulnerabilities)
+ follow the steps in the tutorial (there are some bugs in the tutorial that are easily fixable)
+ run `node test_api_opcua_server.js`
with the above a OPC-UA server is created

Steps of the [tutorial OPC-UA client](https://github.com/node-opcua/node-opcua/blob/v2.1.3/documentation/creating_a_client_typescript.md)
+ install typescript `npm install -g typescript`
+ create a new folder and enter it
+ run `npm init`
+ run `npm install node-opcua-client --save`
+ follow the steps in the tutorial
+ (until now the code fails)