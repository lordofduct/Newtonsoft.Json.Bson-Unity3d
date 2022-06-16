# ![Logo](Doc/logo.jpg) Json.NET BSON for Unity3d

This is a port of Newtonsoft.Json.Bson to work as a package in Unity3d with dependency on the Unity port of Newtonsoft.Json done by Unity themselves found here:
https://docs.unity3d.com/Packages/com.unity.nuget.newtonsoft-json@2.0/manual/index.html

To add to your project, open the package manager and click the + button, select 'Add pacakage from git-url', and paste in the git url of this project:
https://github.com/lordofduct/Newtonsoft.Json.Bson-Unity3d.git

Note that this project does not work with many unity objects right out the gate do to circular references on the types like Vector3. This same issue exists in the unity Newtonsoft-Json package as well. Personally I usually add a contract resolver which only writes properties that are read/write.

[![NuGet version (Newtonsoft.Json.Bson)](https://img.shields.io/nuget/v/Newtonsoft.Json.Bson.svg?style=flat-square)](https://www.nuget.org/packages/Newtonsoft.Json.Bson/)
[![Build Status](https://dev.azure.com/jamesnk/Public/_apis/build/status/JamesNK.Newtonsoft.Json.Bson?branchName=master)](https://dev.azure.com/jamesnk/Public/_build/latest?definitionId=9)

- [Homepage](https://www.newtonsoft.com/json)
- [Documentation](https://www.newtonsoft.com/json/help)
- [NuGet Package](https://www.nuget.org/packages/Newtonsoft.Json.Bson)
- [Release Notes](https://github.com/JamesNK/Newtonsoft.Json.Bson/releases)
- [License](LICENSE.md)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/json.net)
