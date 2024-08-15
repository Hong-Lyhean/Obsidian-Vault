2024-08-07 10:34

Status: #Completed 

Tags: [[C Sharp Programming]]

Source: 
# 1 - Set up and Overview

### Install SDK
``` bash
sudo apt-get install -y dotnet-sdk-8.0
```

### Install runtime
To install runtime that include ASP.net 
``` bash
sudo apt-get install -y aspnetcore-runtime-8.0
```

To install runtime that don't include ASP.net
``` bash
sudo apt-get install -y dotnet-runtime-8.0
```

### Create new project
Console application
``` bash
dotnet new console
```
this command will create project in current folder

with specific dot-net version
``` bash
dotnet new console --framework net8.0 --use-program-main
```
this command will create project in current folder

create project in new folder with specific project name
``` bash
dotnet new console -n MyNewProject
```
`-n` option was to specify the project name

### Run the project
Console application
``` bash
donet run
```


# References

