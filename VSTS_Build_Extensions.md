10/23/2017

# Build Extensions

## Tips for Writing Powershell Scripts for Build Tasks
https://blogs.msdn.microsoft.com/premier_developer/2016/04/13/tips-for-writing-powershell-scripts-to-use-in-build-and-release-tasks/
   - To set a variable in one PowerShell task and access the updated value in subsequent tasks you need to use a special command: Write-Host "##vso[task.setvariable variable=DynamicVariable]Persistent Value Set In Script"
   - use of '##' explained in https://docs.microsoft.com/en-us/vsts/build-release/concepts/definitions/build/variables?tabs=batch
   
   
## Authentication
https://docs.microsoft.com/en-us/vsts/extend/develop/auth-schemes

## VSTS Tasks github repo
https://github.com/Microsoft/vsts-tasks/tree/master/Tasks

## Channel 9 - Build Custom Tasks, subject Octopus Deploy
https://channel9.msdn.com/Blogs/MVPANZ/Team-Foundation-Build-Custom-Tasks

## VSTS Task SDK
https://github.com/Microsoft/vsts-task-lib/tree/master/powershell/Docs

