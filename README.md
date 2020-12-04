# modelDCAT-AP

## Class: dcat:Catalog (MODEL CATALOG)
Properties:
* `dct:publisher`  (Object Property) Range: foaf:Agent
* `dcat:dataset`  (Object Property) Range: dcat:Dataset
* `dct:harPart`  (Object Property) Range: dcat:Catalog


## Class: dcat:Dataset (MODEL)
Properties:
* `dct:type`  (Object Property) Range: skos:Concept
* `mdl:modelScope`  (Object Property) Range: mscope:ModelScope
* `mreg:modellingRegime`  (Object Property) Range: mreg:ModellingRegime
* `vann:preferredNamespaceUri` (Datatype property) Range: xsd:anyURI. 
* `vann:preferredNamespacePrefix` (Datatype property) Range: rdfs:Literal.
* `dct:title` (Datatype property) Range: rdfs:Literal. 
* `skos:altLabel` (Datatype property) Range: rdfs:Literal. 
* `dct:identifier` (Datatype property) Range: rdfs:Literal. 
* `dcat:keyword` (Datatype property) Range: rdfs:Literal. 
* `dct:description` (Datatype property) Range: rdfs:Literal. 
* `frbr:responsibleEntity`  (Object Property) Range: rdfs:Literal.
* `dct:publisher`  (Object Property) Range: rdfs:Literal.
* `dcat:contactPoint`  (Object Property) Range: vcard:Kind
* `dct:issued` (Datatype property) Range: rdfs:Literal. 
* `dct:modified` (Datatype property) Range: rdfs:Literal. 
* `owl:versionInfo` (Datatype property) Range: rdfs:Literal. 
* `adms:versionNotes` (Datatype property) Range: rdfs:Literal. 
* `dct:hasVersion`  (Object Property) Range: dcat:Dataset
* `dct:isVersionOf`  (Object Property) Range: dcat:Dataset
* `status:status` (Object Property) Range: skos:Concept.
* `voag:hasApprovalStatus`  (Object Property) Range: skos:Concept.
* `voag:approvedBy` (Object Property) Range: rdfs:Literal. 
* `dct:hasVersion`  (Object Property) Range: dcat:Dataset
* `dcat:theme`  (Object Property) Range: skos:Concept
* `foaf:page`  (Object Property) Range: foaf:Document
* `dct:rights`  (Object Property) Range: dct:RightsStatement
* `dcat:landingPage`  (Object Property) Range: foaf:Document
* `dcat:distribution`  (Object Property) Range: dcat:Distribution

 ## Class: dcat:Distribution (Model Distribution)
Properties:
* `dcat:accessURL` (Datatype property) Range: rdfs:Literal. 
* `dcat:downloadURL` (Datatype property) Range: rdfs:Literal. 
* `dct:title` (Datatype property) Range: rdfs:Literal. 
* `dct:format`  (Object Property) Range: dct:MediaTypeOrExtent
* `adms:representationTechnique`  (Object Property) Range: skos:Concept
* `dct:license`  (Object Property) Range: dct:LicenseDocument

