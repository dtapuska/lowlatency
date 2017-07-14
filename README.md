# lowlatency
A specification describing the lowlatency AddEventListenerOption extension.
## Abstract
Input events such as pointerevents, mouseevents and touchevents may be dispatched at an appropriate time to reduce the amount of unncessary work. Reducing the amount of work comes at a cost of increasing latency sometimes. This increase in latency may not be a desirable side effect for some applications. Adding the ability for an application to indicate that they require lowlatency input is desired.
## Contribute

This spec is built using [Bikeshed](https://github.com/tabatkins/bikeshed).

Update `index.bs` with your changes, run `bikeshed` in the working directory to generate `index.html`, and then send a pull request describing your changes.
