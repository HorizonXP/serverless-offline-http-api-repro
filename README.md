### Reproduction steps

```
npm install
serverless dynamodb install
serverless offline start
```

```
curl -X POST -H "Content-Type:application/json" http://localhost:3000/ --data '{ "email": "test@example.com" }'
```

Observe:
```
{"statusCode":404,"error":"Serverless-offline: route not found.","currentRoute":"post - /","existingRoutes":[]}
```
