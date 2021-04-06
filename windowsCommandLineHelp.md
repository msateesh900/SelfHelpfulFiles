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



### Step 1:

Open up cmd.exe (note: you may need to run it as an administrator, but this isn't always necessary), then run the below command:
```
netstat -ano | findstr :<PORT>
```
(Replace <PORT> with the port number you want, but keep the colon)

The area circled in red shows the PID (process identifier). Locate the PID of the process that's using the port you want.

### Step 2:

Next, run the following command:
```
taskkill /PID <PID> /F
```
Lastly, you can check whether the operation succeeded or not by re-running the command in **"Step 1"**. If it was successful you shouldn't see any more search results for that port number.

[Source](https://stackoverflow.com/questions/39632667/how-do-i-kill-the-process-currently-using-a-port-on-localhost-in-windows)
