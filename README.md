# testCICD.NET
testCICD.NET
[![Build status](https://ci.appveyor.com/api/projects/status/ostfr4ckyljomno9?svg=true)](https://ci.appveyor.com/project/son0nline/testcicd-net)

rule setting 
https://www.appveyor.com/docs/deployment/github/


config build test
https://github.com/son0nline/testCICD.NET/releases

https://github.com/settings/tokens



config deploy

https://www.appveyor.com/docs/appveyor-yml/

artifacts:
- path: dist/installers/*.exe
  name: myartifact
deploy:
  artifacts: myartifact