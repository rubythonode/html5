# HTML library for Dart / DDC (polymerize)

This library is an HTML library generated by [html_wrapper_generator](https://github.com/polymer-dart/html_wrapper_generator)
starting from webidl files (stolen from the `firefox` project and then adapted).

It leverages the `@JS` interop Dart layer and aims to completely replace the (at the moment) out dated `dart:html` library.

As a separate package from the `SDK` this library has the main advantage to be updated more frequently.

Notably this library adds support to latest standards:

 - WebComponents v1
 - ShadowDom

## Demo project

See [here](https://github.com/polymer-dart/html5_demo) for a demo project using `polymerize` and this library.
