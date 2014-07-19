# Awesome Play1 [![play-isthe1!](http://img.shields.io/badge/play-isthe1-red.svg?style=flat)](https://github.com/markets/awesome-ruby)

A collection of awesome Play 1.x [modules](#modules), [tools](#tools), and [resources](#resources).

>Inspired by [awesome-php](https://github.com/ziadoz/awesome-php), [awesome-python](https://github.com/vinta/awesome-python), [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks) and [awesome-ruby](https://github.com/markets/awesome-ruby).

[Contributions](https://github.com/PerfectCarl/awesome-play1/blob/master/CONTRIBUTING.md) are always welcome! 

# Modules
Lists all the modules available for Play 1.x. with the following `badges` : 

| Badge                                                                                                                                                                                 | Meaning                                                                                                                                                                                                                      |  
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/carbonate)                         | the module is registered in [playframework.com/modules](http://www.playframework.com/modules). The badge points to the registered page.                                                                                      |
| [![registered on playframework.com/modules](http://img.shields.io/badge/registered-no-red.svg?style=flat)](https://github.com/PerfectCarl/play-profiler)                              | the module is **not** registered in [playframework.com/modules](http://www.playframework.com/modules). You have to add an external repository in your `dependencies.yml` file. The badge points to the official module page. |
| [![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.db/play-db) | the module is available in MavenCentral thanks to the [maven-play-plugin](https://code.google.com/p/maven-play-plugin). The badge poins to the maven repository of the module.                                               |
| [![Updated since the play module registry was frozen](http://img.shields.io/badge/ -updated-ff69b4.svg?style=flat)](https://github.com/PerfectCarl/play-profiler)                     | the module has been updated since [playframework.com/modules](http://www.playframework.com/modules) has been frozen. The badge points to the official module page.                                                           |


All the modules in [a spreadsheet](https://docs.google.com/spreadsheets/d/1b-_ipGbktIRnwyipoIpP3bcR-JlpEM3S_OA31r40-L0)
 * [Database](#database) 
 * [Deployment](#deployment) 
 * [Injection/dependencies](#injectiondependencies) 
 * [Language](#language) 
 * [Monitoring](#monitoring) 
 * [Persistence](#persistence) 
 * [Presentation](#presentation) 
 * [Rest](#rest) 
 * [Scaffolding](#scaffolding) 
 * [Security](#security) 
 * [Template](#template) 
 * [Translation](#translation) 
 * [Misc](#misc) 

## Database 

* **[[carbonate] Carbonate](http://www.playframework.com/modules/carbonate)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/carbonate) Creates and runs database migrations using Hibernate schema update to automatically generate SQL to the migrations. See this blog [post](http://huljas.github.com/code/2011/04/04/managing-database-with-playcarbonate.html) 
[More](https://github.com/huljas/play-carbonate)
* **[[chronostamp] Chronostamp](http://www.playframework.com/modules/chronostamp)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/chronostamp) Enhances Models by adding and updating timestamp fields (created_at & updated_at). 
[More](https://github.com/omaroman/chronostamp)
* **[[db] Database module](http://www.playframework.com/modules/db)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/db)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.db/play-db) Export your Play! domain model to a DDL file and import a database into your Play! domain model. 
[More](http://github.com/pepite/play--database)
* **[[jpagen] JpaGen](http://www.playframework.com/modules/jpagen)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/jpagen) Generates JPA Entities and Composite keys (when needed) from metadata or a file containing a list of tables. 
[More](http://github.com/marcuspocus/jpagen)
* **[[liquibase] Liquibase](http://www.playframework.com/modules/liquibase)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/liquibase) [Liquibase](http://www.liquibase.org) is a simple, reliable and elegant solution for database refactoring management 
[More](https://github.com/7uc0/play-liquibase)
* **[[logisimayml] logisima-yml](http://www.playframework.com/modules/logisimayml)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/logisimayml) Exports your database into an yml file 
[More](http://github.com/sim51/logisima-play-yml)
* **[[migrate] Database migration](http://www.playframework.com/modules/migrate)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/migrate) Maintains database versions for your project. 
[More](http://github.com/dcardon/play-migrate)
* **[[multidb] Multiple Databases](http://www.playframework.com/modules/multidb)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/multidb) Scale your application to multiple databases with a common schema. 
[More](http://github.com/dcardon/play-multidb)
## Deployment 

* **[[capistrano] Capistrano](http://www.playframework.com/modules/capistrano)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/capistrano) Deploys a remote application using Capistrano + SSH + VCS and run it in nohup/background mode. 
[More](https://github.com/mandubian/play-capistrano)
* **[[cargo] Cargo](http://www.playframework.com/modules/cargo)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cargo) Remotely deploys your application. 
[More](https://github.com/dgouyette/play-cargo)
* **[[cloudbees] CloudBees](http://www.playframework.com/modules/cloudbees)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cloudbees) Provides integration with CloudBees. 
[More](https://github.com/hadashi/play-cloudbees)
* **[[cloudfoundry] CloudFoundry](http://www.playframework.com/modules/cloudfoundry)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cloudfoundry) Automatically configure the database your application is deployed in In CloudFoundry. 
[More](https://github.com/bcourtine/play--cloudfondry)
* **[[dotcloud] Dotcloud](http://www.playframework.com/modules/dotcloud)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/dotcloud) Deploys your application to dotcloud 
[More](https://github.com/lsinger/play-dotcloud)
* **[[gae] Google App Engine](http://www.playframework.com/modules/gae)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/gae)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.gae/play-gae) Creates application for the Google App Engine platform. 
[More](http://github.com/guillaumebort/play-gae)
* **[[heroku] Heroku](http://www.playframework.com/modules/heroku)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/heroku) Deploys your application on Heroku. 
[More](https://github.com/jamesward/play-heroku)
* **[[openebay] Open eBay](http://www.playframework.com/modules/openebay)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/openebay) Provides the basic plumbing to create an [Open eBay Application](http://apps.ebay.com/) 
[More](https://bitbucket.org/kumaresan/openebay)
* **[[openshift] Openshift](http://www.playframework.com/modules/openshift)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/openshift) Openshift is Red Hat’s free, auto-scaling, cloud-based platform-as-a-service for Java, Perl, PHP, Python, and Ruby applications. 
[More](https://github.com/opensas/openshift)
* **[[play-gae-q42] Q42's Google App Engine](https://github.com/Q42/play-gae)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-no-red.svg?style=flat)](https://github.com/Q42/play-gae) **Maintained** module for Google App Engine integration. Should be used instead of [gae] 
[More](https://github.com/Q42/play-gae)
* **[[playapps] playapps.net](http://www.playframework.com/modules/playapps)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/playapps) playapps.net is a streamlined deployment environment designed to get your Play applications up and running quickly and efficiently 
[More](http://github.com/zenexity/play-playapps)
* **[[reverseproxy] ReverseProxy](http://www.playframework.com/modules/reverseproxy)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/reverseproxy) Configures your application to automatically switch between the HTTP and HTTPS protocols per page when used behind a front end. 
[More](https://github.com/omaroman/reverseproxy)
* **[[router] Play Router Annotations](http://www.playframework.com/modules/router)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/router)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.router/play-router) Adds routes through annotations, allowing you to declare your routes in your controllers. 
[More](https://github.com/digiPlant/play-router-annotations)
* **[[stax] Stax](http://www.playframework.com/modules/stax)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/stax) Easy deployment to Stax cloud hosting platform (http://www.stax.net). 
[More](http://github.com/erwan/playstax)
* **[[vhost] VHost](http://www.playframework.com/modules/vhost)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/vhost) Adds some virtual hosts functionality with separate datasource and customizable application settings for each virtual host. 
[More](https://github.com/lyubo/play-vhost)
## Injection/dependencies 

* **[[constretto] Constretto](http://www.playframework.com/modules/constretto)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/constretto)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.constretto/play-constretto) Makes integration with the Constretto configration framework easy 
[More](https://github.com/zapodot/constretto-play)
* **[[guice] Guice](http://www.playframework.com/modules/guice)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/guice)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.guice/play-guice) Injects Guice managed components into your application. 
[More](http://github.com/pk11/play-guice-module)
* **[[ivy] Ivy dependency management](http://www.playframework.com/modules/ivy)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/ivy) Manages your dependencies with apache ivy. 
[More](http://github.com/pk11/play-ivy)
* **[[maven] Maven dependency management](http://www.playframework.com/modules/maven)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/maven) Manages your dependencies with apache maven 
[More](http://github.com/wangyizhuo/play-maven)
* **[[spring] Spring](http://www.playframework.com/modules/spring)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/spring)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.spring/play-spring) Allows to use Spring managed beans inside your play! 1.x applications. 
[More](http://github.com/pepite/Play--framework-Spring-module)
## Language 

* **[[googleclosure] Google Closure](http://www.playframework.com/modules/googleclosure)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/googleclosure) This module is aimed at integrating Google Closure tools with play!. 
[More](http://code.google.com/p/mandubian-play-google-closure/)
* **[[gwt] Google Web Toolkit](http://www.playframework.com/modules/gwt)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/gwt) This module provides a helper to simplify the integration of a GWT UI with Play as an application server. 
[More](http://code.google.com/p/play-framework-gwt/)
* **[[gwt2] GWT2](http://www.playframework.com/modules/gwt2)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/gwt2) Integrates Play with GWT 
[More](http://github.com/vbuzzano/play-gwt2)
* **[[scala] Scala](http://www.playframework.com/modules/scala)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/scala)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.scala/play-scala) Play Scala enables you to use the Scala language for your application keeping key properties of the Play framework 
[More](http://www.playframework.com/modules/scala)
* **[[scalagen] Scala Gen](http://www.playframework.com/modules/scalagen)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/scalagen) Scala code generators for the Play! framework 
[More](https://github.com/asinghal/Play-ScalaGen)
* **[[scalasecure] Scala secure](http://www.playframework.com/modules/scalasecure)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/scalasecure) This module provides basic security (authentication/ authorization) for Play applications written in Scala. 
[More](https://github.com/asinghal/Play-ScalaSecure)
## Monitoring 

* **[[accesslog] Accesslog](http://www.playframework.com/modules/accesslog)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/accesslog)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.accesslog/play-accesslog) A Play framework module that performs request logging similar to an access log file in nginx or apache. 
[More](https://github.com/briannesbitt/play-accesslog)
* **[[betterlogs] BetterLogs](http://www.playframework.com/modules/betterlogs)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/betterlogs) Enhances the default logs adding  the class and method names, where the log has been called, its signature, the file name and the line. 
[More](https://github.com/sgodbillon/BetterLogs)
* **[[infoplay] InfoPlay](http://www.playframework.com/modules/infoplay)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/infoplay) InfoPlay is a module which gives many informations like infophp in PHP language. 
[More](http://code.google.com/p/infoplay/)
* **[[jpastats] Jpastats](http://www.playframework.com/modules/jpastats)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/jpastats) Record how many database queries were executed during a request 
[More](https://github.com/eamelink/play-jpastats/)
* **[[log4play] Log4Play](http://www.playframework.com/modules/log4play)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/log4play) Provides a log4j appender which publishes log entries to an EventStream 
[More](https://github.com/feliperazeek/log4play)
* **[[playerrors] Playerrors](http://www.playframework.com/modules/playerrors)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/playerrors) Playerrors gathers and informs you about the errors in your production webapps, so you can fix them before your visitors get a chance to complain 
[More](https://github.com/marius0/playerrors)
* **[[profiler] Mini-profiler](https://github.com/PerfectCarl/play-profiler)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-no-red.svg?style=flat)](https://github.com/PerfectCarl/play-profiler) Displays a mini profiler in your application 
[More](https://github.com/PerfectCarl/play-profiler)
* **[[recordtracking] RecordTracking](http://www.playframework.com/modules/recordtracking)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/recordtracking) RecordTracking unobtrusively tracks the creation, updating and elimination events regarding to records. 
[More](https://github.com/omaroman/recordtracking)
* **[[statsd] Statsd](http://www.playframework.com/modules/statsd)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/statsd) The module is a wrapper over [StatsD](https://github.com/etsy/statsd) which allow for dead simple statistic aggregation from within play. 
[More](https://github.com/rkroll/play-statsd/)
* **[[play-hibernate-statistics] Hibernate statistics](https://github.com/francisdb/play-hibernate-statistics)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-no-red.svg?style=flat)](https://github.com/francisdb/play-hibernate-statistics) Displays MBean Hibernate statistics 
[More](https://github.com/francisdb/play-hibernate-statistics)
## Persistence 

* **[[associations] Associations](http://www.playframework.com/modules/associations)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/associations)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.associations/play-associations) This module reduces the code to manage bi-directional associations. 
[More](https://github.com/pareis/play-associations)
* **[[cream] JCR for Play!](http://www.playframework.com/modules/cream)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cream) A module that seamlessly integrates Apache Jackrabbit(JCR 2.0) with Play framework 
[More](https://github.com/mfornos/Cream)
* **[[ebean] EBean ORM support](http://www.playframework.com/modules/ebean)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/ebean)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.ebean/play-ebean) Adds Ebean ORM to play!. Still in very experimental phase. 
[More](https://github.com/lyubo/play-ebean)
* **[[mongo] MongoDB](http://www.playframework.com/modules/mongo)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/mongo) Provides a simple, elegant solution for using models stored in mongodb. For a more complex use cases, please take a look at the morphia module. 
[More](http://github.com/louth/play-mongo)
* **[[morphia] MongoDB Integration](http://www.playframework.com/modules/morphia)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/morphia)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.morphia/play-morphia)[![Updated since the play module registry was frozen](http://img.shields.io/badge/ -updated-ff69b4.svg?style=flat)](http://github.com/greenlaw110/play-morphia) Seamlessly MongoDB access integration with Play’s Model interface. 
[More](http://github.com/greenlaw110/play-morphia)
* **[[mybatisplay] MyBatisPlay](http://www.playframework.com/modules/mybatisplay)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/mybatisplay) Provides support for MyBatis persistence framework. 
[More](https://github.com/eamelink/play-navigation/wiki)
* **[[neo4j] logisima-neo4j](http://www.playframework.com/modules/neo4j)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/neo4j) Integrate neo4j database into your play! project. 
[More](https://github.com/sim51/logisima-play-neo4j)
* **[[objectify] Objectify](http://www.playframework.com/modules/objectify)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/objectify) Objectify is a flexible abstraction on Google App Engine/J which makes data access simple and elegant 
[More](http://code.google.com/p/play-framework-objectify/)
* **[[orientdb] OrientDB](http://www.playframework.com/modules/orientdb)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/orientdb) OrientDB for Play! Framework 
[More](https://github.com/mfornos/orientdb)
* **[[redis] Redis](http://www.playframework.com/modules/redis)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/redis)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.redis/play-redis) The Redis Play! module helps you easily use Redis in your Play! applications 
[More](https://github.com/tkral/play-redis)
* **[[riak] Riak](http://www.playframework.com/modules/riak)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/riak) Allow to use riak-java-client in play! way. 
[More](https://github.com/julienba/play-riak/)
* **[[s3blobs] S3Blobs](http://www.playframework.com/modules/s3blobs)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/s3blobs) The S3Blobs Play Framework Module provides an easy way to read an write files from Amazon S3 from within JPA entities. 
[More](https://github.com/jamesward/S3-Blobs-module-for-Play)
* **[[siena] Siena](http://www.playframework.com/modules/siena)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/siena)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.siena/play-siena)[![Updated since the play module registry was frozen](http://img.shields.io/badge/ -updated-ff69b4.svg?style=flat)](http://github.com/mandubian/play-siena) Enables Siena support to map your Java entities to GAE/MySQL/PostgreSQL/H2 from your play application 
[More](http://github.com/mandubian/play-siena)
* **[[twig] Twig](http://www.playframework.com/modules/twig)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/twig) Twig superpowers Google App Engine’s Datastore for Play applications. Get a fluid API, in-memory joins, and asynchronous queries out of the box. 
[More](https://github.com/netmau5/Play-Twig)
## Presentation 

* **[[formee] Formee](http://www.playframework.com/modules/formee)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/formee) Helps to write forms and add client and server side validation. 
[More](https://github.com/omaroman/formee)
* **[[coffee] CoffeeScript](http://www.playframework.com/modules/coffee)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/coffee)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.coffee/play-coffee) CoffeeScript is a great way to produce javascript. This module provides support for it (Java and Scala). 
[More](https://github.com/robfig/play-coffee)
* **[[excel] Excel](http://www.playframework.com/modules/excel)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/excel)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.excel/play-excel) Template based Excel report generator 
[More](http://github.com/greenlaw110/play-excel)
* **[[greenscript] Minimize javascript/css files](http://www.playframework.com/modules/greenscript)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/greenscript) Play with your javascript/css files! 
[More](http://github.com/greenlaw110/greenscript)
* **[[html5validation] HTML5 Validation](http://www.playframework.com/modules/html5validation)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/html5validation) Client-side form validation based on your Play framework model annotations using HTML5 attributes. 
[More](https://github.com/oasits/play-html5-validation)
* **[[jqueryui] Jqueryui](http://www.playframework.com/modules/jqueryui)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/jqueryui) The jQuery UI module provides working examples of jQuery UI widgets, integrated with a Play application. 
[More](https://github.com/lunatech-labs/play-module-jqueryui)
* **[[less] Less module](http://www.playframework.com/modules/less)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/less)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.less/play-less) Converts [less](http://lesscss.org/) to CSS, and handles error reporting in your Play application 
[More](https://github.com/lunatech-labs/play-module-less)
* **[[markdown] Markdown](http://www.playframework.com/modules/markdown)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/markdown)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.markdown/play-markdown) Easily bring markdown contents into your application. 
[More](https://github.com/orefalo/play-markdown)
* **[[menu] Menu](http://www.playframework.com/modules/menu)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/menu) Eases the implementation of navigation menu. 
[More](http://github.com/greenlaw110/play-menu)
* **[[navigation] Navigation](http://www.playframework.com/modules/navigation)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/navigation) Define and display navigation menus in your Play application.  
[More](https://bitbucket.org/hlassiege/play-nemrod)

* **[[paginate] Paginate](http://www.playframework.com/modules/paginate)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/paginate)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.paginate/play-paginate) A replacement for #{list} tags that allows for easy pagination. 
[More](http://github.com/lmcalpin/Play--Paginate)
* **[[pdf] PDF module](http://www.playframework.com/modules/pdf)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/pdf)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.pdf/play-pdf) Renders PDF document from your HTML templates. This module is based on the YaHP Converter library. 
[More](http://github.com/pepite/play--pdf)
* **[[pegdown] PegDown Markdown](http://www.playframework.com/modules/pegdown)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/pegdown) Integrates the pegdown [Markdown](https://github.com/sirthias/pegdown) processor with your Play application 
[More](https://github.com/jagregory/play-pegdown)
* **[[press] Minimize javascript/css files](http://www.playframework.com/modules/press)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/press) A JavaScript, CSS and Less minimizer that is designed to be transparent to the application developer. 
[More](http://github.com/dirkmc/press)
* **[[sass] Syntactically Awesome Stylesheets](http://www.playframework.com/modules/sass)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/sass)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.sass/play-sass) Sass makes CSS fun again. Sass is CSS, plus nested rules, variables, mixins, and more, all in a concise, readable syntax.  
[More](http://github.com/guillaumebort/play-sass)
* **[[table] Table](http://www.playframework.com/modules/table)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/table)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.table/play-table) Simplifies the code needed to display data in HTML tables. 
[More](https://github.com/julienrf/play-table)
* **[[tabularasa] Tabula Rasa](http://www.playframework.com/modules/tabularasa)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/tabularasa) Tabula Rasa provides support for user-customisable tables in views 
[More](https://github.com/schaloner/tabula-rasa)
* **[[twitterbootstrap] Twitterbootstrap](http://www.playframework.com/modules/twitterbootstrap)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/twitterbootstrap) Bundles up the twitter-bootstrap stylekit and the play less plugin, easing the .less files edition (changes are dynamically taken into account). 
[More](http://www.playframework.com/modules/twitterbootstrap)
## Rest 

* **[[jersey] Jersey](http://www.playframework.com/modules/jersey)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/jersey) Integrates Jersey into the Play! Framework. 
[More](https://bitbucket.org/psartini/play-jersey)
* **[[resteasy] RESTEasy Play! module](http://www.playframework.com/modules/resteasy)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/resteasy) The RESTEasy Play! module allows you to define JAX-RS RESTful web services in the Play! Framework using RESTEasy. 
[More](http://www.lunatech-labs.com/open-source/resteasy-play-module)
* **[[resteasycrud] RESTEasy CRUD module](http://www.playframework.com/modules/resteasycrud)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/resteasycrud) The Play! RESTEasy CRUD module which allows you to automagically generate your RESTful CRUD resources for a given model 
[More](http://www.lunatech-labs.com/open-source/resteasy-crud-play-module)
* **[[swagger] Swagger](http://www.playframework.com/modules/swagger)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/swagger) Creates a self-documenting meta-description for REST APIs which allows for code-gen, UI-sandbox, and test framework. 
[More](https://github.com/wordnik/swagger-play)
## Scaffolding 

* **[[crudsiena] CRUD for Siena](http://www.playframework.com/modules/crudsiena)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/crudsiena) Offers a fully usable web interface for your Siena Model objects with a few more features than default [crud] module.  
[More](https://github.com/mandubian/play-crud-siena)
* **[[mocha] Mocha](http://www.playframework.com/modules/mocha)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/mocha) An implementation of mocha UI javascript interface for Play! 
[More](https://bitbucket.org/blobsmith/mocha/overview)
* **[[scaffold] Scaffold](http://www.playframework.com/modules/scaffold)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/scaffold) Scaffold will generate basic scaffolding for bootstrapping a project from your JPA or Senia entities 
[More](http://github.com/lmcalpin/Play--Scaffold)
* **[[play-bootstrap] Basic bootstrap scaffolding](https://github.com/phaus/play-bootstrap)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-no-red.svg?style=flat)](https://github.com/phaus/play-bootstrap) Creating Bootstrap based applications (derived from the default [scaffold] module).  
[More](https://github.com/phaus/play-bootstrap)
## Security 

* **[[browserid] BrowserID](http://www.playframework.com/modules/browserid)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/browserid) BrowserID is an experimental new way of signing into websites. The goal with BrowserID is to design something safe and easy for users and the developers. 
[More](https://github.com/orefalo/play-browserid)
* **[[cas] logisima-cas](http://www.playframework.com/modules/cas)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cas) This module is a CAS client for Play! application. 
[More](http://github.com/sim51/logisima-play-cas)
* **[[casino] Casino](http://www.playframework.com/modules/casino)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/casino) This project provides a simple method to integrate sign-up and password recovery to your project 
[More](https://github.com/reyez/casino-play)
* **[[deadbolt] Deadbolt](http://www.playframework.com/modules/deadbolt)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/deadbolt)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.deadbolt/play-deadbolt) Deadbolt is an authorisation mechanism for defining access rights to certain controller methods or parts of a view 
[More](https://github.com/schaloner/deadbolt)
* **[[fbconnect] Facebook connect](http://www.playframework.com/modules/fbconnect)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/fbconnect) Easily integrate Facebook based authentication into any Play framework application. 
[More](https://github.com/murz/play-fbconnect)
* **[[force] Force.com](http://www.playframework.com/modules/force)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/force) Build Play! applications that integrates to Force.com. Provides OAuth authentication and REST API adapter. 
[More](https://github.com/jesperfj/play-force)
* **[[linkedin] LinkedIn OAuth Authentication](http://www.playframework.com/modules/linkedin)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/linkedin) Easily integrate LinkedIn’s OAuth authentication into your Play Framework application 
[More](http://geeks.aretotally.in/projects/play-framework-linkedin-module)
* **[[oauth] OAuth Client](http://www.playframework.com/modules/oauth)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/oauth) This module provides tools to connect to an OAuth provider, such as Twitter or Google. 
[More](http://github.com/erwan/playoauthclient)
* **[[recaptcha] Recaptcha](http://www.playframework.com/modules/recaptcha)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/recaptcha)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.recaptcha/play-recaptcha) Quickly integrate reCaptcha.com challenge-response test in your applications. 
[More](https://github.com/orefalo/play-recaptcha)
* **[[securepermissions] Secure Permissions](http://www.playframework.com/modules/securepermissions)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/securepermissions) Extends the defaut secure module to add permission checks based on the rules in the Seam Framework (based on Drools rules). 
[More](http://www.lunatech-labs.com/open-source/secure-permissions-play-module)
* **[[securesocial] SecureSocial](http://www.playframework.com/modules/securesocial)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/securesocial)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.securesocial/play-securesocial) SecureSocial allows you to add an authentication UI to your app that works with services based on OAuth1, OAuth2, OpenID and OpenID+OAuth hybrid protocols 
[More](http://jaliss.github.com/securesocial/)
* **[[shibboleth] Shibboleth](http://www.playframework.com/modules/shibboleth)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/shibboleth) Allow users to login to your Play! application via Shibboleth. 
[More](https://github.com/TAMULib/Shibboleth-play)
## Template 

* **[[fastergt] Faster Groovy Templates](http://www.playframework.com/modules/fastergt)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/fastergt)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.fastergt/play-fastergt) Replaces the default groovy template implementation with GT-Engine which is faster and uses less memory. 
[More](https://github.com/mbknor/faster-groovy-templates)
* **[[japid] Japid Template Engine](http://www.playframework.com/modules/japid)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/japid)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.japid/play-japid) A pure Java-based fast statically typed template engine for the Play! framework version 1.2.x. 
[More](http://github.com/branaway/Japid)
* **[[mustache] Mustache](http://www.playframework.com/modules/mustache)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/mustache) Allows you to define logic-less template snippets that can be used server-side in your Play! views as well as client-side in your JavaScript. 
[More](https://github.com/murz/play-mustache)
* **[[rythm] Rythm Template Engine](http://www.playframework.com/modules/rythm)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/rythm)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.rythm/play-rythm)[![Updated since the play module registry was frozen](http://img.shields.io/badge/ -updated-ff69b4.svg?style=flat)](https://github.com/greenlaw110/play-rythm) PlayRythm is a Razor like template engine. 
[More](https://github.com/greenlaw110/play-rythm)
* **[[scalate] Scalate](http://www.playframework.com/modules/scalate)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/scalate) [Scalate](http://scalate.fusesource.org) Template engine support.  
[More](http://github.com/pk11/play-scalate)
* **[[thymeleaf] Thymeleaf](http://www.playframework.com/modules/thymeleaf)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/thymeleaf) Play framework module to use [Thymeleaf 2.0](http://www.thymeleaf.org/)  as a template engine. 
[More](https://github.com/choreo/play-thymeleaf)
## Testing 

* **[[cobertura] Cobertura](http://www.playframework.com/modules/cobertura)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cobertura)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.cobertura/play-cobertura) Integrates with Cobertura to calculate the percentage of code accessed by tests (test coverage). 
[More](http://github.com/julienba/play-cobertura)
* **[[httpmock] HttpMock](http://www.playframework.com/modules/httpmock)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/httpmock) Caches WebService requests to emulate them in order to overcome connection problems (lag, denial of service, HTTP errors) for fast developping. 
[More](http://github.com/zenexity/play--httpmock)
* **[[mockito] Mockito](http://www.playframework.com/modules/mockito)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/mockito)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.mockito/play-mockito) Mockito is a mocking framework that tastes really good 
[More](https://github.com/eamelink/play-mockito)
* **[[qunit] QUnit](http://www.playframework.com/modules/qunit)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/qunit)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.qunit/play-qunit) The QUnit module provides integration of JUnit Javascript tests with the Play! Framework. 
[More](https://github.com/irregular-at/play-qunit)
* **[[spocktests] Spock tests](http://www.playframework.com/modules/spocktests)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/spocktests) Runs [Spock](https://code.google.com/p/spock/) specifications and to write BDD style tests (still wrapped as  junit) with the expressive power of groovy. 
[More](http://github.com/peterlundberg/play-spock-tests)
* **[[springtester] spring tester](http://www.playframework.com/modules/springtester)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/springtester)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.springtester/play-springtester) Write tests that can auto-magically inject mocks (using Mockito) into Play applications wired up using the spring module. 
[More](https://github.com/digiarnie/springtester)
* **[[tests] Alternative Test module](http://www.playframework.com/modules/tests)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/tests) The Test Module for Play!Framework helps you write tests quicker, is a cleaner and reusable manner. 
[More](https://github.com/GuyMograbi/play_test_module)
* **[[webdrive] Webdrive](http://www.playframework.com/modules/webdrive)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/webdrive)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.webdrive/play-webdrive) WebDrive module provides Selenium 2 testing support for Play framework 
[More](https://github.com/rkaippully/play-webdrive)
## Translation 

* **[[i18ntools] I18ntools](http://www.playframework.com/modules/i18ntools)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/i18ntools) This module will add some tools to ease use of i18n in your Play! projects. 
[More](http://github.com/naholyr/i18ntools)
* **[[messages] @messages](http://www.playframework.com/modules/messages)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/messages)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.messages/play-messages) Module messages provides a web based tool for managing your application’s localizations. 
[More](https://github.com/huljas/play-messages)
* **[[nemrod] Nemrod](http://www.playframework.com/modules/nemrod)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/nemrod) This module helps to import and export translations from your application to a Nemrod instance automatically. 
[More](https://github.com/sim51/logisima-play-neo4j)
## Translations 

* **[[play-i18ned] Play-i18ned](https://github.com/phaus/play-i18ned)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-no-red.svg?style=flat)](https://github.com/phaus/play-i18ned) Converts default i18n files from an Excel Sheet and the other way around. 
[More](https://github.com/phaus/play-i18ned)
## Misc 

* **[[akka] Akka support](http://www.playframework.com/modules/akka)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/akka) Allows you to configure [akka](http://akkasource.org) through The Play! framework’s conf/application.conf file. 
[More](http://github.com/dwhitney/akka)
* **[[bespin] Bespin online editor](http://www.playframework.com/modules/bespin)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/bespin) Allows you to edit all the application sources directly in the browser using bespin, the web code editor. 
[More](http://github.com/erwan/playbespin)
* **[[bhave] Bhave](http://www.playframework.com/modules/bhave)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/bhave) Integrates with [bhave](http://bhave.org/), a web-based behavior driven development (BDD) framework, for web apps, done in a funky way! 
[More](http://bhave.org/)
* **[[camel] Camel](http://www.playframework.com/modules/camel)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/camel) A EIP + Messaging module for the Play! Framework 
[More](https://github.com/marcuspocus/play-camel)
* **[[cheese] Cheese](http://www.playframework.com/modules/cheese)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cheese) Simplified API for integration your application with the CheddarGetter subscription management service. 
[More](https://github.com/lmcalpin/Play--Cheese)
* **[[cms] Cms](http://www.playframework.com/modules/cms)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cms) A very simple embedded CMS 
[More](http://code.google.com/p/play-cms/)
* **[[cnm] Content Negotiation](http://www.playframework.com/modules/cnm)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cnm) Helps using content types which are not directly supported by default such as VCard and Atom/RSS feeds using annotations. 
[More](http://github.com/oasits/play-content-negotiation)
* **[[elasticsearch] ElasticSearch](http://www.playframework.com/modules/elasticsearch)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/elasticsearch) Elastic Search is a Distributed Search Solution based on Apache Lucene. This module provides an embedded Elastic Server instance for Rapid Development. 
[More](http://geeks.aretotally.in/play-framework-module-elastic-search-distributed-searching-with-json-http-rest-or-java)
* **[[externalconfig] External Config](http://www.playframework.com/modules/externalconfig)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/externalconfig) Allows easy loading of external config / properties files. This allows for easy configuration of an app deployed in a war. 
[More](https://github.com/rugbyhead/externalconfig)
* **[[featureflags] Feature Flags](http://www.playframework.com/modules/featureflags)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/featureflags) Enables you to easily use flags in your application that you can switch ON and OFF at runtime, using an admin screen. 
[More](http://code.google.com/p/play-featureflags)
* **[[googlecheckout] Google Checkout](http://www.playframework.com/modules/googlecheckout)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/googlecheckout) Enable your Play application to integrate with Google Checkout as a merchant. 
[More](https://github.com/jagregory/play-google-checkout)
* **[[gravatar] Gravatar](http://www.playframework.com/modules/gravatar)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/gravatar)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.gravatar/play-gravatar) Integrate Gravatar into your Play application 
[More](https://github.com/mbarbieri/play-gravatar)
* **[[hazelcast] Hazelcast](http://www.playframework.com/modules/hazelcast)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/hazelcast)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.hazelcast/play-hazelcast) This module is a dropin replacement for EhCacheImpl or MemcachedImpl from Play 
[More](https://github.com/marcuspocus/hazelcast)
* **[[jelastic] Jelastic Deployment Support](http://www.playframework.com/modules/jelastic)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/jelastic) This module helps you remotely deploy your Play! application in to Jelastic Platform. 
[More](https://github.com/Fameing/play-jelastic)
* **[[jqvalidate] JQuery Validation](http://www.playframework.com/modules/jqvalidate)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/jqvalidate) Client-side form validation via jQuery, based on your Play framework model annotation 
[More](https://github.com/murz/play-jqvalidate)
* **[[jqvalidation] Jqvalidation](http://www.playframework.com/modules/jqvalidation)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/jqvalidation) A jquery library API for validation, supports Ajax validation (per field or per Form) 
[More](http://code.google.com/p/jqvalidate-play-framework/)
* **[[postmark] Postmark](http://www.playframework.com/modules/postmark)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/postmark)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.postmark/play-postmark) Postmark module provides easy integration with postmarkapp.com for handling outgoing emails 
[More](https://github.com/FrostDigital/play-postmark)
* **[[pusher] Pusher](http://www.playframework.com/modules/pusher)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/pusher) This module lets you easily add realtime functionality to your Play applications with [Pusher](http://www.pusher.com) using websockets. 
[More](https://github.com/regisbamba/Play-Pusher)
* **[[rabbitmq] RabbitMQ](http://www.playframework.com/modules/rabbitmq)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/rabbitmq) RabbitMQ offers a highly available and scalable, and yet lightweight, messaging system. 
[More](http://geeks.aretotally.in/rabbitmq-module-for-play-framework)
* **[[search] Search](http://www.playframework.com/modules/search)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/search)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.search/play-search) Search allows you to have basic full text search functionalities to your JPA Model. It is based on Lucene. 
[More](http://github.com/jfp/play-search/)
* **[[useragentcheck] UserAgentCheck](http://www.playframework.com/modules/useragentcheck)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/useragentcheck) UserAgentCheck displays a banner to notify users when their browser is outdated. 
[More](https://github.com/orefalo/play-useragentcheck)


# Tools
*You know a tool that every player should use? [Tell us!](https://github.com/PerfectCarl/awesome-play1/edit/master/README.md)*

# Resources

- [Mavenized modules](https://code.google.com/p/maven-play-plugin/wiki/MavenizedModules)
- [Using Play's controller](http://www.javabeat.net/using-controllers-in-play-framework/) with a nice roundup about caching, expiration and eTags
- Using Luo's `cache4` [annotation](https://code.google.com/p/maven-play-plugin/wiki/MavenizedModules)
- [How to write modules](http://www.packtpub.com/article/play-framework-introduction-writing-modules)
