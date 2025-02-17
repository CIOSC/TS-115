# Objects of Conformity Assessment

Objects of Conformity Assessment definitions ("object definitions") are adapted from selected techical specifications and standards and agreed to by the technical experts The definition reflects a common understanding and is used to define scope of the process, service or component and to specify the appropriate methods of test used for the purposes of conformity assessment.

## Object Definitions

The objects definitions are intended to be:

* **CONCISE** as agreed on by the technical experts.
* **NORMATIVE** in relation to the conformity assessment scheme, scope, requirements and method of test.
* **NON-NORMATIVE** in relation to other standards, specifications and recommendations.
* **SUBSTANTIVE** to assist in the mapping and scoping of product, process or service components for the purposes of conformity assessment.

*Status* field has the following values:

* **PROPOSED** - proposed by technical experts and contributors.
* **DRAFT** - in active draft by the techical experts with [link to object of conformity assessment specification (template example)](./objca-template.md)
* **PILOT** - approved by the sponsor for pilot as part of a prototype conformity asssessment program (note: material may still be in draft phase)
* **RELEASED** - material is finalized and released as part of a published deliverable.

Where possible, the object definitions are developed to be interpreted as a single process, service or component. If the definition implies  a role, then this will be specified as part of the definition. If an object definition consists of several components (i.e. a composite object), this is further specified in the object template.

[Implemenation Profiles](/scheme/implementation-profiles/implementation-profiles.md) are being mapped to the objects of conformity.

## Minimal Viable Set for Inclusion into Technical Specification

Conformity assessment object definitions being developed by the technical experts for inclusion in technical specification

|Object of Conformity Assessment|Object of Conformity Assessment Definition|Status|
|----|----|----|
|**Digital Credential**|A portable digital record about a subject (e.g., organization, individual, product) that can be held and shared through a user-controlled wallet. It is the digital representation of a traditional physical certificate or information.|[DRAFT](./objca-digital-credential.md)|
|**Issuer Component**|A process, service or component that generates and signs the digital credential|[DRAFT](./objca-issuer.md)|
|**Holder Component**|A process, service or component from which a Presentation can be expressed to a Verifier. A Holder is usually under the control of a User|[DRAFT](./objca-holder.md)|
|**Verifier Component**|A process, service or component that verifies the presentation of a credential to yield an ACCEPT or REJECT decision|[DRAFT](./objca-verifier.md)|
|**Digital Trust Registry**|A system that mediates the creation and verification of identifiers, keys, and other relevant data, such as credential schemas, revocation registries, issuer public keys, and so on, which might be required to use credentials.|[DRAFT](./objca-digital-trust-registry.md)|
|**Decentralized Identifier**|A globally unique persistent identifier that does not require a centralized registration authority and is often generated and/or registered cryptographically.|[DRAFT](./objca-decentralized-identifier.md)|
|**Cryptographic Module**|The set of hardware, software, and/or firmware that implements cryptographic security functions (including cryptographic algorithms and key generation) and is contained within the cryptographic boundary.|[DRAFT](./objca-cryptographic-module.md)|
|**Storage Component**|A foundational layer for secure data storage, including personal data, including data models for storage and transport, syntax, data at rest protection.|[DRAFT](./objca-storage.md)|
|**Credential Format**|The format used to specify identifier of the credential issuer, schema of issued credential, keys used to sign claims within the credential and cryptographic methods used. Revocation methods are optional|[DRAFT](./objca-credential-format.md)|

## Priority List

Conformity assessment object definitions that will be included in subsequent document releases.

