# [2.0.1](https://www.nuget.org/packages/Autofac.Extensions.FluentBuilder/2.0.1) (2019-10-10)

## Features

* Update to version `5.0.1` of `Autofac.Extensions.DependencyInjection`
* Add multi-target support for `netstandard2.0` and `netstandard2.1` 

# [2.0.0](https://www.nuget.org/packages/Autofac.Extensions.FluentBuilder/2.0.0) (2019-09-25)

## Features

* Update to latest version of `Autofac.Extensions.DependencyInjection` and adjust samples for `ASP.NET Core` / `.NET-Core` 3.0

# [1.5.0](https://www.nuget.org/packages/Autofac.Extensions.FluentBuilder/1.5.0) (2019-03-17)

## Features

* Add functionality to register typed and none-typed resolver

# [1.4.0](https://www.nuget.org/packages/Autofac.Extensions.FluentBuilder/1.4.0) (2019-03-17)

## Features

* Update Autofac.Extensions.DependencyInjection to version 4.4.0

# [1.3.1](https://www.nuget.org/packages/Autofac.Extensions.FluentBuilder/1.3.1) (2019-03-17)

## Chore

* Add package-icon

# [1.3.0](https://www.nuget.org/packages/Autofac.Extensions.FluentBuilder/1.3.0) (2019-03-17)

## Features

* Update Autofac to version 4.9.1

## Chore

* Adjust copyright notice

# [1.2.0](https://www.nuget.org/packages/Autofac.Extensions.FluentBuilder/1.2.0) (2018-12-11)

## Features

* Update to latest version of Autofac.Extensions.Microsoft.DependencyInjection and  Microsoft.Extensions.DependencyInjection

# [1.1.0](https://www.nuget.org/packages/Autofac.Extensions.FluentBuilder/1.1.0) (2018-08-21)

## Features

* Update to latest Autofac.Extensions.Microsoft.DependencyInjection package

# [1.0.2](https://www.nuget.org/packages/Autofac.Extensions.FluentBuilder/1.0.2) (2018-07-18)

## Bugfixes

* Fix a derp in typeextension that was meant to check for closing types, if it contains a basetype whether it is abstract or not

# [1.0.1](https://www.nuget.org/packages/Autofac.Extensions.FluentBuilder/1.0.1) (2018-07-08)

## Bugfixes

* When registering closed-types with resolved-parameters, parameters are now scoped according to the function (singleton, transient or scoped)

# [1.0.0](https://www.nuget.org/packages/Autofac.Extensions.FluentBuilder/1.0.0) (2018-07-08)

## Features

* Registering types with and without interfaces as scoped-, transient- and single-instances
* Registering instances with a given type
* Registering generics as scoped-, transient- and single-instances
* Registering closed-types using assembly-scanning with possible resolved-parameters as scoped-, transient- and single-instances
* Registering modules with and without parameters
* Type safety for ever function-call 