# Windows Power Shell Commands
### To find list of services running on specific port on windows
```
Syntax: netstat -ano | findstr :<PORT>
Eg:     netstat -ano | findStr "8080"
```
### Kill the port/service in windows
```
Syntax: taskkill /PID <PID> /F
Eg:     taskkill /PID 8080 /F
```
