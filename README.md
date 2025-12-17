# FHIR Testing IG

This documents the HL7 FHIR testing framework.

## FHIR Testing Project Statement

* Maintainers: Grahame Grieve (as FHIR Product Director) + FHIR-I WG
* Issues / Discussion: Create Issues here on GitHub. Discussion about (potential) issues, see [Zulip](https://chat.fhir.org/#narrow/channel/231245-testing). 
* License: [HL7 FHIR - CCO](http://hl7.org/fhir/license.html)
* Contribution Policy: Contributions to this IG are made under [the HL7 GOM](https://www.hl7.org/permalink/?GOM). This IG uses the standard HL7 ci-build for IGs, checking the generated QA. 
* Security Information: [see below](#security)
* Compliance Information: This content is used by/integrated with the base FHIR tools and is used across all versions of FHIR (R2-R5)

## Purpose

The FHIR specification describes a set of <a href="https://hl7.org/fhir/resource.html">resources</a>,
and several different frameworks for exchanging resources between different systems.
Because of its general nature and wide applicability, the rules made in the FHIR
specification are fairly loose. As a consequence, and in order to insure
interoperability between applications claiming conformance to the FHIR specification, this
testing framework has been established.

## Security

As an implementation guide that includes no active content, there's no direct security related content. 

For issues with the scripts that launch the publisher, see https://raw.githubusercontent.com/HL7/ig-publisher-scripts

If you think that there's security issues in the testing framework as documented here, you can report them here 
using GitHub's [standard security reporting framework](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability#privately-reporting-a-security-vulnerability), or you can email the [FHIR Director](mailto:fhir-director@hl7.org) directly.

If you think that there's a security issue with one of the servers that is part of the framework, report it directly to the server.
