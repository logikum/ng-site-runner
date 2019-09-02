# ng-site-runner

This application is a simple Node.js server to run Angular applications.

### Step 1

Set up the application:
```
git clone https://github.com/logikum/ng-site-runner.git
```

### Step 2

Set up the configuration or use the default one:
```
{
  "ngSitePath": "dist",
  "startUpPage": "./dist/index.html",
  "logFile": "logs/ng-site-runner.log"
}
```

### Step 3

Copy the compiled Angular app to the '__dist__' folder (or what is set in the configuration).

### Step 4

Start the server:
```
NODE_ENV=production PORT=80 node server.js
```
### Step 5

Enjoy your Angular app...
