
# Rodar os testes localmente

```
  $ node lambda.js -f test-local/function.js -e test-local/event.json
```

## Parametros
```
-f functionName     | --function=functionName       required       Path to Lambda function main file
-e eventPath        | --event=eventPath             optional       Path to .json file contains event object
-c contextPath      | --context=contextPath         optional       Path to .json file contains context object
-t seconds          | --timeout=seconds             optional       Force quit Lambda function after XX seconds
```
