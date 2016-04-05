# Data-Driven Declarative Documents

**D4.js** is a JavaScript library for declaratively displaying data. It replicates a small subset of [D3.js](https://d3js.org)'s functionality.

## Why?

This is an experiment in replacing the mutative style of d3 with a more declarative style. We use React to handle rendering, which makes most of the complexity go away.

### What's here

* Selections (-ish)
* Transitions
* Shape generation
* Axes
* Layouts

### What's not

* Scales
* (Most) Array operations (get these from elsewhere)
* Math (get from D3)
* Loading external resources (get from D3)
* String formatting
* CSV formatting
* Localization
* Colors
* Namespaces
* Binding / dispatch helpers
* Controls (eventually)
* Time
* Geography
* Geometry
* Behaviors
