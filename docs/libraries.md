# Libraries

List of NuGet Packages and their purpose in .NET, so that you can choose the right package for your next project.

## Choose the right package

| **Purpose** | **Package** | **Description** |
| --- | --- | --- |
| **Logging** | [Serilog](https://www.nuget.org/packages/Serilog/) | Structured, leveled logging with rich context and many sinks |
| | [NLog](https://www.nuget.org/packages/NLog/) | Flexible logging with a wide range of targets and layouts |
| | [log4net](https://www.nuget.org/packages/log4net/) | Apache log4net — reliable, fast, and flexible logging framework |
| | [Microsoft.Extensions.Logging](https://www.nuget.org/packages/Microsoft.Extensions.Logging/) | Built-in .NET logging abstraction used across the ecosystem |
| | [ZLogger](https://www.nuget.org/packages/ZLogger/) | Zero-allocation, high-performance structured logger for .NET |
| | [Serilog.Sinks.Seq](https://www.nuget.org/packages/Serilog.Sinks.Seq/) | Serilog sink that ships structured logs to Seq |
| | [Serilog.Sinks.Elasticsearch](https://www.nuget.org/packages/Serilog.Sinks.Elasticsearch/) | Serilog sink for shipping logs to Elasticsearch |
| **Dependency Injection** | [Autofac](https://www.nuget.org/packages/Autofac/) | Feature-rich IoC container with modules and decorators |
| | [Ninject](https://www.nuget.org/packages/Ninject/) | Lightweight, extensible dependency injection container |
| | [SimpleInjector](https://www.nuget.org/packages/SimpleInjector/) | Fast, simple, and strongly-typed DI container |
| | [StructureMap](https://www.nuget.org/packages/StructureMap/) | Mature DI/IoC container (use Lamar for new projects) |
| | [Unity](https://www.nuget.org/packages/Unity/) | Extensible dependency injection container from Microsoft |
| | [DryIoc](https://www.nuget.org/packages/DryIoc.dll/) | Fast, capable, and friendly DI container |
| | [Castle Windsor](https://www.nuget.org/packages/Castle.Windsor/) | Mature, full-featured IoC container |
| | [Scrutor](https://www.nuget.org/packages/Scrutor/) | Assembly scanning and decoration extensions for Microsoft DI |
| | [Lamar](https://www.nuget.org/packages/Lamar/) | Fast IoC container and successor to StructureMap |
| | [Microsoft.Extensions.DependencyInjection](https://www.nuget.org/packages/Microsoft.Extensions.DependencyInjection/) | Built-in .NET DI container |
| | [Grace](https://www.nuget.org/packages/Grace/) | High-performance, feature-rich DI container |
| **Testing** | [xUnit](https://www.nuget.org/packages/xunit/) | Modern, extensible unit testing framework |
| | [NUnit](https://www.nuget.org/packages/NUnit/) | Popular, feature-rich testing framework |
| | [MSTest](https://www.nuget.org/packages/MSTest.TestFramework/) | Microsoft's official test framework |
| | [SpecFlow](https://www.nuget.org/packages/SpecFlow/) | BDD testing with Gherkin syntax |
| | [Shouldly](https://www.nuget.org/packages/Shouldly/) | Assertion library with human-readable error messages |
| | [FluentAssertions](https://www.nuget.org/packages/FluentAssertions/) | Readable, fluent assertion syntax for tests |
| | [AutoFixture](https://www.nuget.org/packages/AutoFixture/) | Auto-generates test data to reduce test setup boilerplate |
| | [GenFu](https://www.nuget.org/packages/GenFu/) | Generates realistic test data for .NET objects |
| | [TUnit](https://www.nuget.org/packages/TUnit/) | Modern, source-generator powered test framework for .NET 8+ |
| | [Verify](https://www.nuget.org/packages/Verify/) | Approval and snapshot testing — auto-diffs outputs |
| | [Fixie](https://www.nuget.org/packages/Fixie/) | Convention-driven, low-ceremony test framework |
| **Integration Testing** | [Microsoft.AspNetCore.Mvc.Testing](https://www.nuget.org/packages/Microsoft.AspNetCore.Mvc.Testing/) | In-process integration testing for ASP.NET Core apps |
| | [Testcontainers](https://www.nuget.org/packages/Testcontainers/) | Spin up real Docker containers (DB, cache, etc.) in tests |
| | [WireMock.Net](https://www.nuget.org/packages/WireMock.Net/) | HTTP stub/mock server for contract and integration tests |
| | [Respawn](https://www.nuget.org/packages/Respawn/) | Intelligently resets database to a clean state between tests |
| | [Alba](https://www.nuget.org/packages/Alba/) | Supercharges ASP.NET Core HTTP integration testing |
| **Encryption** | [BouncyCastle](https://www.nuget.org/packages/BouncyCastle.Cryptography/) | Comprehensive cryptography library |
| | [DotNetCore.Encrypt](https://www.nuget.org/packages/DotNetCore.Encrypt/) | Simple encryption utilities for .NET Core |
| | [NSec.Cryptography](https://www.nuget.org/packages/NSec.Cryptography/) | Modern, libsodium-based cryptography for .NET |
| | [Jose-Jwt](https://www.nuget.org/packages/jose-jwt/) | JSON Object Signing and Encryption (JOSE) — JWT/JWE/JWS |
| **Mocking** | [Moq](https://www.nuget.org/packages/Moq/) | The most popular .NET mocking library |
| | [FakeItEasy](https://www.nuget.org/packages/FakeItEasy/) | Simple, clean mocking framework with a friendly API |
| | [NSubstitute](https://www.nuget.org/packages/NSubstitute/) | Friendly substitute for mocking with natural syntax |
| | [Rocks](https://www.nuget.org/packages/Rocks/) | Source-generator based, AOT-compatible mock library |
| **Background Jobs** | [Quartz.NET](https://www.nuget.org/packages/Quartz/) | Enterprise-grade job scheduling with cron support |
| | [Hangfire](https://www.nuget.org/packages/Hangfire/) | Background job processing with a built-in web dashboard |
| | [Microsoft.Extensions.Hosting](https://www.nuget.org/packages/Microsoft.Extensions.Hosting/) | Built-in hosted services and worker model |
| | [Coravel](https://www.nuget.org/packages/Coravel/) | Near-zero config task scheduling, queuing, and caching |
| | [NCrontab](https://www.nuget.org/packages/ncrontab/) | Lightweight cron expression parser and scheduler |
| **Serialization** | [Newtonsoft.Json](https://www.nuget.org/packages/Newtonsoft.Json/) | The most widely used JSON library for .NET |
| | [System.Text.Json](https://www.nuget.org/packages/System.Text.Json/) | High-performance built-in JSON library |
| | [MessagePack](https://www.nuget.org/packages/MessagePack/) | Extremely fast binary serialization for .NET |
| | [Utf8Json](https://www.nuget.org/packages/Utf8Json/) | Fast JSON serializer that works directly on UTF-8 bytes |
| | [YamlDotNet](https://www.nuget.org/packages/YamlDotNet/) | YAML parser and serializer for .NET |
| | [Google.Protobuf](https://www.nuget.org/packages/Google.Protobuf/) | Protocol Buffers — language-neutral binary serialization |
| | [Avro](https://www.nuget.org/packages/Apache.Avro/) | Apache Avro binary serialization with schema evolution |
| **CSV** | [CsvHelper](https://www.nuget.org/packages/CsvHelper/) | Fast, flexible library for reading and writing CSV files |
| | [Sylvan.Data.Csv](https://www.nuget.org/packages/Sylvan.Data.Csv/) | High-performance CSV reader with minimal allocations |
| | [TinyCsvParser](https://www.nuget.org/packages/TinyCsvParser/) | Easy-to-use, high-performance CSV parser |
| **Date and Time** | [NodaTime](https://www.nuget.org/packages/NodaTime/) | A better date and time API than the built-in DateTime |
| | [Humanizer](https://www.nuget.org/packages/Humanizer/) | Manipulates and displays strings, dates, numbers, and more |
| | [TimeZoneConverter](https://www.nuget.org/packages/TimeZoneConverter/) | Converts between IANA, Windows, and Rails time zone IDs |
| **Mapping** | [AutoMapper](https://www.nuget.org/packages/AutoMapper/) | Convention-based object-to-object mapping |
| | [Mapster](https://www.nuget.org/packages/Mapster/) | Fast and flexible object mapper with great performance |
| | [Mapperly](https://www.nuget.org/packages/Riok.Mapperly/) | Source-generator based mapper — zero runtime overhead |
| | [TinyMapper](https://www.nuget.org/packages/TinyMapper/) | Lightweight object-to-object mapper |
| | [ExpressionMapper](https://www.nuget.org/packages/ExpressMapper/) | Fast mapping library using compiled expressions |
| **Fake Data** | [Bogus](https://www.nuget.org/packages/Bogus/) | Generates realistic fake data using the Faker.js API |
| | [Faker.Net](https://www.nuget.org/packages/Faker.Net/) | Port of the Ruby Faker library for .NET |
| **Authentication** | [Microsoft.AspNetCore.Authentication.JwtBearer](https://www.nuget.org/packages/Microsoft.AspNetCore.Authentication.JwtBearer/) | JWT bearer token authentication for ASP.NET Core |
| | [Duende IdentityServer](https://www.nuget.org/packages/Duende.IdentityServer/) | OpenID Connect and OAuth 2.0 server framework |
| | [OpenIddict](https://www.nuget.org/packages/OpenIddict.AspNetCore/) | Flexible, standards-compliant OpenID Connect server |
| | [AspNet.Security.OpenIdConnect.Server](https://www.nuget.org/packages/AspNet.Security.OpenIdConnect.Server/) | OpenID Connect/OAuth 2.0 server middleware |
| | [Microsoft.Identity.Web](https://www.nuget.org/packages/Microsoft.Identity.Web/) | Microsoft Entra ID (Azure AD) auth for ASP.NET Core |
| **Authorization** | [Microsoft.AspNetCore.Authorization](https://www.nuget.org/packages/Microsoft.AspNetCore.Authorization/) | Built-in policy-based authorization for ASP.NET Core |
| | [PolicyServer.Local](https://www.nuget.org/packages/PolicyServer.Local/) | Simple, local policy-based authorization solution |
| | [Casbin.NET](https://www.nuget.org/packages/Casbin.NET/) | RBAC/ABAC authorization library with flexible policy models |
| **Validation** | [FluentValidation](https://www.nuget.org/packages/FluentValidation/) | Strongly-typed, fluent validation rules |
| | [DataAnnotationsValidator](https://www.nuget.org/packages/DataAnnotationsValidator/) | Validate nested data annotation models recursively |
| | [GuardNet](https://www.nuget.org/packages/GuardNet/) | Simple, lightweight guard clause helpers |
| **Guard Clauses** | [Ardalis.GuardClauses](https://www.nuget.org/packages/Ardalis.GuardClauses/) | Lightweight guard clause helper library |
| | [Dawn.Guard](https://www.nuget.org/packages/Dawn.Guard/) | Fluent argument validation and guard clauses |
| **Caching** | [StackExchange.Redis](https://www.nuget.org/packages/StackExchange.Redis/) | High-performance Redis client for .NET |
| | [Microsoft.Extensions.Caching.Memory](https://www.nuget.org/packages/Microsoft.Extensions.Caching.Memory/) | Built-in in-memory cache |
| | [FusionCache](https://www.nuget.org/packages/ZiggyCreatures.FusionCache/) | Advanced multi-layer cache with fail-safe and background refresh |
| | [EasyCaching](https://www.nuget.org/packages/EasyCaching.Core/) | Caching abstraction supporting memory, Redis, Memcached, etc. |
| | [LazyCache](https://www.nuget.org/packages/LazyCache/) | Simple thread-safe in-memory caching with lazy loading |
| | [CacheManager](https://www.nuget.org/packages/CacheManager.Core/) | Unified caching layer supporting multiple cache providers |
| **ORM** | [Microsoft.EntityFrameworkCore](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/) | Microsoft's official, full-featured ORM |
| | [Dapper](https://www.nuget.org/packages/Dapper/) | Lightweight micro-ORM for fast, direct SQL |
| | [NHibernate](https://www.nuget.org/packages/NHibernate/) | Mature, full-featured ORM ported from Java |
| | [RepoDb](https://www.nuget.org/packages/RepoDb/) | Hybrid ORM — combines features of full ORM and micro-ORM |
| | [linq2db](https://www.nuget.org/packages/linq2db/) | LINQ to database provider — fast and flexible ORM |
| | [PetaPoco](https://www.nuget.org/packages/PetaPoco/) | Tiny ORM with a T4-based POCO generator |
| | [SqlKata](https://www.nuget.org/packages/SqlKata/) | SQL query builder with fluent API and multi-DB support |
| **Database Migrations** | [FluentMigrator](https://www.nuget.org/packages/FluentMigrator/) | Code-based database migrations with version tracking |
| | [DbUp](https://www.nuget.org/packages/dbup/) | Tracks and applies SQL script migrations to a database |
| | [Evolve](https://www.nuget.org/packages/Evolve/) | Database migration tool inspired by Flyway |
| **NoSQL / Document DB** | [MongoDB.Driver](https://www.nuget.org/packages/MongoDB.Driver/) | Official MongoDB .NET driver |
| | [Marten](https://www.nuget.org/packages/Marten/) | Use PostgreSQL as a document database and event store |
| | [LiteDB](https://www.nuget.org/packages/LiteDB/) | Embedded NoSQL database — SQLite for documents |
| | [Azure.Data.Tables](https://www.nuget.org/packages/Azure.Data.Tables/) | Client for Azure Table Storage / Cosmos DB Table API |
| | [Microsoft.Azure.Cosmos](https://www.nuget.org/packages/Microsoft.Azure.Cosmos/) | Official Azure Cosmos DB SDK for .NET |
| | [RavenDB.Client](https://www.nuget.org/packages/RavenDB.Client/) | Client for RavenDB — multi-model NoSQL database |
| **Event Sourcing** | [EventStore.Client](https://www.nuget.org/packages/EventStore.Client/) | Official client for EventStoreDB event sourcing database |
| | [NEventStore](https://www.nuget.org/packages/NEventStore/) | Event store abstraction for implementing event sourcing |
| | [SqlStreamStore](https://www.nuget.org/packages/SqlStreamStore/) | Stream-based event store built on relational databases |
| **API Gateway** | [Ocelot](https://www.nuget.org/packages/Ocelot/) | .NET API gateway with routing, auth, and rate limiting |
| | [YARP](https://www.nuget.org/packages/Yarp.ReverseProxy/) | Microsoft's high-performance reverse proxy and API gateway |
| **API Clients** | [Refit](https://www.nuget.org/packages/Refit/) | Type-safe REST client — define APIs as C# interfaces |
| | [RestSharp](https://www.nuget.org/packages/RestSharp/) | Simple REST and HTTP API client for .NET |
| | [Flurl](https://www.nuget.org/packages/Flurl/) | Fluent URL builder and testable HTTP client |
| | [Polly](https://www.nuget.org/packages/Polly/) | Resilience — retries, circuit breakers, fallbacks |
| | [Kiota](https://www.nuget.org/packages/Microsoft.Kiota.Abstractions/) | Generate strongly-typed API clients from OpenAPI specs |
| **Resiliency** | [Polly](https://www.nuget.org/packages/Polly/) | Retries, circuit breakers, fallbacks, timeouts, bulkheads |
| | [Microsoft.Extensions.Http.Resilience](https://www.nuget.org/packages/Microsoft.Extensions.Http.Resilience/) | Resilience pipelines for HttpClient via Polly integration |
| | [Simmy](https://www.nuget.org/packages/Polly.Contrib.Simmy/) | Chaos engineering — inject faults into Polly policies |
| **Rate Limiting** | [AspNetCoreRateLimit](https://www.nuget.org/packages/AspNetCoreRateLimit/) | IP and client-based rate limiting middleware |
| | [Microsoft.AspNetCore.RateLimiting](https://www.nuget.org/packages/Microsoft.AspNetCore.RateLimiting/) | Built-in rate limiting middleware in .NET 7+ |
| **API Versioning** | [Asp.Versioning.Http](https://www.nuget.org/packages/Asp.Versioning.Http/) | API versioning for ASP.NET Core (URL, header, query) |
| | [Asp.Versioning.Mvc](https://www.nuget.org/packages/Asp.Versioning.Mvc/) | API versioning for MVC-style ASP.NET Core controllers |
| **Minimal APIs** | [Carter](https://www.nuget.org/packages/Carter/) | Minimal API module framework built on ASP.NET Core |
| | [FastEndpoints](https://www.nuget.org/packages/FastEndpoints/) | REPR pattern-based endpoint framework for ASP.NET Core |
| **Messaging** | [MassTransit](https://www.nuget.org/packages/MassTransit/) | Distributed application framework for message-based systems |
| | [RabbitMQ.Client](https://www.nuget.org/packages/RabbitMQ.Client/) | Official RabbitMQ .NET client |
| | [EasyNetQ](https://www.nuget.org/packages/EasyNetQ/) | Easy-to-use RabbitMQ .NET client |
| | [Wolverine](https://www.nuget.org/packages/WolverineFx/) | In-process command bus and message broker |
| | [Confluent.Kafka](https://www.nuget.org/packages/Confluent.Kafka/) | Official Apache Kafka .NET client |
| | [Azure.Messaging.ServiceBus](https://www.nuget.org/packages/Azure.Messaging.ServiceBus/) | Client for Azure Service Bus messaging |
| | [AWSSDK.SQS](https://www.nuget.org/packages/AWSSDK.SQS/) | AWS SDK client for Amazon SQS message queuing |
| | [NATS.Client.Core](https://www.nuget.org/packages/NATS.Client.Core/) | Official .NET client for NATS high-performance messaging |
| | [SlimMessageBus](https://www.nuget.org/packages/SlimMessageBus/) | Slim facade over multiple messaging brokers |
| **Real-Time** | [Microsoft.AspNetCore.SignalR](https://www.nuget.org/packages/Microsoft.AspNetCore.SignalR/) | Real-time web communication over WebSockets |
| | [StackExchange.Redis](https://www.nuget.org/packages/StackExchange.Redis/) | Used as SignalR backplane for scale-out scenarios |
| **GraphQL** | [HotChocolate.AspNetCore](https://www.nuget.org/packages/HotChocolate.AspNetCore/) | Modern, feature-rich GraphQL server for ASP.NET Core |
| | [GraphQL.NET](https://www.nuget.org/packages/GraphQL/) | Popular, mature GraphQL implementation for .NET |
| | [Strawberry Shake](https://www.nuget.org/packages/StrawberryShake.Tools/) | Type-safe GraphQL client generator by ChilliCream |
| **gRPC** | [Grpc.AspNetCore](https://www.nuget.org/packages/Grpc.AspNetCore/) | gRPC framework for ASP.NET Core services |
| | [protobuf-net.Grpc](https://www.nuget.org/packages/protobuf-net.Grpc/) | Code-first gRPC using contract attributes, no .proto files |
| | [Grpc.Net.Client](https://www.nuget.org/packages/Grpc.Net.Client/) | gRPC client for .NET |
| **API Documentation** | [Swashbuckle.AspNetCore](https://www.nuget.org/packages/Swashbuckle.AspNetCore/) | Swagger/OpenAPI documentation for ASP.NET Core |
| | [NSwag.AspNetCore](https://www.nuget.org/packages/NSwag.AspNetCore/) | OpenAPI toolchain with code generation |
| | [Scalar.AspNetCore](https://www.nuget.org/packages/Scalar.AspNetCore/) | Modern, beautiful API reference documentation UI |
| | [Microsoft.AspNetCore.OpenApi](https://www.nuget.org/packages/Microsoft.AspNetCore.OpenApi/) | Built-in OpenAPI document generation in .NET 9+ |
| **CQRS** | [MediatR](https://www.nuget.org/packages/MediatR/) | Simple mediator for CQRS, commands, and notifications |
| | [Brighter](https://www.nuget.org/packages/Paramore.Brighter/) | Command processor with outbox pattern for messaging |
| | [Darker](https://www.nuget.org/packages/Paramore.Darker/) | Query side companion to Brighter following CQRS |
| **Observability** | [OpenTelemetry](https://www.nuget.org/packages/OpenTelemetry/) | Observability framework — traces, metrics, and logs |
| | [Serilog.AspNetCore](https://www.nuget.org/packages/Serilog.AspNetCore/) | Serilog integration and request logging for ASP.NET Core |
| | [App.Metrics](https://www.nuget.org/packages/App.Metrics/) | Real-time metrics and health reporting for .NET |
| | [prometheus-net](https://www.nuget.org/packages/prometheus-net/) | Prometheus metrics instrumentation for .NET |
| | [MiniProfiler.AspNetCore.Mvc](https://www.nuget.org/packages/MiniProfiler.AspNetCore.Mvc/) | Lightweight profiling widget in the page for ASP.NET Core |
| **Health Checks** | [AspNetCore.HealthChecks.UI](https://www.nuget.org/packages/AspNetCore.HealthChecks.UI/) | UI dashboard for ASP.NET Core health check endpoints |
| | [AspNetCore.HealthChecks.SqlServer](https://www.nuget.org/packages/AspNetCore.HealthChecks.SqlServer/) | Health check for SQL Server connectivity |
| | [AspNetCore.HealthChecks.Redis](https://www.nuget.org/packages/AspNetCore.HealthChecks.Redis/) | Health check for Redis connectivity |
| | [AspNetCore.HealthChecks.Uris](https://www.nuget.org/packages/AspNetCore.HealthChecks.Uris/) | Health check that probes external HTTP/URI endpoints |
| **Document Storage** | [Marten](https://www.nuget.org/packages/Marten/) | Use PostgreSQL as a document database and event store |
| **PDF Generation** | [QuestPDF](https://www.nuget.org/packages/QuestPDF/) | Fluent, code-first PDF layout engine |
| | [iTextSharp](https://www.nuget.org/packages/itext7/) | iText 7 — comprehensive PDF creation and manipulation |
| | [PdfSharpCore](https://www.nuget.org/packages/PdfSharpCore/) | .NET Core port of PdfSharp for creating PDF documents |
| | [DinkToPdf](https://www.nuget.org/packages/DinkToPdf/) | Converts HTML to PDF using wkhtmltopdf |
| | [Wkhtmltopdf.NetCore](https://www.nuget.org/packages/Wkhtmltopdf.NetCore/) | Wrapper around wkhtmltopdf for HTML-to-PDF conversion |
| **Excel / Spreadsheet** | [EPPlus](https://www.nuget.org/packages/EPPlus/) | Create and read Excel files without Office installed |
| | [ClosedXML](https://www.nuget.org/packages/ClosedXML/) | Friendly API for creating and editing Excel spreadsheets |
| | [DocumentFormat.OpenXml](https://www.nuget.org/packages/DocumentFormat.OpenXml/) | Official SDK for Office Open XML files (docx, xlsx, pptx) |
| | [NPOI](https://www.nuget.org/packages/NPOI/) | .NET port of Apache POI for reading/writing Excel and Word |
| | [MiniExcel](https://www.nuget.org/packages/MiniExcel/) | Low-memory, high-performance Excel reading and writing |
| **Image Processing** | [SixLabors.ImageSharp](https://www.nuget.org/packages/SixLabors.ImageSharp/) | Cross-platform, fully managed image processing library |
| | [SkiaSharp](https://www.nuget.org/packages/SkiaSharp/) | .NET bindings for Google's Skia 2D graphics engine |
| | [Magick.NET](https://www.nuget.org/packages/Magick.NET-Q16-AnyCPU/) | .NET bindings for ImageMagick — extensive format support |
| | [SixLabors.Fonts](https://www.nuget.org/packages/SixLabors.Fonts/) | Font loading and rendering library for ImageSharp |
| **QR Code / Barcode** | [QRCoder](https://www.nuget.org/packages/QRCoder/) | Pure .NET library to generate QR codes |
| | [ZXing.Net](https://www.nuget.org/packages/ZXing.Net/) | Port of ZXing — reads and writes barcodes and QR codes |
| | [BarcodeWriter](https://www.nuget.org/packages/BarcodeWriter.Portable/) | Generates barcode images in various formats |
| **HTML Parsing** | [HtmlAgilityPack](https://www.nuget.org/packages/HtmlAgilityPack/) | HTML parser that handles malformed markup gracefully |
| | [AngleSharp](https://www.nuget.org/packages/AngleSharp/) | HTML5/CSS3 parser with a W3C-spec DOM implementation |
| **Web Scraping** | [PuppeteerSharp](https://www.nuget.org/packages/PuppeteerSharp/) | Headless Chromium control for crawling and screenshots |
| | [Microsoft.Playwright](https://www.nuget.org/packages/Microsoft.Playwright/) | Cross-browser automation — Chrome, Firefox, WebKit |
| | [Selenium.WebDriver](https://www.nuget.org/packages/Selenium.WebDriver/) | Browser automation via WebDriver protocol |
| **Compression** | [SharpZipLib](https://www.nuget.org/packages/SharpZipLib/) | Zip, GZip, tar, and BZIP2 compression library |
| | [System.IO.Compression](https://www.nuget.org/packages/System.IO.Compression/) | Built-in compression support (GZip, Deflate, ZStd, Brotli) |
| | [K4os.Compression.LZ4](https://www.nuget.org/packages/K4os.Compression.LZ4/) | Ultra-fast LZ4 compression and decompression |
| **Email** | [FluentEmail.Core](https://www.nuget.org/packages/FluentEmail.Core/) | Fluent email sending API with multiple provider support |
| | [MailKit](https://www.nuget.org/packages/MailKit/) | Full-featured email client library (SMTP, IMAP, POP3) |
| | [SendGrid](https://www.nuget.org/packages/SendGrid/) | Official SendGrid SDK for transactional email delivery |
| | [Mailgun.Net](https://www.nuget.org/packages/Mailgun.Net/) | .NET client for the Mailgun email delivery API |
| **SMS / Notifications** | [Twilio](https://www.nuget.org/packages/Twilio/) | Official Twilio SDK for SMS, voice, and messaging |
| | [WebPush](https://www.nuget.org/packages/WebPush/) | Web Push Notifications via the VAPID protocol |
| | [FirebaseAdmin](https://www.nuget.org/packages/FirebaseAdmin/) | Firebase Admin SDK — push notifications and more |
| **Feature Flags** | [Microsoft.FeatureManagement](https://www.nuget.org/packages/Microsoft.FeatureManagement/) | Built-in .NET feature flag library |
| | [LaunchDarkly.ServerSdk](https://www.nuget.org/packages/LaunchDarkly.ServerSdk/) | Official LaunchDarkly SDK for server-side feature flags |
| | [Flagsmith](https://www.nuget.org/packages/Flagsmith/) | Open source feature flag client for Flagsmith platform |
| **Search** | [NEST](https://www.nuget.org/packages/NEST/) | High-level .NET client for Elasticsearch |
| | [Elastic.Clients.Elasticsearch](https://www.nuget.org/packages/Elastic.Clients.Elasticsearch/) | New official Elasticsearch .NET client (replaces NEST) |
| | [Lucene.Net](https://www.nuget.org/packages/Lucene.Net/) | Full-featured text search engine library for .NET |
| | [Meilisearch](https://www.nuget.org/packages/Meilisearch/) | .NET SDK for the Meilisearch fast search engine |
| | [Typesense](https://www.nuget.org/packages/Typesense/) | .NET client for the Typesense open-source search engine |
| **Cloud Storage** | [Azure.Storage.Blobs](https://www.nuget.org/packages/Azure.Storage.Blobs/) | Azure Blob Storage client SDK |
| | [AWSSDK.S3](https://www.nuget.org/packages/AWSSDK.S3/) | AWS SDK client for Amazon S3 object storage |
| | [Google.Cloud.Storage.V1](https://www.nuget.org/packages/Google.Cloud.Storage.V1/) | Google Cloud Storage client for .NET |
| | [Minio](https://www.nuget.org/packages/Minio/) | .NET SDK for MinIO — S3-compatible object storage |
| **AI / Machine Learning** | [Microsoft.ML](https://www.nuget.org/packages/Microsoft.ML/) | ML.NET — machine learning framework for .NET |
| | [Microsoft.SemanticKernel](https://www.nuget.org/packages/Microsoft.SemanticKernel/) | AI orchestration SDK for building LLM-powered apps |
| | [Azure.AI.OpenAI](https://www.nuget.org/packages/Azure.AI.OpenAI/) | Azure OpenAI client for GPT models and embeddings |
| | [OpenAI](https://www.nuget.org/packages/OpenAI/) | Official OpenAI .NET SDK for GPT, DALL-E, and Whisper |
| | [OllamaSharp](https://www.nuget.org/packages/OllamaSharp/) | .NET client for locally running LLMs with Ollama |
| | [Microsoft.Extensions.AI](https://www.nuget.org/packages/Microsoft.Extensions.AI/) | Unified AI abstractions for .NET ecosystem |
| | [Betalgo.Ranul.OpenAI](https://www.nuget.org/packages/Betalgo.Ranul.OpenAI/) | Community .NET client for the OpenAI API |
| | [LLamaSharp](https://www.nuget.org/packages/LLamaSharp/) | Run local LLMs (llama.cpp models) directly in .NET |
| **Vector Databases** | [Qdrant.Client](https://www.nuget.org/packages/Qdrant.Client/) | .NET client for the Qdrant vector similarity search engine |
| | [Milvus.Client](https://www.nuget.org/packages/Milvus.Client/) | .NET SDK for Milvus open-source vector database |
| | [Microsoft.SemanticKernel.Connectors.Weaviate](https://www.nuget.org/packages/Microsoft.SemanticKernel.Connectors.Weaviate/) | Weaviate vector store connector for Semantic Kernel |
| **Reactive Programming** | [System.Reactive](https://www.nuget.org/packages/System.Reactive/) | Rx.NET — reactive extensions for async/event-based code |
| | [DynamicData](https://www.nuget.org/packages/DynamicData/) | Reactive collections and change sets built on Rx.NET |
| **Functional Programming** | [LanguageExt.Core](https://www.nuget.org/packages/LanguageExt.Core/) | Functional-programming types: Option, Either, Result, IO |
| | [OneOf](https://www.nuget.org/packages/OneOf/) | Discriminated union types — type-safe alternative to exceptions |
| | [CSharpFunctionalExtensions](https://www.nuget.org/packages/CSharpFunctionalExtensions/) | Result and Maybe types for functional error handling in C# |
| | [ErrorOr](https://www.nuget.org/packages/ErrorOr/) | Fluent result type for error handling without exceptions |
| **Architecture** | [Ardalis.Result](https://www.nuget.org/packages/Ardalis.Result/) | Result pattern — return successes and failures uniformly |
| | [Ardalis.SmartEnum](https://www.nuget.org/packages/Ardalis.SmartEnum/) | Base class for strongly-typed enums with behavior |
| | [Ardalis.Specification](https://www.nuget.org/packages/Ardalis.Specification/) | Specification pattern for EF Core and other ORMs |
| | [NetArchTest.Rules](https://www.nuget.org/packages/NetArchTest.Rules/) | Enforce architectural rules and dependencies in tests |
| **CLI Tools** | [System.CommandLine](https://www.nuget.org/packages/System.CommandLine/) | Microsoft's API for building command-line tools |
| | [Spectre.Console](https://www.nuget.org/packages/Spectre.Console/) | Build beautiful, rich console applications |
| | [CommandLineParser](https://www.nuget.org/packages/CommandLineParser/) | Simple, opinionated command-line argument parser |
| | [Cocona](https://www.nuget.org/packages/Cocona/) | Micro-framework to quickly build console apps in .NET |
| **Performance** | [BenchmarkDotNet](https://www.nuget.org/packages/BenchmarkDotNet/) | Powerful, accurate .NET benchmarking library |
| | [Microsoft.IO.RecyclableMemoryStream](https://www.nuget.org/packages/Microsoft.IO.RecyclableMemoryStream/) | Pooled MemoryStream replacement to reduce GC pressure |
| | [ObjectPool](https://www.nuget.org/packages/Microsoft.Extensions.ObjectPool/) | Built-in object pooling to reduce allocations |
| **Configuration** | [Microsoft.Extensions.Configuration](https://www.nuget.org/packages/Microsoft.Extensions.Configuration/) | Built-in configuration abstraction for .NET |
| | [Steeltoe.Extensions.Configuration](https://www.nuget.org/packages/Steeltoe.Extensions.Configuration.CloudFoundryCore/) | Cloud-native config from Spring Cloud Config Server |
| | [dotenv.net](https://www.nuget.org/packages/dotenv.net/) | Loads environment variables from .env files |
| **Code Quality** | [StyleCop.Analyzers](https://www.nuget.org/packages/StyleCop.Analyzers/) | Roslyn-based StyleCop rules as code analyzers |
| | [SonarAnalyzer.CSharp](https://www.nuget.org/packages/SonarAnalyzer.CSharp/) | SonarQube rules for C# as Roslyn analyzers |
| | [Roslynator.Analyzers](https://www.nuget.org/packages/Roslynator.Analyzers/) | 190+ Roslyn analyzers and refactorings for C# |
| | [Meziantou.Analyzer](https://www.nuget.org/packages/Meziantou.Analyzer/) | Roslyn analyzer with performance and best-practice rules |
| **Benchmarking** | [BenchmarkDotNet](https://www.nuget.org/packages/BenchmarkDotNet/) | Powerful, accurate .NET benchmarking library |
| **Geospatial** | [NetTopologySuite](https://www.nuget.org/packages/NetTopologySuite/) | Geospatial geometry library with GIS operations |
| | [GeoJSON.Net](https://www.nuget.org/packages/GeoJSON.Net/) | GeoJSON types and serialization for .NET |
| | [Mapsui](https://www.nuget.org/packages/Mapsui/) | .NET map component for WPF, WinForms, Blazor, and MAUI |
| **Payment** | [Stripe.net](https://www.nuget.org/packages/Stripe.net/) | Official Stripe SDK for payment processing |
| | [Braintree](https://www.nuget.org/packages/Braintree/) | Official Braintree (PayPal) SDK for payment processing |
| **Diagnostics** | [MiniProfiler.AspNetCore.Mvc](https://www.nuget.org/packages/MiniProfiler.AspNetCore.Mvc/) | Lightweight profiling tool embedded in ASP.NET Core pages |
| | [dotnet-counters](https://www.nuget.org/packages/dotnet-counters/) | CLI tool for monitoring .NET performance counters |
| | [dotMemory Unit](https://www.nuget.org/packages/JetBrains.DotMemoryUnit/) | Extend unit tests with memory profiling assertions |
