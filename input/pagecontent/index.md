
### Introduction

This IG documents the testing support that HL7 provides for 
testing FHIR implementations. In includes the formal definition
of several [R6 Additional Resources](https://build.fhir.org/resource.html#additional): TestScript, TestReport, and TestPlan.

#### In this IG

* The R6 [TestScript resource](StructureDefinition-TestScript.html), and [discussion about its use](testing.html)
* The R6 [TestReport resource](StructureDefinition-TestReport.html)
* The R6 [TestPlan resource](StructureDefinition-TestPlan.html)
* A simple approach to using [profiles for scoring](index.html). See [PIQI](https://build.fhir.org/ig/HL7/piqiimplementation/) for a more complex approach

Todo: what parts of [the IG Publisher Documentation](https://build.fhir.org/ig/FHIR/ig-guidance/testing.html) move here? 

#### Tools that support testing

Note that the following tools implement parts of the 
testing framework defined in this specification:

<table class="grid">
 <tr>
  <th>Tool</th>
  <th>License</th>
  <th>Implements</th>
 </tr>
 <!-- open source implementations come first -->
 <tr>
  <td><a href="https://github.com/hapifhir/org.hl7.fhir.core/releases">FHIR&nbsp;Validator</a></td>
  <td>Open Source (Apache 2)</td>
  <td>
    Static Validation of FHIR Resources; supports the scoring approach documented in this IG,
    and used by other testing tools in this list. Implements several runners for TestPlan resources:
    <ul>
     <li><a href="https://build.fhir.org/ig/HL7/fhir-tx-ecosystem-ig/runner.html">Terminology Tester</a></li>
    </ul>
  </td>
 </tr>

 <!-- Now, commercial implementations. Order is at the discretion of the FHIR Product Director -->
 <tr>
  <td><a href="https://touchstone.aegis.net">AEGIS Touchstone</a></td>
  <td>Commercial</td>
  <td>
    Nearly complete implementation of TestScript.
  </td>
 </tr> 
</table>

<div style="display: none">
{% include ip-statements-en.xhtml %}
{% include dependency-table-short-en.xhtml %}
{% include globals-table-en.xhtml %}
</div>
