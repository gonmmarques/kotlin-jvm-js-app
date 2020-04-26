## Building a Full Stack Web App with Kotlin Multiplatform

This a very basic Shopping List app to demonstrate the usage of Kotlin  Multiplatform as a great solution for full stack apps.
It is built using Kotlin/JVM, for the backend, and Kotlin/JS, for the frontend.

## App overview
Basic app with
* REST API that allows creation, reading and deleting of shopping items running on a Netty embedded server;
* Client UI that list all items; allows to add items (higher priority to items can by set using (!)); and it allows to delete items by clicking on an item;
* Persistance is achieved by using a MongoDB;
* Ready to be deployed to Heroku;


## Frameworks & Libraries
* [kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization)
* [kotlinx.coroutines](https://github.com/Kotlin/kotlinx.coroutines)
* [Ktor - asynchronous Web framework for Kotlin](https://ktor.io/)
* [kotlin-react](https://github.com/JetBrains/kotlin-wrappers/blob/master/kotlin-react/README.md)
* [KMongo - a Kotlin toolkit for Mongo](https://litote.org/kmongo/)
* [Gradle](https://gradle.org/)


## Goal & Conclusions

The app is very basic and is mostly a copy of following the Kotlin tutorial. 

My goal on doing this tutorial was was to just learn a little bit more about how to configure a full stack app and what are the main steps to do so.

The main conclusion that I take is that it's fairly simple to configure the app and makes it very fast to build a full stack app without much hassle.

## Reference

[Building a Full Stack Web App with Kotlin Multiplatform](https://play.kotlinlang.org/hands-on/Full%20Stack%20Web%20App%20with%20Kotlin%20Multiplatform/01_Introduction)