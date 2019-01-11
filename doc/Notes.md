Goal is gathering hands on experience via RESTful Microservices.
Agent based simulations as a fun topic.
Wanted to implement [Think Complexity](https://learning.oreilly.com/library/view/think-complexity-2nd/9781492040194/ch09.html%23a0000004383%20) for some time.
First thought [Sugarscape](https://en.wikipedia.org/wiki/Sugarscape).
But evolutionary Prisoner Dilemma is more interesting and tournament offers nice distributed use case (players as clients)


Of  the [many Scala REST frameworks](https://nordicapis.com/8-frameworks-to-build-a-web-api-in-scala/) pick [Play Framework](https://www.lightbend.com/play-framework). It is popular, [easy to use](https://nordicapis.com/building-a-rest-api-in-java-scala-using-play-framework-2-part-1/), based on Akka, promotes functional and asynchronous programming and has good [Zalando adoption](https://techradar.zalando.net/frameworks/play_scala.html).

Started [new GitHub project](https://github.com/dpetz/prison-play/) based on the [Play Scala Starter Example](https://developer.lightbend.com/start/?group=play&project=play-scala-starter-example).

~Run sbt to generate [Welcome to Play](/Welcome to Play.htm) on http://localhost:9000/.
It explains the directory structure, routes [Twirl](https://www.playframework.com/documentation/2.6.21/ScalaTemplates) as the template language used by Play and  [dependency injection](https://www.playframework.com/documentation/2.6.21/ScalaDependencyInjection) via [Guice](https://github.com/google/guice).