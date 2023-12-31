﻿# Cloud Foundry Python  Sample App
This is a sample python flask app for Cloud Foundry (CF). 

## Log-in to CF

> In some case, you need to specify your cf version while you are running 'cf' command e.g. 'cf8' 

Specify your Cloud Foundry Environment API Endpoint 
```zsh
foo@bar:~$ cf api <--CF API ENDPOINT LINK-->
```
```plain
Setting API endpoint to <--CF API ENDPOINT LINK-->...
OK

API endpoint:   <--CF API ENDPOINT LINK-->
API version:    3.144.0

Not logged in. Use 'cf8 login' or 'cf8 login --sso' to log in.
```

Run command below and enter your email and password to login 
```zsh
foo@bar:~$ cf login
```
```plain
API endpoint: <--CF API ENDPOINT LINK-->

Email: <--YOUR EMAIL-->
Password:

Authenticating...
OK

Targeted org e89e824678851232.

Targeted space dev.

API endpoint:   <--CF API ENDPOINT LINK-->
API version:    3.144.0
user:           <--YOUR EMAIL-->
org:            e89e824678851232
space:          dev

```



## Deploy to CF
Before deploying, enter the folder that you clone this repository. 

    cf push

