# Velocity 2017 - Application Tracing

Bryan Liles

[bryanliles@gmail.com](mailto:bryanliles@gmail.com)

**Workshop Chat: [https://gitter.im/Velocity-SJ-OpenTracing/Lobby](https://gitter.im/Velocity-SJ-OpenTracing/Lobby)**

## Introduction

This workshop is for intermediate level (and beyond) developers looking to learn more about instrumenting their applications.

### Prerequisites

Developers are expected to:

* Be comfortable with a code editor
* Have general knowledge of Git
* Have general knowledge of Docker
* Have general knowledge in developing applications in Go or Python

## Getting started

Make sure to log in to the [workshop tracing chat](https://gitter.im/Velocity-SJ-OpenTracing/Lobby) to ask questions and get answers.

* Using Go? https://github.com/bryanl/apptracing-go
* Using Python? https://github.com/bryanl/apptracing-py

## Program

### Introduction

Learn about the whys, whats, and hows of OpenTracing.

#### Jaeger HotRod Demo

```
go get github.com/uber/jaeger
cd $GOPATH/src/github.com/uber/jaeger
make install_examples
cd examples/hotrod
go run ./main.go all
```

### Hands on: Tracing Concepts

Learn how to start with OpenTracing in your applications

* Exercise: Tracing functions
* Exercise: Tracing HTTP

### Hands on: More Tracing Concepts

Expand on the knowledge learned in the first section to configure and implement OpenTracing in a database-backed application.

* Exercise: People Catalog
* Instrumenting everything

### Discussion / Lessons Learned

Discussion of tracing topics, items learned today, and a question and answer section.

### Closing





