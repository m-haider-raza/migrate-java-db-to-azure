---
page_type: sample
languages: 
- java
products: 
- app-service
- PostgreSQL
description: "Migrate Java EE apps and PostgreSQL database to Azure"
urlFragment: "migrate-javaee-app-postgresql-to-azure-training"
---

# Migrate Java EE App and PostgreSQL Database to Azure

You will find here a full training workshop on migrating an existing Java EE application and backend PostgreSQL database to Azure, including guides and demos. 
You will migrate:

- Java EE application to App Service Linux and 
- Application's data to Azure Database for PostgreSQL.

## What you should expect

This is not the official documentation but an opinionated training.

It is a hands-on training, and it will use the command line extensively. 
The idea is to get coding very quickly and play with the platform, 
from a simple demo to far more complex examples.

After completing all the guides, you should have a fairly good understanding of 
everything that Azure offers for running Java EE applications on PaaS without worrying
about the underlying infrastructure or monitoring applications.

You will migrate the famous [Sun's 2003 Java EE Blue Print](https://www.oracle.com/java/technologies/java-blueprint.html) 
sample application. The most recent incarnation of the sample application uses:

- Java SE 8
- Java EE 7
- JSR 338 Java Persistence API (JPA 2.2)
- JSR 346 Context and Dependency Injection (CDI 1.1)
- JSR 345 Enterprise Java Beans 3.2 (EJB 3.2)
- JSR 344 Java Server Faces (JSF 2.2) 
- JSR 339 Java API for RESTful Web Services (JAX-RS 2.0)
- Twitter Bootstrap (Bootstrap 3.x, JQuery 2.x, PrimeFaces 6.x) 

Upon migration, you will power the app using Azure Database for PostgreSQL.

## Symbols

>🛑 -  __Manual Modification Required__. When this symbol appears in front of one or 
more commands, you will need to modify the commands as indicated prior to running them.

>🚧 - __Preview-specific__. This symbol indicates steps that are only necessary while 
JBoss EAP on App Service is in preview.

>💡 - __Frustration Avoidance Tip__. These will help you avoid potential pitfalls.

Prerequisites and environment setup.

## [00 - Prerequisites and Setup](OSS-Java-DB-Migration/step-00-setup-your-environment/README.md) (30 minutes)

Deploy Petstore Application and Database locally on to a VM (simulating on-premises)
 
## [01 - Deploy a Java EE application to Azure VM](OSS-Java-DB-Migration/step-01-deploy-java-ee-app-to-VM/README.md) (15 minutes)

Create Azure Database for PostgreSQL Flexible Server.

## [02 - Create a database](OSS-Java-DB-Migration/step-02-create-azure-postgresql-database/README.md) (10 minutes)

Migrate on-premises PostgreSQL database to Azure.

## [03 - Migrate PostgreSQL database to Azure](OSS-Java-DB-Migration/step-03-migrate-database-to-azure/README.md) (30 minutes)

Migrate Java EE application to Azure.

## [04 - Migrate Java EE application to Azure](OSS-Java-DB-Migration/step-04-migrate-application-to-azure/README.md) (30 minutes)

---

## Petstore is back!

This Java EE Petstore sample is forked from 
[agoncal/agoncal-application-petstore-ee7](https://github.com/agoncal/agoncal-application-petstore-ee7) - see [Petstore README](./README-petstoreee7.md). 

> When you create something and give it away, you lose control of what you've created and then, anything can happen.
> 
> I created this Petstore application years ago to show how Java EE components would work all together. 
> I used this application in many talks, workshops, demos... and then, time passed, I forgot about it and never updated it.
> I've written this code when monoliths were a thing, when the cloud was just starting, and when the only CI/CD tool we had was called Hudson.
> 
> Today, thanks to the Azure team, my Petstore application is built with GitHub actions and deployed to the cloud.
> Without changing the original code, and with only a few commands and some configuration, you can deploy the application to Azure.
> What a journey!
> 
> Thank you,
> 
> [Antonio Goncalves](http://www.antoniogoncalves.org)

## Contributors

Thank you and congratulations to many contributors for making this training repo available 
millions of Java developers:

- [Antonio Goncalves](https://github.com/agoncal)
- [Asir Selvasingh](https://github.com/selvasingh)
- [Sree Adigopula](https://github.com/sadigopu)
- [Jason Freeberg](https://github.com/JasonFreeberg)
- [Joaquin Vano](https://github.com/jvano)
- [Julia Goloshubina](https://github.com/MS-jgol)
- [Yuchen Wang](https://github.com/yucwan)
- [Andy Xu](https://github.com/andxu)
- [Shrirang Shirodhkar](https://github.com/ShriShrirang)

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

---
