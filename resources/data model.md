# Data Model

The OntoUML Vocabulary's data model was structured to be in conformance with the [OntoUML Metamodel](https://w3id.org/ontouml/metamodel).

It is important to emphasize that the OntoUML Metamodel is implementation-independent. When building the Vocabulary, an OWL artifact, the building language's constraints will restrict the generated artifact. In this sense, design decisions had to be made in order to generate the OntoUML Vocabulary. The adopted design decisions are registered as comments in the vocabulary's related concepts.

Being grounded on an explicit implementation-independent metamodel benefits OntoUML Vocabulary, in the sense that a mapping between these two artifacts is already stablished, facilitating future integration and data exchange to other implementations based on the OntoUML Metamodel.

## Metamodel's Abstract Syntax

All OntoUML modeling elements are represented in the Metamodel's abstract syntax, which can be visualized in the following diagram.

<p align="center"><img src="https://raw.githubusercontent.com/OntoUML/ontouml-metamodel/main/diagrams/Abstract%20Syntax.png">

The modeling elements are the ones that carry information about the domain being represented, not about the visual representation itself.

## Metamodel's Concrete Syntax

The Metamodel's concrete syntax contains all diagramatic elements that are part of an OntoUML model. These elements are displayed in the diagram below.

<p align="center"><img src="https://raw.githubusercontent.com/OntoUML/ontouml-metamodel/main/diagrams/Concrete%20Syntax.png">

The diagramatical representation are the views and shapes that forms the visual representation of the modeling elements. Every modeling element that can be visualized in a diagram has its corresponding view and shape.
