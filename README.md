![](https://github.com/google/digitalbuildings/workflows/Tools/badge.svg)
![Ontology Type Validator](https://github.com/google/digitalbuildings/workflows/Ontology%20Type%20Validator/badge.svg)
![Node.js CI](https://github.com/google/digitalbuildings/workflows/Node.js%20CI/badge.svg)
[![GitHub stars](https://img.shields.io/github/stars/google/digitalbuildings.svg)](https://github.com/google/digitalbuildings/stargazers)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# Digital Buildings Project

The Digital Buildings project is an open-source, Apache-licensed effort to create a uniform schema and toolset for representing structured information about buildings and building-installed equipment. A version of the Digital Buildings ontology and toolset is currently being used by Google to manage buildings in its portfolio. 

The Digital Buildings project originated from the need to manage a very large, heterogeneous building portfolio in a scalable way. The project aims to enable management applications/analyses that are trivially portable between buildings.  This goal is achieved through a combination of semantically-expressive abstract modeling, an easy-to-use configuration language, and robust validation tooling.  Digital Buildings work has been inspired by [Project Haystack](https://project-haystack.org/tag) and [BrickSchema](https://brickschema.org/), and maintains cross-compatibility and/or convergence as a long-term objective.

In creating the Digital Buildings project, we have considered the following:

* Human Readability
* Machine readability and interpretation
* Composable functionality
* Dimensional Analysis
* Correctness validation
* Cross compatibility

## Project Structure

This project is structured as following:
*  An [**ontology**](/ontology/README.md) that defines the parameters of the semantic data model and tools for building, validating and associating real equipment with a specific model. It contains the following formats:
   * [Yaml format](/ontology/yaml/README.md)
   * [RDF/OWL format](/ontology/rdf/README.md)
* Tools which allow the following:
  * [Yaml Validator](/tools/validators/ontology_validator/README.md) which allows to validate the yaml ontology upon a change or an extension.
  * [RDF/OWL Generator](/tools/rdf_generator/README.md) which allows to generate an RDF version from the yaml ontology files.
* [Internal Building Representation](/ibr/README.md) (IBR) File Format to represent data from different verticals such as spatial, assets.

## Issues
Please post issues in [Issues](https://github.com/google/digitalbuildings/issues) section.

## Discussion
Open mailing list to discuss Google's Digital Building effort. Discussion could include general questions, standards, APIs, and more. [google-digital-building-discuss@googlegroups.com](mailto:google-digital-building-discuss@googlegroups.com)

Members are expected to adhere to this code of conduct: [https://opensource.google.com/conduct](https://opensource.google.com/conduct)

## How to Contribute

Please see the [contribution section](CONTRIBUTING.md)

## License
```
Copyright 2020 Google LLC

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

## Publications & Talks
* [Québec Bâtiment Vert et Intelligent 2020](https://www.eventbrite.ca/e/billets-rendez-vous-annuel-quebec-bvi-presente-par-google-128034116489)
* [ISWC 2020](http://ceur-ws.org/Vol-2721/paper510.pdf)
* [LDAC 2020](http://linkedbuildingdata.net/ldac2020/abstracts.html#industry10)
* [ICML 2020](http://proceedings.mlr.press/v119/sipple20a/sipple20a.pdf)
* [Semantics 2019](https://2019.semantics.cc/role-semantics-googles-smart-building-platform)
* [Google Cloud Next'19](https://youtu.be/Zz6jkLYkzSQ)


