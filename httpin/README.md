# httpin

**httpin** - Decode an HTTP request into a custom struct, including querystring, forms, HTTP headers, etc.

Documentation: https://ggicci.github.io/httpin/

Integrate with chi: https://ggicci.github.io/httpin/integrations/gochi.

## Run this example

```bash
# start the http server
go run main.go


curl -H "Authorization: abc" "http://localhost:3333/users/ggicci/repos?visibility=private&fork=1"
# Output:
# {"Username":"ggicci","Visibility":"private","Fork":true,"Token":"abc"}
```
