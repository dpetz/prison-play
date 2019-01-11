# January 2019
 
## Motivation
* Goal: hands on experience of RESTful Microservices
* Go beyond theory of [Building Microservices](http://shop.oreilly.com/product/0636920033158.do)
* Maybe learn some fullstack and reactive skills along the way
* Always wanted to implement some agent based simulation and game theory.
* Revisiting [Think Complexity](http://greenteapress.com/complexity/) 
* First thought [Sugarscape](https://en.wikipedia.org/wiki/Sugarscape)
* But evolutionary Prisoner Dilemma is more interesting and tournament offers nice distributed use case (players as clients)

## Tech Choices

* Scala is fun and good to work in JVM after Data Science work in Python.
* Of the various [Scala REST frameworks][2] picking [Play].
* It's [easy to use][3] and popular incl. [Zalando](https://techradar.zalando.net/frameworks/play_scala.html).
* Akka, functional and event based all good by-catches too
* While working with Sublime, Terminal and sbt in last Scala project worked just fine, use IntelliJ this time for variation.


## Getting Started
* Bootstrapping [new GitHub project][github] from [Play Scala Starter Example][starter]
* Configure ~Run sbt task to benefit from auto-updates that sets Play appart from most Web frameworks
* [Welcome to Play](/Welcome to Play.htm) on http://localhost:9000/ explains the directory structure, routes, [Twirl](https://www.playframework.com/documentation/2.6.21/ScalaTemplates) as the template language used by Play and  [dependency injection](https://www.playframework.com/documentation/2.6.21/ScalaDependencyInjection) via [Guice](https://github.com/google/guice).

Use [this][1] `.gitignore`. Add `.DS_Store`  on Mac.
Remove checked in ignored files via `git rm -r -q --cached .`

Starting this notes. https://daringfireball.net/projects/markdown/syntax has all the Markdown Syntax.


[1]: https://github.com/playframework/playframework/blob/master/.gitignore
[2]: https://nordicapis.com/8-frameworks-to-build-a-web-api-in-scala/
[Play]: https://www.lightbend.com/play-framework
[3]: https://nordicapis.com/building-a-rest-api-in-java-scala-using-play-framework-2-part-1/
[starter]: https://developer.lightbend.com/start/?group=play&project=play-scala-starter-example
[github]: https://github.com/dpetz/prison-play/