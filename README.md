# RDFJS Library README template

_**Placeholder:** Library-related badges go here_

This document is a README template for RDFJS-related projects.
It is a minimal template that lists all recommended elements and sections,
with some example placeholder contents.

The structure of this README can be changed to meet the needs of the library.
The following elements SHOULD be present (optionally behind links to other documents):

* General description: High-level description of tool and available features.
* Installation: How to install and import into project.
* Usage: Describing the main features with code examples.
* Configuration: The available config options for this tool, e.g. constructor params.
* Specification Compliance: mention the compliance with respect to any (W3C) specification, including RDFJS interfaces.
* License: The license under which the library is available.

_**Placeholder:** A high-level description of this library_


## Installation

This tool can be installed via either npm or yarn:

```bash
$ npm install my-library
```

or

```bash
$ yarn add my-library
```

This tool can be imported into your project as follows:

```javascript
import {MyTool} from "my-library";
```

_or_

```javascript
const MyTool = require("my-library").MyTool;
```

## Usage

_**Placeholder:** A high-level description on the usage and available functionality_

### Main Feature 1

_**Placeholder:** Description of a feature_

```javascript
// Some example code
```

## Configuration

_**Placeholder:** The available config options for this library, e.g. constructor params_

Optionally, the following parameters can be set in the `MyTool` constructor:

* `dataFactory`: A custom [RDFJS DataFactory](http://rdf.js.org/#datafactory-interface) to construct terms and triples. _(Default: `require('@rdfjs/data-model')`)_
* `baseIRI`: An initial default base IRI. _(Default: `''`)_

```javascript
new MyTool({
  dataFactory: require('@rdfjs/data-model'),
  baseIRI: 'http://example.org/',
});
```

## Specification Compliance

_**Placeholder:** If applicable, mention the compliance with respect to any (W3C) specification, including RDFJS interfaces_

## License

This software is written by Someone.

This code is released under the [MIT license](http://opensource.org/licenses/MIT).
