# Awesome Play1 [![play-isthe1!](http://img.shields.io/badge/play-isthe1-red.svg?style=flat)](https://github.com/markets/awesome-ruby)

A collection of awesome Play 1.x modules, tools, and resources.

>Inspired by [awesome-php](https://github.com/ziadoz/awesome-php), [awesome-python](https://github.com/vinta/awesome-python), [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks) and [awesome-ruby](https://github.com/markets/awesome-ruby).

Contributions are always welcome! Please take a look at the [contribution guidelines and quality standard](https://github.com/PerfectCarl/awesome-play1/blob/master/CONTRIBUTING.md) first.

# Modules

All the modules in [a spreadsheet](https://docs.google.com/spreadsheets/d/1b-_ipGbktIRnwyipoIpP3bcR-JlpEM3S_OA31r40-L0)

[accesslog] ![official](http://img.shields.io/badge/ -official-green.svg?style=flat) _ [![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.accesslog/play-accesslog)
> A Play framework module that performs request logging similar to an access log file in nginx or apache.
>
> [Project page](https://github.com/briannesbitt/play-accesslog) ![github](http://img.shields.io/badge/ -github-lightgrey.svg?style=flat)


[[accesslog] accesslog](http://www.playframework.com/modules/accesslog) [![official](http://img.shields.io/badge/ -official-green.svg?style=flat)](http://www.playframework.com/modules/accesslog)[![mavenized](http://img.shields.io/badge/ -mavenized-blue.svg?style=flat)](http://mvnrepository.com/artifact/com.google.code.maven-play-plugin.org.playframework.modules.accesslog/play-accesslog) 
> A Play framework module that performs request logging similar to an access log file in nginx or apache. 
>
> [Project page](https://github.com/briannesbitt/play-accesslog) 

* Templates
  * Faster groovy templates
  * Rythm
  * Markdown
  * 
  
* Persistence
  * Siena 
  * Morphia
  * 
  
* Deployment
  * Google App Engine

* Security
  * Deadbolt
  * 
  
* Performance and auditing
  * Hibernate statistics
  * profiler
  
# Tools

# Resources

- [Mavenized modules](https://code.google.com/p/maven-play-plugin/wiki/MavenizedModules)
- [Using Play's controller](http://www.javabeat.net/using-controllers-in-play-framework/) with a nice roundup about caching, expiration and eTags
- Using Luo's `cache4` [annotation](https://code.google.com/p/maven-play-plugin/wiki/MavenizedModules)
- [How to write modules](http://www.packtpub.com/article/play-framework-introduction-writing-modules)

>  *Note:* don't use - in the folder of your module name. A barely 
>  Your module is found only under the name "play" because Play has a (barely documented) check build in to detect dashes ("-") and ignore everything after the last dash. 
> 
> Since you called your module "play-profiler" (remember it only detects the name by the folder name), it strips the (last and only) dash and everything after it, leaving only "play". 
>
> See the Play source line that does this [here](https://github.com/playframework/play1/blob/1.2.x/framework/src/play/Play.java#L705).
>
>I can't find why this is as it is, but it is known, judging by this bug [ticket with a "wontfix" status]( http://play.lighthouseapp.com/projects/57987/tickets/828-module-names-cant-contain-dash-characters)
