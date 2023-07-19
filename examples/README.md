# Examples

This folder contains an example of use of the OntoUML Vocabulary for the serialization of a model.

We created an OntoUML model at the [Visual Paradigm](https://www.visual-paradigm.com/download/community.jsp) using the [ontouml-vp-plugin](https://github.com/OntoUML/ontouml-vp-plugin/) and exported it to a JSON format. This JSON format contains the created model serialized according to the [OntoUML Schema](https://w3id.org/ontouml/schema).

Both the OntoUML Schema and Vocabulary comply with the [OntoUML Metamodel](https://w3id.org/ontouml/metamodel), allowing their mapping and the formats transformation.

The JSON file was converted to TTL using the [ontouml-json2ttl](https://w3id.org/ontouml/json2graph) decoder. This tool generates graph files that comply with the OntoUML Vocabulary and includes an optional basic verification and correction.

This example is composed of the following files:
- `MyExample.vpp`: OntoUML model editable file.
- `MyClassDiagram.png`: Exported image of the created OntoUML model.
- `MyExample.json`: OntoUML model exported as JSON.
- `MyExample.ttl`: OntoUML model exported as Graph in Turtle syntax (`.ttl`).

## Individual Objects

The transformation of specific types of JSON objects are presented in individual `.ttl` files located into the `objects` folder.