README.md

An HTTP triggered Azure Function demo created by using Azure Functions Core Tools.

Steps:
1. Create folder

```bash
mkdir ~/HttpTriggeredAzureFunction
cd ~/HttpTriggeredAzureFunction
```

2. Initialize directory

```bash
func init
```

choose "**dotnet**"

3. Create an HTTP-triggered function

```bash
func new
```

choose "**HTTP trigger**", enter function name as "**Hello**"

4. Run app

```bash
func start
```

```
Azure Functions Core Tools
Core Tools Version:       3.0.2996 Commit hash: c54cdc36323e9543ba11fb61dd107616e9022bba
Function Runtime Version: 3.0.14916.0


Functions:

        Hello: [GET,POST] http://localhost:7071/api/Hello

For detailed output, run func with --verbose flag.
```

5. Test api, open link _http://localhost:7071/api/Hello?name=Azure_ in browser

