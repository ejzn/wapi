WAPI
====

Wapi a language for the future Web API's.

Why Wapi?
----

Data and services suck. We hear all the buzz words of the day including Speed, high concurrency, non-blocking, functional, cross platform etc etc. What language solves these? Is Java really a middleweare lanaguage designed for high concurrency? What about Scala, or Clojure compiling into the JVM? WAPI is a vision of a non-blocking functional style language that borrows from Erlang without the ugly syntax, Java with the programmers ability in mind and Perl with the data and interopability. Wapi is not designed to be a general purpose language, it is designed to solve a specific problem.

The wen has taken hold, but the next generation of web technologies will need ot have a light weight middle tier that can respond to HTTP/IP/TCP requests fast and at scale. A majority of services will run and we need something that can run quickly from the ground up.

What is Wapi good for?
----

Wapi is geared towards high concurrent web acceissble API's. It aims to provide the programmer with productivity where Erlang fails, and steal the performance elements. Wapis is ideal for non user interface services that exist in a network, for data interchange, messaging or other mechanisms. You should choose Wapi if you want the following:

+ Web API,
+ Data exchange support and transformation ie: JSON-<->XML<->SQL<->HTTP<->SOAP,
+ Easy API Schema Definition - every single method you write in wapi is documented automagically,
+ Messaging and Queuing support, callbacks, and high concurrent non-blocking IO interactions with large distributed systems,
+ Integration with middleware services - Wapi works best when integrated with middleware services,

What is Wapi not good for?
----

Wapi is not good for general purpose programming. It's aim is to provide SPEED and PRODUCTIVITY, not feature completeness for taks that require data interchange, and process execution givin the user instance feedback and validation on data processing.

