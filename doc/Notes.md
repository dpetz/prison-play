# January 2019
 
## Motivation

* Goal: hands on experience of RESTful Microservices
* [Building Microservices] was good theory. Now get real.
* Practice some fullstack codibility along the way
* Agent based simulation and game theory as domain are fun
* Remembered [Sugarscape] from [Think Complexity]
* Evolutionary Prisoner Dilemma from next chapter even more interesting
* Tournament may be a nice distributed use case with players as clients

## Tech Choices

* Want to practice my Scala + good to work in JVM after Data Science in Python.
* Of the various [Scala REST frameworks], [Play] is [easy to use][1] and most popular
  [incl. Zalando](https://techradar.zalando.net/frameworks/play_scala.html)
* Reactive + functional programming and learning Akka are good by-catches
* IntelliJ as IDE to diversify from Sublime + Terminal sbt of [my previous project](https://github.com/dpetz/parser)
* For DB access [comparing Slick and Anorm](https://codewithstyle.info/slick-vs-anorm-choosing-db-framework-scala-application/)
  Like Slick's functional and non-blocking design more.
* Looking at [Play Scala concepts]
** 

## Getting Started

* Bootstrapping [prison-play] GitHub project from the [Play Scala Starter Example]
* Configure `~Run` sbt task to benefit from Play auto-updates that sets Play apart from most Web frameworks
* [Welcome to Play.html](./Welcome to Play.htm) served to <http://localhost:9000> introduces `conf/routes`,
Play's template language [Twirl] and it's [dependency injection] via [Guice].
* Use [this][2] `.gitignore`. Add `.DS_Store`  on Mac. Reset repo via `git rm -r -q --cached .`
* Migrating this notes from Evernote to [Markdown].

[Building Microservices]: http://shop.oreilly.com/product/0636920033158.do
[Play]: https://www.lightbend.com/play-framework
[Play Scala Starter Example]: https://developer.lightbend.com/start/?group=play&project=play-scala-starter-example
[prison-play]: https://github.com/dpetz/prison-play/
[Scala REST frameworks]: https://nordicapis.com/8-frameworks-to-build-a-web-api-in-scala/
[Twirl]: https://www.playframework.com/documentation/2.6.21/ScalaTemplates
[dependency injection]: https://www.playframework.com/documentation/2.6.21/ScalaDependencyInjection
[Guice]: https://github.com/google/guice
[Markdown]: https://daringfireball.net/projects/markdown/syntax
[Sugarscape]: https://en.wikipedia.org/wiki/Sugarscape
[Think Complexity]: http://greenteapress.com/complexity/
 [Play Scala concepts]: https://www.playframework.com/documentation/2.6.21/ScalaHome

[1]: https://nordicapis.com/building-a-rest-api-in-java-scala-using-play-framework-2-part-1/
[2]: https://github.com/playframework/playframework/blob/master/.gitignore
