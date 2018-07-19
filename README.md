# dotmarks.net

This application has been designed using an event based architecture. The application is very simple: it's a bookmark manager.

The idea is to provide an example that can be used to learn and understand the principles behind asynchronous and "Serverless" architectures.

There's a frontend written in html and javascript that consumes a set of APIs, those APIs are deployed independently as __functions__ in a serverless environment as OpenFAAS, Google Functions or AWS lambda.