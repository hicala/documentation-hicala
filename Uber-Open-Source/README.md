[Back to documentation-hicala]( https://github.com/hicala/documentation-hicala)

![Uber Open Sourse](https://github.com/hicala/documentation-hicala/blob/main/images/Uber-Open-Sourse.jpg)

# Uber Open Sourse

1. https://github.com/hicala/m3

   M3 monorepo - Distributed TSDB, Aggregator and Query Engine, Prometheus Sidecar, Graphite Compatible, Metrics Platform 

   ### Overview

   M3 is the obvious choice for Cloud Native companies looking to scale up their Prometheus based monitoring systems. M3 can be used as Prometheus Remote Storage and has 100% PromQL compatibility.

   M3 was originally developed at Uber in order to provide visibility into Uber’s business operations, microservices and infrastructure. With its ability to horizontally scale with ease, M3 provides a single centralized storage solution for all monitoring use cases.

1. https://github.com/hicala/jaeger-operator

   Jaeger Operator for Kubernetes simplifies deploying and running Jaeger on Kubernetes. 

   ### Overview

   The Jaeger Operator is an implementation of a Kubernetes Operator.

1. https://github.com/hicala/baseweb

   A React Component library implementing the Base design language 

   ### Overview

   Base Web provides a robust suite of components out of the box. These include complex, ready to use components such as the Datepicker and low-level composable primitives, such as Layer.

For an overview of everything that we offer, check out the component gallery.

1. https://github.com/hicala/documentation

   Documentation/website for the Jaeger Distributed Tracing project. 

   ### Overview

   This repo houses all the assets used to build the Jaeger website, available at https://jaegertracing.io.

The site is built with Hugo and hosted by Netlify.

1. https://github.com/hicala/ludwig

   Ludwig is a toolbox that allows to train and evaluate deep learning models without the need to write code. 

   ### Overview

   Ludwig is a toolbox that allows users to train and test deep learning models without the need to write code. It is built on top of TensorFlow.

To train a model you need to provide is a file containing your data, a list of columns to use as inputs, and a list of columns to use as outputs, Ludwig will do the rest. Simple commands can be used to train models both locally and in a distributed way, and to use them to predict new data.

A programmatic API is also available to use Ludwig from Python. A suite of visualization tools allows you to analyze models' training and test performance and to compare them.

Ludwig is built with extensibility principles in mind and is based on datatype abstractions, making it easy to add support for new datatypes as well as new model architectures.

1. https://github.com/hicala/pyro

   Deep universal probabilistic programming with Python and PyTorch 

   ### Overview

   Pyro is a flexible, scalable deep probabilistic programming library built on PyTorch. Notably, it was designed with these principles in mind:

    Universal: Pyro is a universal PPL - it can represent any computable probability distribution.
    Scalable: Pyro scales to large data sets with little overhead compared to hand-written code.
    Minimal: Pyro is agile and maintainable. It is implemented with a small core of powerful, composable abstractions.
    Flexible: Pyro aims for automation when you want it, control when you need it. This is accomplished through high-level abstractions to express generative and inference models, while allowing experts easy-access to customize inference.

Pyro was originally developed at Uber AI and is now actively maintained by community contributors, including a dedicated team at the Broad Institute. In 2019, Pyro became a project of the Linux Foundation, a neutral space for collaboration on open source software, open standards, open data, and open hardware.

For more information about the high level motivation for Pyro, check out our launch blog post. For additional blog posts, check out work on experimental design and time-to-event modeling in Pyro.

1. https://github.com/hicala/react-digraph

   A library for creating directed graph editors 

   ### Overview

   A React component which makes it easy to create a directed graph editor without implementing any of the SVG drawing or event handling logic.

1. https://github.com/hicala/jaeger-ui

   Web UI for Jaeger    

   ### Overview

   Visualize distributed tracing with Jaeger.

1. https://github.com/hicala/jaeger-client-java

   Jaeger Bindings for Java OpenTracing API 

   ### Overview

   Jaeger's Tracing Instrumentation Library for Java

    Intended to be used with Jaeger backend, but can also be configured to send traces to Zipkin.
    Implements OpenTracing Java API.
    Supports Java 1.6 and above

1. https://github.com/hicala/jaeger-client-csharp

   C# client (tracer) for Jaeger 

   ### Overview

   As on-the-ground microservice practitioners are quickly realizing, the majority of operational problems that arise when moving to a distributed architecture are ultimately grounded in two areas: networking and observability. It is simply an orders of magnitude larger problem to network and debug a set of intertwined distributed services versus a single monolithic application.

1. https://github.com/hicala/jaeger-analytics-java

   Data analytics pipeline and models for tracing data   

   ### Overview

   Experimental repository with data analytics models, pipelines for Jaeger tracing data.

Repository contains:

    Graph trace DSL based on Apache Gremlin. It helps to write graph "queries" against a trace
    Spark streaming integration with Kafka for Jaeger topics
    Loading trace from Jaeger query service
    Jupyter notebooks to run examples with data analytic models
    Data analytics models, metrics based on tracing data
    Grafana dashboards

1. https://github.com/hicala/jaeger-client-python

   Jaeger Bindings for Python OpenTracing API 

   ### Overview

   This is a client-side library that can be used to instrument Python apps for distributed trace collection, and to send those traces to Jaeger. See the OpenTracing Python API for additional detail.

1. https://github.com/hicala/jaeger-client-go

   Jaeger Bindings for Go OpenTracing API. 

   ### Overview

   Jaeger Bindings for Go OpenTracing API

Instrumentation library that implements an OpenTracing Go Tracer for Jaeger (https://jaegertracing.io).

1. https://github.com/hicala/jaeger-performance

   Home of the Jaeger Performance tests 

   ### Overview

   This project is designed to do basic smoke and performance testing of JaegerTracing. The primary target for these tests is OpenShift, where they can be run using the Jenkinsfile in this directory.

1. https://github.com/hicala/spark-dependencies

   Spark job for dependency links 

   ### Overview

   This is a Spark job that collects spans from storage, analyze links between services, and stores them for later presentation in the UI. Note that it is needed for the production deployment. all-in-one distribution does not need this job.

This job parses all traces on a given day, based on UTC. By default, it processes the current day, but other days can be explicitly specified.

This repository is based on zipkin-dependencies.

1. https://github.com/hicala/jaeger-client-cpp

   C++ OpenTracing binding for Jaeger 

   ### Overview

   Jaeger SDK with OpenTracing API for C++ binding.

1. https://github.com/hicala/fiber

   Distributed Computing for AI Made Simple 

   ### Overview

   Distributed Computing for AI Made Simple

This project is experimental and the APIs are not considered stable.

Fiber is a Python distributed computing library for modern computer clusters.

    It is easy to use. Fiber allows you to write programs that run on a computer cluster level without the need to dive into the details of computer cluster.
    It is easy to learn. Fiber provides the same API as Python's standard multiprocessing library that you are familiar with. If you know how to use multiprocessing, you can program a computer cluster with Fiber.
    It is fast. Fiber's communication backbone is built on top of Nanomsg which is a high-performance asynchronous messaging library to allow fast and reliable communication.
    It doesn't need deployment. You run it as the same way as running a normal application on a computer cluster and Fiber handles the rest for you.
    It it reliable. Fiber has built-in error handling when you are running a pool of workers. Users can focus on writing the actual application code instead of dealing with crashed workers.

Originally, it was developed to power large scale parallel scientific computation projects like POET and it has been used to power similar projects within Uber.

1. https://github.com/hicala/jaeger-lib

   A collection of shared infrastructure libraries used by different components of Jaeger. 

   ### Overview

   A collection of shared infrastructure libraries used by different components of Jaeger backend and jaeger-client-go. This library is not intended to be used standalone, and provides no guarantees of backwards compatibility.

1. https://github.com/hicala/aresdb

   A GPU-powered real-time analytics storage and query engine. 

   ### Overview

   AresDB is a GPU-powered real-time analytics storage and query engine. It features low query latency, high data freshness and highly efficient in-memory and on disk storage management. Please see AresDB's features, architecture design described in the Uber Engineering Blog.

This repo contains the source code of AresDB and debug UI.

1. https://github.com/hicala/docker-protobuf

   An all-inclusive protoc Docker image for the Jaeger project 

   ### Overview

   A lightweight protoc Docker image, published as jaegertracing/protobuf to Docker Hub, with all dependencies built-in, to generate code in multiple languages. Forked from https://github.com/TheThingsIndustries/docker-protobuf.

1. https://github.com/hicala/vertx-create-span

   Demo application used in e2e tests for the Jaeger Operator 

   ### Overview

   This is a Vert.x starter project (from http://start.vertx.io/), with just enough code to include Jaeger tracer and report a span.

1. https://github.com/hicala/jaeger-client-node

   Jaeger Bindings for OpenTracing API for Node.js 

   ### Overview

   This is Jaeger's client side instrumentation library for Node.js that implements Javascript OpenTracing API 1.0.

Note that this library is not designed to run in the browser, only in the Node.js-backend servers. For browser-only version, see https://github.com/jaegertracing/jaeger-client-javascript.

1. https://github.com/hicala/jaeger-idl

   A set of shared data model definitions used by Jaeger components. 

   ### Overview

   This repository does not publish the generated code, but it does run Thrift and protoc generators as part of the CI to verify all IDL files. See the Makefile for example. In particular, the classes for different languages can be compiled using the jaegertracing/protobuf Docker image (see README).

1. https://github.com/hicala/jaeger-kubernetes

   Support for deploying Jaeger into Kubernetes 

   ### Overview

   The recommended way of installing and managing Jaeger in a production Kubernetes cluster is via the Jaeger Operator.

The Jaeger Operator provides a CLI to generate Kubernetes manifests from the Jaeger CR. This can be considered as an alternative source of plain Kubernetes manifest files.

Jaeger ecosystem also provides a Helm chart as an alternative way of deploying Jaeger.

1. https://github.com/hicala/jaeger-opentelemetry-collector

   Jaeger OpenTelemetry Collector is now in the main Jaeger repository 

   ### Overview

   This repository is deprecated! All code has been migrated to the main Jaeger repository.

1. https://github.com/hicala/jaeger-analytics-flink

   Big data analytics for Jaeger using Apache Flink 

   ### Overview

   This repository was created from the internal Uber repository used to run Flink jobs. It was created by stripping away Uber specific components, and hasn't been tested in it's current form. It is intended to serve as a starting point for a more generic OSS release.
