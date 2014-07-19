# Awesome Play1 [![play-isthe1!](http://img.shields.io/badge/play-isthe1-red.svg?style=flat)](https://github.com/markets/awesome-ruby)

A collection of awesome Play 1.x [modules](#modules), [tools](#tools), and [resources](#resources).

>Inspired by [awesome-php](https://github.com/ziadoz/awesome-php), [awesome-python](https://github.com/vinta/awesome-python), [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks) and [awesome-ruby](https://github.com/markets/awesome-ruby).

Contributions are always welcome! Please take a look at the [contribution guidelines and quality standard](https://github.com/PerfectCarl/awesome-play1/blob/master/CONTRIBUTING.md) first.

# Modules
Lists all the modules available for Play 1.x.
 * [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/carbonate) : 
 * [![registered on playframework.com/modules](http://img.shields.io/badge/registered-no-red.svg?style=flat)](https://github.com/PerfectCarl/play-profiler) :
 * [![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.db/play-db) :
 * [![Updated since the play module registry was frozen](http://img.shields.io/badge/ -updated-ff69b4.svg?style=flat)]() : 

All the modules in [a spreadsheet](https://docs.google.com/spreadsheets/d/1b-_ipGbktIRnwyipoIpP3bcR-JlpEM3S_OA31r40-L0)
 * [Database](#database) 
 * [Deployment](#deployment) 
 * [Forms](#forms) 
 * [Injection/dependencies](#injectiondependencies) 
 * [Language](#language) 
 * [Monitoring](#monitoring) 
 * [Persistence](#persistence) 
 * [Presentation](#presentation) 
 * [Rest](#rest) 
 * [Security](#security) 
 * [Template](#template) 
 * [Translation](#translation) 
 * [Misc](#misc) 


### Database 

* **[[carbonate] Carbonate](http://www.playframework.com/modules/carbonate)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/carbonate) Module for creating and running database migrations for Play application. Uses Hibernate schema update to automatically generate SQL to the migrations. See this blog [post](http://huljas.github.com/code/2011/04/04/managing-database-with-play-carbonate.html) 

* **[[jpagen] JpaGen](http://www.playframework.com/modules/jpagen)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/jpagen) JPAGEN aim at generating JPA Entities and Composite keys (when needed) from metadata or a file containing a list of tables. 

* **[[liquibase] Liquibase](http://www.playframework.com/modules/liquibase)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/liquibase) [Liquibase](http://www.liquibase.org) is a simple, reliable and elegant solution for database refactoring management 

* **[[logisimayml] logisima-yml](http://www.playframework.com/modules/logisimayml)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/logisimayml) Logisima-yml helps you to export your database into an yml file 

* **[[migrate] Database migration](http://www.playframework.com/modules/migrate)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/migrate) This module allows you to easily maintain database versions for your project. 

* **[[multidb] Multiple Databases](http://www.playframework.com/modules/multidb)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/multidb) This module allows you to scale your Play! apps to multiple databases with a common schema. 

* **[[db] Database module](http://www.playframework.com/modules/db)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/db)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.db/play-db) Export your Play! domain model to a DDL file and import a database into your Play! domain model. 

* **[[chronostamp] Chronostamp](http://www.playframework.com/modules/chronostamp)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/chronostamp) Chronostamp enhances Models by adding magic timestamp fields (created_at & updated_at) and it will automatically record creation and update timestamps of database objects in an unobtrusive way. 

## Deployment 

* **[[capistrano] Capistrano](http://www.playframework.com/modules/capistrano)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/capistrano) Here is a draft module to deploy a remote play app using Capistrano + SSH + VCS and run it in nohup/background mode. 

* **[[cargo] Cargo](http://www.playframework.com/modules/cargo)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cargo) This module helps you remotely deploy your Play! application. 

* **[[cloudbees] CloudBees](http://www.playframework.com/modules/cloudbees)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cloudbees) This module provides integration with CloudBees. 

* **[[cloudfoundry] CloudFoundry](http://www.playframework.com/modules/cloudfoundry)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cloudfoundry) In CloudFoundry, when a database resource is linked to an application, the credentials are put in an environment variable. This module automatically reads this variable and configures the Play database. 

* **[[dotcloud] Dotcloud](http://www.playframework.com/modules/dotcloud)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/dotcloud) This module helps you deploy your Play! application to dotcloud 

* **[[gae] Google App Engine](http://www.playframework.com/modules/gae)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/gae)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.gae/play-gae) Creates application for the Google App Engine platform. 

* **[[heroku] Heroku](http://www.playframework.com/modules/heroku)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/heroku) This module makes it easy to deploy Play applications on Heroku. 

* **[[openebay] Open eBay](http://www.playframework.com/modules/openebay)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/openebay) This module provides the basic plumbing to create an [Open eBay Application](http://apps.ebay.com/) 

* **[[openshift] Openshift](http://www.playframework.com/modules/openshift)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/openshift) Openshift is Red Hat’s free, auto-scaling, cloud-based platform-as-a-service for Java, Perl, PHP, Python, and Ruby applications. 

* **[[playapps] playapps.net](http://www.playframework.com/modules/playapps)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/playapps) playapps.net is a streamlined deployment environment designed to get your Play applications up and running quickly and efficiently 

* **[[reverseproxy] ReverseProxy](http://www.playframework.com/modules/reverseproxy)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/reverseproxy) ReverseProxy allows developers to configure web applications to automatically switch between the HTTP and HTTPS protocols per page when used behind a front end  

* **[[router] Play Router Annotations](http://www.playframework.com/modules/router)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/router)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.router/play-router) Adds routes through annotations, allowing you to declare your routes in your controllers. 

* **[[stax] Stax](http://www.playframework.com/modules/stax)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/stax) Easy deployment to Stax cloud hosting platform (http://www.stax.net). 

* **[[vhost] VHost](http://www.playframework.com/modules/vhost)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/vhost) Adds some virtual hosts functionality with separate datasource and customizable application settings for each virtual host. 

## Forms 

* **[[formee] Formee](http://www.playframework.com/modules/formee)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/formee) Formee eases and helps out to build html forms designs, and also validates its data from both client-side and server-side based on model validation annotations. 

## Injection/dependencies 

* **[[constretto] Constretto](http://www.playframework.com/modules/constretto)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/constretto)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.constretto/play-constretto) Makes integration with the Constretto configration framework easy 

* **[[guice] Guice](http://www.playframework.com/modules/guice)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/guice)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.guice/play-guice) Injects Guice managed components into your application. 

* **[[ivy] Ivy dependency management](http://www.playframework.com/modules/ivy)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/ivy) This module lets you manage your dependencies with apache ivy. 

* **[[maven] Maven dependency management](http://www.playframework.com/modules/maven)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/maven) This module lets you manage your dependencies with apache mave 

* **[[spring] Spring](http://www.playframework.com/modules/spring)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/spring)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.spring/play-spring) This module allows to use Spring managed beans inside your play! 1.x applications. 

## Language 

* **[[googleclosure] Google Closure](http://www.playframework.com/modules/googleclosure)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/googleclosure) This module is aimed at integrating Google Closure tools with play!. 

* **[[gwt] Google Web Toolkit](http://www.playframework.com/modules/gwt)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/gwt) This module provides a helper to simplify the integration of a GWT UI with Play as an application server. 

* **[[gwt2] GWT2](http://www.playframework.com/modules/gwt2)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/gwt2) Integrates Play with GWT 

* **[[scala] Scala](http://www.playframework.com/modules/scala)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/scala)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.scala/play-scala) Play Scala enables you to use the Scala language for your application keeping key properties of the Play framework 

## Messaging 

* **[[camel] Camel](http://www.playframework.com/modules/camel)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/camel) A EIP + Messaging module for the Play! Framework 

## Monitoring 

* **[[accesslog] Accesslog](http://www.playframework.com/modules/accesslog)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/accesslog)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.accesslog/play-accesslog) A Play framework module that performs request logging similar to an access log file in nginx or apache. 

* **[[betterlogs] BetterLogs](http://www.playframework.com/modules/betterlogs)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/betterlogs) This very simple module enhances the Play! Framework logs to bring some missing information such as the class name, the method name where the log has been called, its signature, the file name and the line. 

* **[[jpastats] Jpastats](http://www.playframework.com/modules/jpastats)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/jpastats) Record how many database queries were executed during a request 

* **[[playerrors] Playerrors](http://www.playframework.com/modules/playerrors)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/playerrors) Playerrors gathers and informs you about the errors in your production webapps, so you can fix them before your visitors get a chance to complain 

* **[[recordtracking] RecordTracking](http://www.playframework.com/modules/recordtracking)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/recordtracking) RecordTracking unobtrusively tracks the creation, updating and elimination events regarding to records. 

* **[[statsd] Statsd](http://www.playframework.com/modules/statsd)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/statsd) The module is a wrapper over [StatsD](https://github.com/etsy/statsd) which allow for dead simple statistic aggregation from within play. 

* **[[infoplay] InfoPlay](http://www.playframework.com/modules/infoplay)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/infoplay) InfoPlay is a module which gives many informations like infophp in PHP language. 

* **[[log4play] Log4Play](http://www.playframework.com/modules/log4play)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/log4play) Log4Play is a module that provides a log4j appender which publishes log entries to an EventStream 

## Persistence 

* **[[associations] Associations](http://www.playframework.com/modules/associations)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/associations)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.associations/play-associations) This module reduces the code to manage bi-directional associations. 

* **[[cream] JCR for Play!](http://www.playframework.com/modules/cream)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cream) A module that seamlessly integrates Apache Jackrabbit(JCR 2.0) with Play framework 

* **[[ebean] EBean ORM support](http://www.playframework.com/modules/ebean)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/ebean)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.ebean/play-ebean) Adds Ebean ORM to play!. Still in very experimental phase. 

* **[[mongo] MongoDB](http://www.playframework.com/modules/mongo)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/mongo) This module provides a simple, elegant solution for using models stored in mongodb. For a more complex use cases, please take a look at the morphia module. 

* **[[morphia] MongoDB Integration](http://www.playframework.com/modules/morphia)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/morphia)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.morphia/play-morphia)[![Updated since the play module registry was frozen](http://img.shields.io/badge/ -updated-ff69b4.svg?style=flat)]() Seamlessly MongoDB access integration with Play’s Model interface. 

* **[[mybatisplay] MyBatisPlay](http://www.playframework.com/modules/mybatisplay)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/mybatisplay) This module provides support for MyBatis persistence framework. 

* **[[neo4j] logisima-neo4j](http://www.playframework.com/modules/neo4j)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/neo4j) Integrate neo4j database into your play! project. 

* **[[objectify] Objectify](http://www.playframework.com/modules/objectify)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/objectify) Objectify is a flexible abstraction on Google App Engine/J which makes data access simple and elegant 

* **[[orientdb] OrientDB](http://www.playframework.com/modules/orientdb)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/orientdb) OrientDB for Play! Framework 

* **[[redis] Redis](http://www.playframework.com/modules/redis)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/redis)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.redis/play-redis) The Redis Play! module helps you easily use Redis in your Play! applications 

* **[[siena] Siena](http://www.playframework.com/modules/siena)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/siena)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.siena/play-siena)[![Updated since the play module registry was frozen](http://img.shields.io/badge/ -updated-ff69b4.svg?style=flat)]() The siena module enables Siena support to map your Java entities to GAE/MySQL/PostgreSQL/H2 from your play application 

* **[[twig] Twig](http://www.playframework.com/modules/twig)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/twig) Twig superpowers Google App Engine’s Datastore for Play applications. Get a fluid API, in-memory joins, and asynchronous queries out of the box. 

## Presentation 

* **[[jqueryui] Jqueryui](http://www.playframework.com/modules/jqueryui)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/jqueryui) The jQuery UI module provides working examples of jQuery UI widgets, integrated with a Play application. 

* **[[coffee] CoffeeScript](http://www.playframework.com/modules/coffee)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/coffee)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.coffee/play-coffee) CoffeeScript is a great way to produce javascript. This module provides support for it (Java and Scala). 

* **[[greenscript] Minimize javascript/css files](http://www.playframework.com/modules/greenscript)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/greenscript) Play with your javascript/css files! 

* **[[less] Less module](http://www.playframework.com/modules/less)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/less)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.less/play-less) The less module automatically converts [less](http://lesscss.org/) to CSS, and handles error reporting in your Play application 

* **[[press] Minimize javascript/css files](http://www.playframework.com/modules/press)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/press) The press module is a JavaScript, CSS and Less minimizer that is designed to be transparent to the application developer. 

* **[[crudsiena] CRUD for Siena](http://www.playframework.com/modules/crudsiena)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/crudsiena) The CRUD (Create, Read, Update, Delete) Siena module a fully usable web 
interface for your Siena Model objects with a few more features than 
default CRUD.  

* **[[excel] Excel](http://www.playframework.com/modules/excel)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/excel)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.excel/play-excel) Template based Excel report generator 

* **[[html5validation] HTML5 Validation](http://www.playframework.com/modules/html5validation)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/html5validation) Client-side form validation based on your Play framework model annotations using HTML5 attributes. 

* **[[menu] Menu](http://www.playframework.com/modules/menu)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/menu) help app developer to easily implement navigation menu 

* **[[mocha] Mocha](http://www.playframework.com/modules/mocha)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/mocha) Mocha module for Play! Framework is an implementation of mocha UI javascript interface for Play! 

* **[[navigation] Navigation](http://www.playframework.com/modules/navigation)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/navigation) Define and display navigation menus in your Play application.  

* **[[paginate] Paginate](http://www.playframework.com/modules/paginate)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/paginate)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.paginate/play-paginate) A replacement for #{list} tags that allows for easy pagination. 

* **[[pdf] PDF module](http://www.playframework.com/modules/pdf)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/pdf)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.pdf/play-pdf) A module that allows you to render PDF document from your HTML templates. This module is based on the YaHP Converter library. 

* **[[sass] Syntactically Awesome Stylesheets](http://www.playframework.com/modules/sass)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/sass)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.sass/play-sass) Sass makes CSS fun again. Sass is CSS, plus nested rules, variables, mixins, and more, all in a concise, readable syntax.  

* **[[table] Table](http://www.playframework.com/modules/table)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/table)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.table/play-table) This module aims to simplify the code needed to display data in HTML tables. 

* **[[tabularasa] Tabula Rasa](http://www.playframework.com/modules/tabularasa)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/tabularasa) Tabula Rasa provides support for user-customisable tables in views 

* **[[twitterbootstrap] Twitterbootstrap](http://www.playframework.com/modules/twitterbootstrap)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/twitterbootstrap) Play module that bundles up the twitter-bootstrap stylekit and the play less plugin, so that you can use twitter-bootstrap, edit the .less files and have your changes picked up and dynamically rendered to css. 

* **[[markdown] Markdown](http://www.playframework.com/modules/markdown)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/markdown)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.markdown/play-markdown) Easily bring markdown contents into your application. 

* **[[pegdown] PegDown Markdown](http://www.playframework.com/modules/pegdown)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/pegdown) Integrate the pegdown [Markdown](https://github.com/sirthias/pegdown) processor with your Play application 

## Rest 

* **[[jersey] Jersey](http://www.playframework.com/modules/jersey)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/jersey) Integrates Jersey into the Play! Framework. 

* **[[resteasy] RESTEasy Play! module](http://www.playframework.com/modules/resteasy)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/resteasy) The RESTEasy Play! module allows you to define JAX-RS RESTful web services in the Play! Framework using RESTEasy. 

* **[[resteasycrud] RESTEasy CRUD module](http://www.playframework.com/modules/resteasycrud)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/resteasycrud) The Play! RESTEasy CRUD module which allows you to automagically generate your RESTful CRUD resources for a given model 

* **[[swagger] Swagger](http://www.playframework.com/modules/swagger)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/swagger) Creates a self-documenting meta-description for REST APIs which allows for code-gen, UI-sandbox, and test framework. 

## Security 

* **[[browserid] BrowserID](http://www.playframework.com/modules/browserid)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/browserid) BrowserID is an experimental new way of signing into websites. The goal with BrowserID is to design something safe and easy for users and the developers. 

* **[[cas] logisima-cas](http://www.playframework.com/modules/cas)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cas) This module is a CAS client for Play! application. 

* **[[casino] Casino](http://www.playframework.com/modules/casino)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/casino) This project provides a simple method to integrate sign-up and password recovery to your project 

* **[[deadbolt] Deadbolt](http://www.playframework.com/modules/deadbolt)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/deadbolt)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.deadbolt/play-deadbolt) Deadbolt is an authorisation mechanism for defining access rights to certain controller methods or parts of a view 

* **[[fbconnect] Facebook connect](http://www.playframework.com/modules/fbconnect)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/fbconnect) Easily integrate Facebook based authentication into any Play framework application. 

* **[[force] Force.com](http://www.playframework.com/modules/force)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/force) Build Play! applications that integrates to Force.com. Provides OAuth authentication and REST API adapter. 

* **[[linkedin] LinkedIn OAuth Authentication](http://www.playframework.com/modules/linkedin)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/linkedin) Easily integrate LinkedIn’s OAuth authentication into your Play Framework application 

* **[[oauth] OAuth Client](http://www.playframework.com/modules/oauth)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/oauth) This module provides tools to connect to an OAuth provider, such as Twitter or Google. 

* **[[recaptcha] Recaptcha](http://www.playframework.com/modules/recaptcha)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/recaptcha)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.recaptcha/play-recaptcha) Quickly integrate reCaptcha.com challenge-response test in your applications. 

* **[[scalasecure] Scala secure](http://www.playframework.com/modules/scalasecure)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/scalasecure) This module provides basic security (authentication/ authorization) for Play applications written in Scala. 

* **[[securepermissions] Secure Permissions](http://www.playframework.com/modules/securepermissions)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/securepermissions) The Secure Permissions Play! module extends the Secure module in Play! Framework to add permission checks based on the rule-based permissions in the Seam Framework (based on Drools rules). 

* **[[securesocial] SecureSocial](http://www.playframework.com/modules/securesocial)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/securesocial)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.securesocial/play-securesocial) SecureSocial allows you to add an authentication UI to your app that works with services based on OAuth1, OAuth2, OpenID and OpenID+OAuth hybrid protocols 

* **[[shibboleth] Shibboleth](http://www.playframework.com/modules/shibboleth)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/shibboleth) Allow users to login to your Play! application via Shibboleth. 

## Template 

* **[[fastergt] Faster Groovy Templates](http://www.playframework.com/modules/fastergt)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/fastergt)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.fastergt/play-fastergt) This is a module for Play! Framework 1 applications which replaces the default groovy template implementation with GT-Engine which is faster and uses less memory. 

* **[[japid] Japid Template Engine](http://www.playframework.com/modules/japid)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/japid)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.japid/play-japid) A pure Java-based fast statically typed template engine for the Play! framework version 1.2.x. 

* **[[mustache] Mustache](http://www.playframework.com/modules/mustache)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/mustache) Allows you to define logic-less template snippets that can be used server-side in your Play! views as well as client-side in your JavaScript. 

* **[[rythm] Rythm Template Engine](http://www.playframework.com/modules/rythm)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/rythm)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.rythm/play-rythm)[![Updated since the play module registry was frozen](http://img.shields.io/badge/ -updated-ff69b4.svg?style=flat)]() PlayRythm is a Razor like template engine. 

* **[[scalate] Scalate](http://www.playframework.com/modules/scalate)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/scalate) [Scalate](http://scalate.fusesource.org) Template engine support.  

* **[[thymeleaf] Thymeleaf](http://www.playframework.com/modules/thymeleaf)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/thymeleaf) Play framework module to use [Thymeleaf 2.0](http://www.thymeleaf.org/)  as a template engine. 

## Testing 

* **[[mockito] Mockito](http://www.playframework.com/modules/mockito)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/mockito)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.mockito/play-mockito) Mockito is a mocking framework that tastes really good 

* **[[httpmock] HttpMock](http://www.playframework.com/modules/httpmock)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/httpmock) play-httpmock caches WebService requests to emulate them in order to overcome connection problems (lag, denial of service, HTTP errors) for fast developping. 

* **[[qunit] QUnit](http://www.playframework.com/modules/qunit)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/qunit)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.qunit/play-qunit) The QUnit module provides integration of JUnit Javascript tests with the Play! Framework. 

* **[[spocktests] Spock tests](http://www.playframework.com/modules/spocktests)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/spocktests) This module allows running [Spock](https://code.google.com/p/spock/) specifications and to write BDD style tests (still wrapped as  junit) with the expressive power of groovy. 

* **[[springtester] spring tester](http://www.playframework.com/modules/springtester)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/springtester)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.springtester/play-springtester) Write tests that can auto-magically inject mocks (using Mockito) into Play applications wired up using the spring module. 

* **[[tests] Alternative Test module](http://www.playframework.com/modules/tests)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/tests) The Test Module for Play!Framework helps you write tests quicker, is a cleaner and reusable manner. 

* **[[webdrive] Webdrive](http://www.playframework.com/modules/webdrive)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/webdrive)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.webdrive/play-webdrive) WebDrive module provides Selenium 2 testing support for Play framework 

## Translation 

* **[[i18ntools] I18ntools](http://www.playframework.com/modules/i18ntools)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/i18ntools) This module will add some tools to ease use of i18n in your Play! projects. 

* **[[messages] @messages](http://www.playframework.com/modules/messages)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/messages)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.messages/play-messages) Module messages provides a web based tool for managing your application’s localizations. 

* **[[nemrod] Nemrod](http://www.playframework.com/modules/nemrod)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/nemrod) This module helps to import and export translations from your application to a Nemrod instance automatically. 

## Misc 

* **[[akka] Akka support](http://www.playframework.com/modules/akka)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/akka) [Akka](http://akkasource.org) is a platform for building simple, correct, fault-tolerant, concurrent, and scalable applications for the JVM. This module allows you to configure akka through The Play! framework’s conf/application.conf file; it provides a few command-line scripts to start akka when your application starts; and it has some examples of it in action. 

* **[[bespin] Bespin online editor](http://www.playframework.com/modules/bespin)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/bespin) Bespin is a Mozilla Labs experiment on how to build an extensible web code editor using HTML 5 technology. The play bespin module allows you to edit all the application sources directly in the browser using bespin. 

* **[[bhave] Bhave](http://www.playframework.com/modules/bhave)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/bhave) Integrates with [bhave](http://bhave.org/), a web-based behavior driven development (BDD) framework, for web apps, done in a funky way! 

* **[[cheese] Cheese](http://www.playframework.com/modules/cheese)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cheese) Simplified API for integration Play! applications with the CheddarGetter subscription management service. 

* **[[cms] Cms](http://www.playframework.com/modules/cms)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cms) A very simple embedded CMS 

* **[[cnm] Content Negotiation](http://www.playframework.com/modules/cnm)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cnm) The content negotiation module helps using content types which are not directly supported by the Play! framework such as VCard and Atom/RSS feeds using annotations. 

* **[[cobertura] Cobertura](http://www.playframework.com/modules/cobertura)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/cobertura)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.cobertura/play-cobertura) Cobertura is a free Java tool that calculates the percentage of code accessed by tests. It can be used to identify which parts of your Java program are lacking test coverage. 

* **[[elasticsearch] ElasticSearch](http://www.playframework.com/modules/elasticsearch)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/elasticsearch) Elastic Search is a Distributed Search Solution based on Apache Lucene. This module provides an embedded Elastic Server instance for Rapid Development. 

* **[[externalconfig] External Config](http://www.playframework.com/modules/externalconfig)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/externalconfig) Allows easy loading of external config / properties files. This allows for easy configuration of an app deployed in a war. 

* **[[featureflags] Feature Flags](http://www.playframework.com/modules/featureflags)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/featureflags) play-featureflags is a module for playframework that enables you to easily use ‘feature flags’ in your application. A feature flag is any piece of functionality in your application that you want to be able to switch ON and OFF at runtime, using an admin screen. 

* **[[googlecheckout] Google Checkout](http://www.playframework.com/modules/googlecheckout)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/googlecheckout) Enable your Play application to integrate with Google Checkout as a merchant. 

* **[[gravatar] Gravatar](http://www.playframework.com/modules/gravatar)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/gravatar)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.gravatar/play-gravatar) Integrate Gravatar into your Play application 

* **[[hazelcast] Hazelcast](http://www.playframework.com/modules/hazelcast)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/hazelcast)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.hazelcast/play-hazelcast) This module is a dropin replacement for EhCacheImpl or MemcachedImpl from Play 

* **[[jelastic] Jelastic Deployment Support](http://www.playframework.com/modules/jelastic)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/jelastic) This module helps you remotely deploy your Play! application in to Jelastic Platform. 

* **[[jqvalidate] JQuery Validation](http://www.playframework.com/modules/jqvalidate)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/jqvalidate) Client-side form validation via jQuery, based on your Play framework model annotation 

* **[[jqvalidation] Jqvalidation](http://www.playframework.com/modules/jqvalidation)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/jqvalidation) A jquery library API for validation, supports Ajax validation (per field or per Form) 

* **[[postmark] Postmark](http://www.playframework.com/modules/postmark)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/postmark)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.postmark/play-postmark) Postmark module provides easy integration with postmarkapp.com for handling outgoing emails 

* **[[pusher] Pusher](http://www.playframework.com/modules/pusher)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/pusher) This module lets you easily add realtime functionality to your Play applications with [Pusher](http://www.pusher.com) using websockets. 

* **[[rabbitmq] RabbitMQ](http://www.playframework.com/modules/rabbitmq)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/rabbitmq) RabbitMQ offers a highly available and scalable, and yet lightweight, messaging system. 

* **[[riak] Riak](http://www.playframework.com/modules/riak)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/riak) Allow to use riak-java-client in play! way. 

* **[[s3blobs] S3Blobs](http://www.playframework.com/modules/s3blobs)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/s3blobs) The S3Blobs Play Framework Module provides an easy way to read an write files from Amazon S3 from within JPA entities. 

* **[[scaffold] Scaffold](http://www.playframework.com/modules/scaffold)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/scaffold) Scaffold will generate basic scaffolding for bootstrapping a project from your JPA or Senia entities 

* **[[scalagen] Scala Gen](http://www.playframework.com/modules/scalagen)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/scalagen) Scala code generators for the Play! framework 

* **[[search] Search](http://www.playframework.com/modules/search)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/search)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.search/play-search) Search allows you to have basic full text search functionalities to your JPA Model. It is based on Lucene. 

* **[[useragentcheck] UserAgentCheck](http://www.playframework.com/modules/useragentcheck)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-yes-green.svg?style=flat)](http://www.playframework.com/modules/useragentcheck) UserAgentCheck provides an easy way to notify users when their browser is outdated. It displays a banner (blocking or non blocking) that drives the user to a page where he/she may download an upgrade. 

* **[[profiler] Mini-profiler](https://github.com/PerfectCarl/play-profiler)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-no-red.svg?style=flat)](https://github.com/PerfectCarl/play-profiler) Displays a mini profiler in your application 

* **[[play-gae-q42] Q42's Google App Engine](https://github.com/Q42/play-gae)** [![registered on playframework.com/modules](http://img.shields.io/badge/registered-no-red.svg?style=flat)](https://github.com/Q42/play-gae) Maintained module for Google App Engine integration 



# Tools
*You know a tool that every player should use? [Tell us!](https://github.com/PerfectCarl/awesome-play1/edit/master/README.md)*

# Resources

- [Mavenized modules](https://code.google.com/p/maven-play-plugin/wiki/MavenizedModules)
- [Using Play's controller](http://www.javabeat.net/using-controllers-in-play-framework/) with a nice roundup about caching, expiration and eTags
- Using Luo's `cache4` [annotation](https://code.google.com/p/maven-play-plugin/wiki/MavenizedModules)
- [How to write modules](http://www.packtpub.com/article/play-framework-introduction-writing-modules)