|Object of Conformity Assessment|Object of Conformity Assessment Definition|Status|
|----|----|----|
|**Holder Binding**|Holder Binding is the process of associating a Credential issued to a Holder and limiting its control to the associated Holder|PROPOSED|
|**Signature**|An electronic representation where, at a minimum: the entity signing the data can be associated with the electronic representation, it is clear that the entity intended to sign, the reason or purpose for signing is conveyed, and the data integrity of the signed transaction is maintained, including the original. **Alternate definition:** A key represents content secured with a digital   signature or message authentication code |PROPOSED|
|**Digital Trust Service**|A Digital Trust Service is an enabling service that can include one or several of the followiing: digital credentials, verifiable data registries, issuing services, verifying services, and, digital wallet services.|PROPOSED|
|**Decentralized Identifier**|A globally unique persistent identifier that does not require a centralized registration authority and is often generated and/or registered cryptographically.|PROPOSED|
|**Credential Exchange**|Credential Exchange is the set of protocols required to 1. Issue a Credential to a Holder, 2) Present a Proof to a Verifier|PROPOSED|
|**Credential Proof**|A generalized proof (or set of proofs) that can be used to demonstrate one or more of: that the credential is valid, that the information (or derived information) is consistent with the intent for which it was issued, that the credential has not been tampered with, and, that the credential is being presented by the Holder (or authorized delegate) to whom it was issued. The proofs may employ cryptographic, or non-cryptographic means|PROPOSED|
|**Cryptographic Proof**|A Cryptographic Proof is a method by which one party (the prover) can prove to another party (the verifier) that a given statement is true while avoiding conveying additional information apart from the fact that the statement is true.|PROPOSED|

## Under Consideration

Conformity assessment object definitions that are under consideration and may be included in subsquent document releases.

