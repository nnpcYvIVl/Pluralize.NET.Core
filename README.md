[![Build Status](https://travis-ci.org/sarathkcm/Pluralize.NET.svg?branch=master)](https://travis-ci.org/sarathkcm/Pluralize.NET)  [![NuGet version](https://badge.fury.io/nu/pluralize.net.svg)](https://www.nuget.org/packages/pluralize.net)
# What is it?
This is a C# port of Blake Embrey's [pluralize](https://github.com/blakeembrey/pluralize) library which helps in pluralizing and singularize any English word.
# Why
I could not find a good C# alternative for converting words from singular to plural and vice versa. [System.Data.Entity.Design.PluralizationServices.PluralizationService](https://msdn.microsoft.com/en-us/library/system.data.entity.design.pluralizationservices.pluralizationservice(v=vs.110).aspx) and [Humanizer](http://humanizr.net/) library did not meet the expectations (try 'shoes' or 'toes'). However this small but awesome Javascript libray [pluralize](https://github.com/blakeembrey/pluralize) worked very well for me and I decided to convert the code to C# and use it.
# How
**Install from NuGet**
```
Install-Package Pluralize.NET
```

**Include using directive**
```
using Pluralize.NET
```
**Write code**
```
var singular = new Pluralizer().Singularize("Horses");
var plural = new Pluralizer().Pluralize("Horse");
```

**Profit!**

# Licence
[MIT](https://github.com/sarathkcm/Pluralize.NET/blob/master/LICENCE) - because the original project is MIT
