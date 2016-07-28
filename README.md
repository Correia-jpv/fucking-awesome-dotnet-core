# Awesome .NET Core Collection [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of awesome .NET Core frameworks, libraries, tools, resources and software.

Inspired by [awesome](https://github.com/sindresorhus/awesome), [awesome-dotnet](https://github.com/quozd/awesome-dotnet),  [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs), [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks).

Contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/thangchung/awesome-dotnet-core/blob/master/CONTRIBUTING.md) pages first. We accept proprietary and commercial software too.

Thanks to all [contributors](https://github.com/thangchung/awesome-dotnet-core/graphs/contributors), you're awesome and wouldn't be possible without you! The goal is to build a categorized community-driven collection of very well-known resources.

* [Frameworks, Libraries and Tools](#frameworks-libraries-and-tools)
  * [API](#api)
  * [Application Frameworks](#application-frameworks)
  * [Application Templates](#application-templates)
  * [Authentication and Authorization](#authentication-and-authorization)
  * [Build Automation](#build-automation)
  * [Bundling and Minification](#bundling-and-minification)
  * [Caching](#caching)
  * [Cryptography](#cryptography)
  * [CMS](#cms)
  * [Code Analysis and Metrics](#code-analysis-and-metrics)
  * [Database Drivers](#database-drivers)
  * [E-Commerce and Payments](#e-commerce-and-payments)
  * [Graphics](#graphics)
  * [Functional Reactive Programming](#functional-reactive-programming)
  * [IDE](#ide)
  * [Internationalization](#internationalization)
  * [IOC](#ioc)
  * [Logging](#logging)
  * [Mail](#mail)
  * [Misc](#misc)
  * [ORM](#orm)
  * [Profiling](#profiling)
  * [Queue and Messaging](#queue-and-messaging)
  * [Scheduler and Job](#scheduler-and-job)
  * [SDKs](#sdks)
  * [Security](#security)
  * [Searching](#searching)
  * [Serialization](#serialization)
  * [Testing](#testing)
  * [Web Framework](#web-framework)
  * [Web Socket](#web-socket)
  * [Windows Service](#windows-service)
* [Starter Kits](#starter-kits)
* [Sample Projects](#sample-projects)
* [Best Articles](#best-articles)

# Frameworks, Libraries and Tools

## API
* [autorest](https://github.com/Azure/autorest) - A Swagger (OpenAPI) Specification code generator featuring C# and Razor templates. Supports C#, Java, Node.js, TypeScript, Python and Ruby. `only works for 4.5.1`
* [LightNode](https://github.com/neuecc/LightNode) - A Micro RPC/REST Framework built on OWIN [http://neuecc.github.io/LightNode](http://neuecc.github.io/LightNode).
* [Swashbuckle](https://github.com/domaindrivendev/Ahoy) - Seamlessly adds a swagger to WebApi projects.
* [WebAPIContrib for ASP.NET CORE](https://github.com/WebApiContrib/WebAPIContrib.Core) - A collection of open source projects, add-ons and extensions to help improve your work with ASP.NET Core and ASP.NET Core MVC.
* [graphql-dotnetcore](https://github.com/mkmarek/graphql-dotnetcore) - GraphQL for .NET core based on [https://github.com/graphql/graphql-js](https://github.com/graphql/graphql-js)

## Application Frameworks
* [ASP.NET MVC](https://github.com/aspnet/Mvc) - A model view controller framework for building dynamic web sites with clean separation of concerns, including the merged MVC, Web API, and Web Pages w/ Razor.
* [Nancy](https://github.com/NancyFx/Nancy) - A lightweight, low-ceremony, framework for building HTTP based services on .Net and Mono.
* [ExtCore](https://github.com/ExtCore) - A Free, open source and cross-platform framework for creating modular and extendable web applications based on ASP.NET Core 1.0.

## Application Templates
* [ASP.NET MVC Boilerplate](https://github.com/RehanSaeed/ASP.NET-MVC-Boilerplate) - A professional ASP.NET MVC template for building secure, fast, robust and adaptable web applications or sites. It provides the minimum amount of code required on top of the default MVC template provided by Microsoft.

## Authentication and Authorization
* [Identity](https://github.com/aspnet/Identity) - ASP.NET Core Identity is the membership system for building ASP.NET Core web applications, including membership, login, and user data.
* [IdentityServer](https://github.com/IdentityServer/IdentityServer4) - IdentityServer for ASP.NET Core 1.0
 * [20|20 IdentityServer4.EntityFrameworkCore](https://github.com/2020IP/TwentyTwenty.IdentityServer4.EntityFrameworkCore) - An Entity Framework Core persistence layer for IdentityServer v4.
* [openiddict](https://github.com/openiddict/openiddict-core) - Easy-to-use OpenID Connect server for ASP.NET Core.
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) - Build [simple, secure web applications](https://github.com/stormpath/stormpath-aspnetcore) with Stormpath and ASP.NET Core.

## Build Automation
* [cake-build](https://github.com/cake-build/cake) - A cross platform build automation system. [http://cakebuild.net](http://cakebuild.net)
* [Colorful.Console](https://github.com/tomakita/Colorful.Console) - Style your C# console output! [http://colorfulconsole.com](http://colorfulconsole.com)
* [msbuild](https://github.com/Microsoft/msbuild) - The Microsoft Build Engine is a platform for building applications.
* [vsts-agent](https://github.com/Microsoft/vsts-agent/blob/master/README.md) - Visual Studio Team Services Build and Release Agent.

## Bundling and Minification
* [BundlerMinifier](https://github.com/madskristensen/BundlerMinifier) - A Visual Studio extension that let's you configure bundling and minification of JS, CSS and HTML files.
* [Smidge](https://github.com/Shazwazza/Smidge/) - A lightweight runtime CSS/JavaScript file minification, combination, compression & management library for ASP.Net Core.

## Caching
* [CacheManager](https://github.com/MichaCo/CacheManager) - an open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features. [http://cachemanager.net](http://cachemanager.net)
* [Microsoft Caching](https://github.com/aspnet/Caching) - Libraries for in-memory caching and distributed caching.
* [Stack Exchange Redis](https://github.com/StackExchange/StackExchange.Redis) - A high performance general purpose redis client for .NET languages (C# etc).

## Cryptography
* [BouncyCastle PCL](https://github.com/onovotny/BouncyCastle-PCL) - The Bouncy Castle Crypto package is a C# implementation of cryptographic algorithms and protocols.

## CMS
* [OrchardCMS2](https://github.com/OrchardCMS/Orchard2) - An implementation of Orchard CMS in ASP.NET Core (also known as DNX).
* [Platformus](https://github.com/Platformus) - A free, open source and cross-platform CMS based on ASP.NET Core 1.0 and ExtCore framework.

## Code Analysis and Metrics
* [OpenCover](https://github.com/OpenCover/opencover) - A code coverage tool for .NET 2 and above (WINDOWS OS only), support for 32 and 64 processes with both branch and sequence points.

## Database Drivers
* [MongoDB.Driver](https://github.com/mongodb/mongo-csharp-driver) - .NET Driver for MongoDB. `only works for 4.5.x`
* [Neo4jClient](https://github.com/Readify/Neo4jClient/tree/DotNetCore) - A .NET client binding for Neo4j.
* [npgsql](https://github.com/npgsql/npgsql) - A .NET data provider for PostgreSQL. It allows any program developed for .NET framework to access a PostgreSQL database server. It is implemented in 100% C# code. PostgreSQL versions since 9.1 are officially supported, others may work. [http://www.npgsql.org](http://www.npgsql.org)
* [ravendb](https://github.com/ayende/ravendb/tree/v4.0) - A linq enabled document database for .NET.
* [RethinkDb.Driver](https://github.com/bchavez/RethinkDb.Driver) - A C#/.NET RethinkDB driver with 100% ReQL API coverage.

## E-Commerce and Payments
* [SimplCommerce](https://github.com/simplcommerce/SimplCommerce) - A super simple ecommerce system built on .NET Core.

## Graphics
* [ImageProcessor](https://github.com/JimBobSquarePants/ImageProcessor) - A cross-platform library for processing of image files written in C# [http://imageprocessor.org](http://imageprocessor.org)

## Functional Reactive Programming
* [Rx.NET](https://github.com/Reactive-Extensions/Rx.NET) - The [Reactive Extensions](http://reactivex.io) for .NET.
* [sodium](https://github.com/SodiumFRP/sodium/tree/master/c%23) - A Functional Reactive Programming (FRP) Library. `only works for 4.5.x`

## IDE
* [rider](https://www.jetbrains.com/rider/) - A cross-platform C# IDE based on the IntelliJ platform and ReSharper.
* [Omnisharp](http://www.omnisharp.net/) - a family of Open Source projects, each with one goal: To enable a great .NET experience in YOUR editor of choice.
* [Visual Studio Code](https://github.com/Microsoft/vscode) - A new type of tool that combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle. Code provides comprehensive editing and debugging support, an extensibility model, and lightweight integration with existing tools.
* [Visual Studio Community](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx) - A free editor for individual developers, open source projects, academic research, education, and small professional teams.

## Internationalization
* [Localization](https://github.com/aspnet/Localization) - Localization abstractions and implementations for ASP.NET Core applications.
* [nodatime](https://github.com/nodatime/nodatime) - A better date and time API for .NET [http://nodatime.org](http://nodatime.org).

## IOC
* [Autofac](https://github.com/autofac/Autofac) - An addictive .NET IoC container.
* [DryIoc](https://bitbucket.org/dadhi/dryioc) - A fast, small, full-featured IoC Container for .NET.
* [LightInject](https://github.com/seesharper/LightInject) - An ultra lightweight IoC container [http://www.lightinject.net](http://www.lightinject.net).
* [SimpleInjector](https://github.com/simpleinjector/SimpleInjector) - An easy, flexible, and fast Dependency Injection library that promotes best practice to steer developers towards the pit of success.
* [StructureMap](https://github.com/structuremap/structuremap.dnx) - A Dependency Injection/Inversion of Control tool for .NET.

## Logging
* [common-logging](https://github.com/net-commons/common-logging) - A portable logging abstraction for .NET [http://net-commons.github.io/common-logging](http://net-commons.github.io/common-logging)
* [dnxcore-logging-logstash](https://github.com/jvandevelde/dnxcore-logging-logstash) - A Logstash logging extension for .NET Core applications with UDP and Redis transports.
* [serilog](https://github.com/serilog/serilog) - Simple .NET logging with fully-structured events.
* [NLog](https://github.com/NLog/NLog) - Advanced .NET, Silverlight and Xamarin Logging.
* [Q42.Logging.ApplicationInsights](https://github.com/Q42/Q42.Logging.ApplicationInsights) - Log appender for the build in ASP.Net Core logging to send all logs to Application Insights.

## Mail
* [MailKit](https://github.com/jstedfast/MailKit) - A cross-platform .NET library for IMAP, POP3, and SMTP.
* [PreMailer.Net](https://github.com/milkshakesoftware/PreMailer.Net/tree/dotnet-core) - C# library that moves your stylesheets to inline style attributes, for maximum compatibility with E-mail clients.
* [MimeKit](https://github.com/jstedfast/MimeKit) - A cross-platform .NET MIME creation and parser library with support for S/MIME, PGP, DKIM, TNEF and Unix mbox spools.

## Misc
* [AutoMapper](https://github.com/AutoMapper/AutoMapper) - A convention-based object-object mapper in .NET.
* [Castle.Core](https://github.com/castleproject/Core/tree/netcore) - Castle Core, including Castle DynamicProxy, Logging Services and DictionaryAdapter [http://www.castleproject.org](http://www.castleproject.org).
* [CommonMark.NET](https://github.com/Knagis/CommonMark.NET) - An implementation of CommonMark specification in C# for converting Markdown documents to HTML.
* [consuldotnet](https://github.com/PlayFab/consuldotnet/tree/develop) - A .NET API for Consul.
* [datatables](https://github.com/ALMMa/datatables.aspnet/tree/dev) - A Microsoft Asp.Net server-side support and helpers for jQuery DataTables.
* [Docker.DotNet](https://github.com/Microsoft/Docker.DotNet) - A .NET (C#) Client Library for Docker API.
* [FluentValidation](https://github.com/JeremySkinner/FluentValidation) - A small validation library for .NET that uses a fluent interface and lambda expressions for building validation rules.
* [markdig](https://github.com/lunet-io/markdig) - A fast, powerfull, CommonMark compliant, extensible Markdown processor for .NET.
* [Microphone](https://github.com/rogeralsing/Microphone) - A lightweight framework to run self hosting REST services using Web Api or NancyFx ontop of a Consul or ETCD cluster.
* [NReco.LambdaParser](https://github.com/nreco/lambdaparser) - A parses string expressions (formulas, methods calls, conditions) to LINQ expression tree that can be compiled to lambda and evaluated. 
* [NReco.PivotData](https://www.nuget.org/packages/NReco.PivotData/) - An in-memory data cube with OLAP operations and PivotTable data model.
* [reCAPTCHA](https://github.com/PaulMiami/reCAPTCHA) - A reCAPTCHA 2.0 for ASPNET Core.
* [Polly](https://github.com/App-vNext/Polly) - Polly is a .NET 3.5 / 4.0 / 4.5 / PCL library that allows developers to express transient exception and fault handling policies such as Retry, Retry Forever, Wait and Retry or Circuit Breaker in a fluent manner.
* [Scrutor](https://github.com/khellang/Scrutor) - An assembly scanning extensions for Microsoft.Extensions.DependencyInjection.

## ORM
* [Entity Framework Core](https://github.com/aspnet/EntityFramework) - A familiar developer experience to previous versions of EF, including LINQ, POCO, and Code First support.
* [Dapper](https://github.com/StackExchange/dapper-dot-net/tree/netstandard) - A simple object mapper for .NET.
 * [Dapper-FluentMap](https://github.com/henkmollema/Dapper-FluentMap) - Provides a simple API to fluently map POCO properties to database columns when using Dapper.
 * [Dommel](https://github.com/henkmollema/Dommel) - Simple CRUD operations for Dapper.
* [NoDb](https://github.com/joeaudette/NoDb) - A "no database" file system storage for .NET Core/ASP.NET Core because not every project needs a database.
* [NReco.Data](https://github.com/nreco/data) - A lightweight provider-independent DAL for SQL commands generation, CRUD operations and simple POCO mapping.
* [yessql](https://github.com/sebastienros/yessql) - A .NET document database working on any RDBMS.
* [Limebean](https://nick-lucas.github.io/LimeBean/) - A Hybrid-ORM, designed to be simple to use and not totally hide SQL, while having all the nice things you expect from an ORM. Inspired by RedBeanPHP.

## Profiling
* [Glimpse](http://getglimpse.com) - A lightweight, open-source, real-time diagnostics and insights profiler for .NET. 

## Queue and Messaging
* [MediatR](https://github.com/jbogard/MediatR) - Simple, unambitious mediator implementation in .NET.
 * [MediatR.Extensions.Microsoft.DependencyInjection](https://github.com/jbogard/MediatR.Extensions.Microsoft.DependencyInjection) - A MediatR extensions for Microsoft.Extensions.DependencyInjection.
* [MicroBus](https://github.com/Lavinski/Enexure.MicroBus) - MicroBus is a simple in process mediator for .NET.
* [rabbitmq-dotnet-client](https://github.com/rabbitmq/rabbitmq-dotnet-client) - RabbitMQ .NET client [https://www.rabbitmq.com](https://www.rabbitmq.com).
* [netmq](https://github.com/zeromq/netmq) - A 100% native C# implementation of ZeroMQ for .NET.

## Scheduler and Job
* [HangfireIO](https://github.com/HangfireIO/Hangfire) - An easy way to perform fire-and-forget, delayed and recurring tasks inside ASP.NET apps [http://hangfire.io](http://hangfire.io).
* [quartznet](https://github.com/quartznet/quartznet/tree/quartznet-3) - A Quartz Enterprise Scheduler .NET [http://www.quartz-scheduler.net](http://www.quartz-scheduler.net)
* [Chroniton.NetCore](https://github.com/leosperry/Chroniton) - A lightweight robust library for running tasks(jobs) on schedules. 

## SDKs
* [NetTelegramBotApi](https://github.com/justdmitry/NetTelegramBotApi) - A C# client library for building Telegram bot [https://core.telegram.org/bots/api](https://core.telegram.org/bots/api).
* [octokit.net](https://github.com/octokit/octokit.net/tree/target-the-coreclr) - A GitHub API client library for .NET.

## Security
* [Security](https://github.com/aspnet/Security) - Middleware for security and authorization of web apps.

## Searching
* [Elasticsearch.Net & NEST](https://github.com/elastic/elasticsearch-net) - A repository for both NEST and Elasticsearch.Net, the two official elasticsearch .NET clients.
* [ElasticsearchCRUD](https://github.com/damienbod/ElasticsearchCRUD) - Elasticsearch .NET API.
* [AngleSharp](https://github.com/AngleSharp/AngleSharp) - The ultimate angle brackets parser library. It parses HTML5, MathML, SVG and CSS to construct a DOM based on the official W3C specification. Comparable to beautifulsoup4 of python.

## Serialization
* [CsvHelper](https://github.com/JoshClose/CsvHelper) - A library to help reading and writing CSV files [http://csvhelper.com](http://csvhelper.com).
* [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json) - A popular high-performance JSON framework for .NET.
* [protobuf-net](https://github.com/mgravell/protobuf-net/) - A Protocol Buffers library for idiomatic .NET.
* [TinyCsvParser](https://github.com/bytefish/TinyCsvParser) - An easy to use, easy to extend and high-performance library for CSV parsing with .NET.
* [YamlDotNet](https://github.com/aaubry/YamlDotNet) - A .NET library for YAML.

## Testing
* [Bogus](https://github.com/bchavez/Bogus) - A simple and sane fake data generator for C#. Based on and ported from the famed faker.js.
* [GenFu](https://github.com/MisterJames/GenFu) - A library you can use to generate realistic test data.
* [FluentAssertions](https://github.com/dennisdoomen/FluentAssertions) - A set of .NET extension methods that allow you to more naturally specify the expected outcome of a TDD or BDD-style test.
* [moq.netcore](https://github.com/aspnet/moq4/tree/netcore) - A most popular and friendly mocking framework for .NET.
* [MyTested.AspNetCore.Mvc](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc) - A fluent testing
  framework for ASP.NET Core MVC.
* [nunit](https://github.com/nunit/dotnet-test-nunit) - A NUnit test runner for .NET Core.
* [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore) - A pragmatic BDD solution for .NET. It uses the Gherkin specification language and integrates to Visual Studio.
* [TestStack.BDDfy](https://github.com/TestStack/TestStack.BDDfy) - A BDDfy is the simplest BDD framework EVER!
* [xunit](https://github.com/xunit/xunit) - A free, open source, community-focused unit testing tool for the .NET Framework.

## Web Framework
* [ReactJS.NET](https://github.com/reactjs/React.NET) - .NET library for JSX compilation and server-side rendering of React components.

## Web Socket
* [SignalR Server](https://github.com/aspnet/SignalR-Server) - A real-time web functionality for web apps, including server-side push.

## Windows Service
* 

# Starter Kits
* [ASP.NET Core Starter Kit](https://github.com/kriasoft/aspnet-starter-kit) - An opinionated boilerplate for web development based on .NET Core, Kestrel, GraphQL on the backend and Babel, Webpack, React and Redux on the frontend. This boilerplate comes in both C# and F# flavors.
* [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate) - An ASP.NET Boilerplate is a starting point for new modern web applications using best practices and most popular tools. It's aimed to be a SOLID model, a general-purpose application framework and a project template. `Still using framework 4.5.2`
* [saaskit](https://github.com/saaskit/saaskit) - A developer toolkit for building SaaS applications.

# Sample Projects
* [AlbumViewerVNext](https://github.com/RickStrahl/AlbumViewerVNext) - West Wind Album Viewer ASP.NET 5 Sample.
* [AspNet5GeoElasticsearch](https://github.com/damienbod/AspNet5GeoElasticsearch) - An ASP.NET Core MVC Geo Elasticsearch Swashbuckle Swagger.
* [cloudscribe](https://github.com/joeaudette/cloudscribe) - ASP.NET Core Multi-tenant web application foundation.
* [DotNetClub](https://github.com/scheshan/DotNetClub) - A tiny club written in Asp.Net Core.
* [Entropy](https://github.com/aspnet/Entropy) - A chaotic experimental playground for new features and ideas - check here for small and simple samples for individual features.
* [magazine-website](https://github.com/thangchung/magazine-website) - A magazine website (using dotnetcore, aspnetcore, efcore) with DDD, CQRS, microservices, asynchronous programming applied.
* [minicompiler](Minification, bundling and compiling sample) - Minification, bundling and compiling sample.
* [MusicStore](https://github.com/aspnet/MusicStore) - Sample MusicStore application that uses MVC and Entity Framework.
* [ReactiveTraderCloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) - A real-time trading platform demo showcasing reactive programming principles applied across the full application stack.

# Best Articles 
* [.NET platform standard](https://github.com/dotnet/corefx/blob/master/Documentation/architecture/net-platform-standard.md) - The differrent between the old version and the new version of .NET.
* [Porting a .Net Framework Library to .Net Core](http://www.michael-whelan.net/porting-dotnet-framework-library-to-dotnet-core) 
* [A guide to the .NET Core projects on GitHub](https://blog.rendle.io/a-guide-to-the-net-projects-on-github/)
* [haproxy, nginx, Angular 2, ASP.NET Core, Redis and Docker](http://tattoocoder.azurewebsites.net/legion-of-heroes-haproxy-nginx-angular2-aspnetcore-redis-docker/) - Really awesome article that using .NET Core and some of libraries like HAProxy, NGINX, Redis for the large scale infrastruture. 
* [.Net Continuous Delivery Microservices](http://stackshare.io/tomstaijen/net-continuous-delivery-microservices)
* [The New Configuration Model in ASP.NET Core](http://developer.telerik.com/featured/new-configuration-model-asp-net-core/)
* Comparison between dotnet core and nodejs at [here](https://manuel-rauber.com/2016/03/07/node-js-asp-net-core-1-0-a-usage-comparison/), [here](https://gist.github.com/ilyaigpetrov/f6df3e6f825ae1b5c7e2) and [here](https://github.com/thinktecture/nodejs-aspnetcore-webapi)
* [Authentication in ASP.NET Core](https://stormpath.com/blog/authentication-asp-net-core)
* [A walk-through for an ASP.NET Authorization Lab](https://github.com/blowdart/AspNetAuthorizationWorkshop)
* [A very good example about EF Core](https://github.com/rowanmiller/Demo-EFCore)
* [Adding Travis CI builds to a .NET Core app](http://andrewlock.net/adding-travis-ci-to-a-net-core-app/)

# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [thangchung](http://weblogs.asp.net/thangchung) has waived all copyright and related or neighboring rights to this work.
