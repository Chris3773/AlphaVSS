AlphaVSS
========

[![Inactively Maintained](https://img.shields.io/badge/Maintenance%20Level-Inactively%20Maintained-yellowgreen.svg)](https://gist.github.com/cheerfulstoic/d107229326a01ff0f333a1d3476e068d)
[![License](https://img.shields.io/github/license/alphaleonis/AlphaVSS)](https://github.com/alphaleonis/AlphaVSS/blob/develop/LICENSE)
[![Build](https://img.shields.io/azure-devops/build/alphaleonis-pp/d105224a-eec8-4a24-a7e2-aea090bdc782/2/develop?logo=azuredevops)](https://dev.azure.com/alphaleonis-pp/AlphaVSS/_build) 
[![Latest](https://img.shields.io/nuget/v/AlphaVSS?color=blue&label=stable&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/AlphaVSS/)
[![Prerelease](https://img.shields.io/nuget/vpre/AlphaVSS?label=prerelease&logo=nuget&cacheSeconds=3600)](https://www.nuget.org/packages/AlphaVSS/)
[![Downloads](https://img.shields.io/nuget/dt/AlphaVSS)](https://www.nuget.org/packages/AlphaVSS/)

AlphaVSS is a .NET class library providing a managed API for the Volume Shadow Copy Service also known as VSS. The Volume Shadow Copy Service is a set of COM interfaces that implements a framework to allow volume backups to be performed while applications on a system continue to write to the volumes.

AlphaVSS, written in C# and C++/CLI provides a managed interface to this API.

The goal of AlphaVSS is to provide an interface that is simple to use from any .NET application, yet provides the full functionality of VSS.

For documentation and more information see [http://alphavss.alphaleonis.com](http://alphavss.alphaleonis.com)

For samples, see https://github.com/alphaleonis/AlphaVSS-Samples
