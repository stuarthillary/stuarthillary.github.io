---
title: "The Actor Programming Model"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - actormodel
classes: wide
---

Notes and information on the Actor Programming model

<!--more-->

> The actor model in computer science is a mathematical model of concurrent computation that treats an actor as the basic building block of concurrent computation. In response to a message it receives, an actor can: make local decisions, create more actors, send more messages, and determine how to respond to the next message received. Actors may modify their own private state, but can only affect each other indirectly through messaging (removing the need for lock-based synchronization).
>
> The actor model originated in 1973. It has been used both as a framework for a theoretical understanding of computation and as the theoretical basis for several practical implementations of concurrent systems. The relationship of the model to other work is discussed in actor model and process calculi.
> [Wikipedia](https://en.wikipedia.org/wiki/Actor_model)

Popular Actor frameworks

| Name     | Language |
| -------- | -------- |
| [Akka](https://github.com/akka/akka)     | Java, Scala     |
| [Akka.NET](https://getakka.net/) | C#, F#   |
| [Proto.Actor](https://github.com/asynkron) | Go, C#, Java |
| [Orleans](https://learn.microsoft.com/en-gb/dotnet/orleans/)  | C#, F#   |