|Object of Conformity Assessment|Object of Conformity Assessment Definition|Status|
|----|----|----|
|**Identifier**|The set of identity attributes used to uniquely distinguish a particular entity within a population.`|PROPOSED|
|**Assigned Identifier**|A numeric or alphanumeric string that is generated automatically and that uniquely distinguishes between Entities within a population without the use of any other identity attributes.|PROPOSED|
|**Verifiable Identifier**|A type of identifier which its control can be independently verified (generally by cryptographic means|PROPOSED|
|**Key**|A key is data structure that represents a key or a secret.|PROPOSED|
|**Presentation**|A Presentation is information derived from one or more Credentials. The source Credentials may have been issued by different Issuers.|PROPOSED|
|**Schema**|A Schema is used to define a set of attributes and data types in order to provide a layer of semantic interoperability with other entities utilising the same schema.|PROPOSED|
|**Credential Data Model**|A credential data model organizes elements of data and standardizes how they relate to one another and to the properties of real-world|PROPOSED|
|**Revocation Method**|A Revocation Method generates the necessary information required to indicate whether a credential has been revoked by the issuer since issuance.|PROPOSED|
|**Facial Comparison**|Facial comparision is the use of a facial recognition algorthim to yield a matching or confidence score (e.g MATCH/NO MATCH, PERCENT SIMILARITY)|PROPOSED|
|**Trust Registry**|A Trust Registry answers queries about whether an entity or object is trusted or is authorized to perform an action within a given context.|PROPOSED|
|**Messaging Protocol**|A Messaging Protocol supports identifier-based relationships, credential exchanges, and specialized application workflows in a manner that ensures privacy and security.|PROPOSED|
|**Selective Disclosure**|The ability of a user to make nuanced decisions about what information to share.|PROPOSED|
|**Predicate**| The ability of a user to check a value against a certain condition, disclosing only true or false without revealing the value.|PROPOSED|
|**Rich Schema**|Hierarchically composable graph-based representations of complex data.|PROPOSED|

## Common Requirements for Objects of Conformity

The following requirements apply to all objects of conformity under assessment:

### Conformance

1. Conforming implementations shall pass respective normative specification-based techniques and requirements of this Specification. Test results including the test plan for executing specification-based techniques shall be reviewed before taking a final decision as to whether the object of conformity has been reliably demonstrated. A standardized expression shall be used for means of communicating the fulfilment of conformity assessment requirements. NOTE: A statement of conformity may include non-fulfilment of specified requirements.

### Methods of Test

1. The following two specification-based testing techniques shall be used in accordance with ISO/IEC/IEEE 29119-4 to derive test cases that, when executed, generate evidence that test item requirements have been met or not: a) scenario testing, b) Requirements-based testing. NOTE: Additional specification-based test design techniques, structure-based test design techniques, and experience-based test design techniques may be used in accordance with ISO/IEC/IEEE 29119-4 where appropriate to provide added evidence and confidence that requirements in this Technical Specification are met.
2. Test results shall demonstrate conformance to the relevant specification or open standard specified  and remain in accordance with the conformity assessment requirements.
3. Data model, data interchange and file formats used shall be published by a recognized body.

### Scenario Testing

1. A test plan for executing the test scenarios using the data model and data interchange and file formats specified shall be sufficiently detailed with specific inputs, outputs, execution conditions, testing procedures and expected results.
2. Test scenarios shall be executed on the service in scope. Each test scenario shall illustrate how the object of conformity behaves in context. Test scenarios shall include one or several of the following dependent on the scope of the service.
3. The result of the test scenarios should be documented in a test report.
4. All test scenarios executed shall result and/or preserve the general characteristics of the object of conformity.

### Requirements-based Testing

1. The criteria specified shall comprise the test model and a test case derived to cover each atomic requirements with at least one test case and executed in accordance with ISO/IEC/IEEE 29119-4.

## Recognized Bodies

Recognized bodies are any organizations that develop standards, specifications or recommendations and which have established governance and  processes that ensure fair development and ongoing maintenance of published materials. Standards, specificatios and recommendations used in conjunction for conformity assessment SHALL be published by a recognized body.

Recognized bodies (under review)

|Acronym/Short Name|Official Name|Website|
|---|---|---|
|DIF|Decentralized Identity Foundation| <https://identity.foundation>|
|FIDO|FIDO Alliance|<https://fidoalliance.org/>|
Hyperledger|Hyperledger Foundation, Aries|<https://www.hyperledger.org/use/aries>|
|IETF|Internet Engineering Task Force|<https://www.ietf.org/>|
|NIST|National Institute for Standards and Technology|<https://www.nist.gov/>|
|ISO|International Organization for Standardization|<https://www.iso.org/home.html>|
|ICAO|International Civil Aviation Organization|<https://www.icao.int/Pages/default.aspx>|
|ToIP|Trust Over IP Foundation|<https://trustoverip.org/>|
|W3C|Worldwide Web Consortium|<https://www.w3.org>|

## ISO Conventions for Requirements

Recommended terminology for conformity assessment requirements:

* **Requirements** - SHALL, SHALL NOT
* **Recommendations** - SHOULD, SHOULD NOT
* **Permission** - MAY, MAY NOT
* **Possibility and Capability** - CAN, CANNOT

## Technology Readiness Levels

Technology Readiness Levels (TRL) describe the different stages of pre-commercial development.

All objects of conformity SHOULD be assessed at TRL 7 or greater

|TRL|Short Definition|Description|Example of Activities|
|----|----|----|----|
|1|Basic principles observed and reported.|Lowest level of technology readiness. Scientific research begins to be translated into applied research and development (R&D).|Activities might include paper studies of a technology's basic properties.|
|2|Technology concept and/or application formulated.|Invention begins. Once basic principles are observed, practical applications can be invented. Applications are speculative, and there may be no proof or detailed analysis to support the assumptions.|Activities are limited to analytic studies.|
|3|Analytical and experimental critical function and/or characteristic proof of concept.|Active R&D is initiated. This includes analytical studies and laboratory studies to physically validate the analytical predictions of separate elements of the technology.|Activities include components that are not yet integrated or representative.|
|4|Component(s)/subsystem(s) and/or process validation in a laboratory environment.|Basic technological components are integrated to establish that they will work together.|Activities include integration of "ad hoc" hardware in the laboratory.|
|5|Semi-integrated component(s)/subsystem(s) and/or process validation in a simulated environment.|The basic technological components are integrated for testing in a simulated environment.|Activities include laboratory integration of components.|
|6|System and/or process prototype demonstration in a simulated environment.|A model or prototype that represents a near desired configuration.|Activities include testing a model or prototype in a simulated or laboratory environment.|
|7|Prototype system ready (form, fit, and function) for demonstration in an appropriate operational environment.|Prototype is ready for demonstration in an operational environment and is at planned operational level.|Activities include prototype field testing in a real-world operational setting.|
|8|Actual technology completed and qualified through tests and demonstrations.|Technology has been proven to work in its final form and under expected conditions.|Activities include developmental testing and evaluation of whether it will meet operational requirements.|
|9|Actual technology proven through successful deployment in an operational setting.|Actual application of the technology in its final form and under real-life conditions, such as those encountered in operational tests and evaluations.|Activities include using the innovation under operational conditions.|

[Source: ISC Technology Readiness Scale](https://ised-isde.canada.ca/site/innovative-solutions-canada/en/isc-technology-readiness-level-scale)
