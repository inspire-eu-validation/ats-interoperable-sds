ats-interoperable-sds
===========================

Abstract Test Suite for "Interoperable Spatial Data Services"
as defined in the Technical Guidance for INSPIRE Spatial Data Services and services allowing spatial data services to be invoked.

*Note*: This ATS is in draft stage, none of the tests have an official INSPIRE MIG approval.

## External document references

| Abbreviation | Document name                       |
| ------------ | ----------------------------------- |
| INSPIRE <a name="ref_INSPIRE"></a> | [Directive 2007/2/EC of the European Parliament and of the Council of 14 March 2007 establishing an Infrastructure for Spatial Information in the European Community (INSPIRE)](http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32007L0002&from=EN)
| INT SDS <a name="ref_INT_SDS"></a> | [Commission Regulation (EU) No 1089/2010 of 23 November 2010 implementing Directive 2007/2/EC of the European Parliament and of the Council as regards interoperability of spatial data sets and services](http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=OJ:L:2010:323:FULL&from=EN)
| INT SDS AMD <a name="ref_INT_SDS_AMD"></a> | [Commission Regulation (EU) No 1312/2014 of 10 December 2014 amending Regulation (EU) No 1089/2010 implementing Directive 2007/2/EC of the European Parliament and of the Council as regards interoperability of spatial data services](http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32014R1312&from=EN)
| IR NS <a name="ref_IR_NS"></a>   | [Commission Regulation (EC) No 976/2009 of 19 October 2009 implementing Directive 2007/2/EC of the European Parliament and of the Council as regards the Network Services](http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32009R0976&from=EN)
| IR NS AMD <a name="ref_IR_NS_AMD"></a> | [Commission Regulation (EU) No 1311/2014 of 10 December 2014 amending Regulation (EC) No 976/2009 as regards the definition of an INSPIRE metadata element](http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32014R1311&from=EN)
| TG SDS <a name="ref_TG_SDS"></a> | [Technical Guidance for INSPIRE Spatial Data Services and services allowing spatial data services to be invoked](http://inspire.jrc.ec.europa.eu/documents/Spatial_Data_Services/TG_for_INSPIRE_SDS_3_1.pdf)
| SDS ALT <a name="ref_SDS_alt"></a> | Alternative approaches to implement Metadata for Spatial data services (not published?)

## TG Requirement coverage

Based on requirement numbering in [TG SDS](#ref_TG_SDS).

| Req#   | Description                          | Covered by test(s)                 | IR reference(s)                  |
| ------ | ------------------------------------ | ---------------------------------- | -------------------------------- |
| 6      | Supported CRSes as a list | [A.01.IR06.IR07.supported.crses.as.list](A.01.IR06.IR07.supported.crses.as.list.md)| |
| 7      | CRS identifiers | [A.01.IR06.IR07.supported.crses.as.list](A.01.IR06.IR07.supported.crses.as.list.md) | |
| 8      | Indicate QoS for availability | [A.02.IR08.extension.for.QoS.declared.availability](A.02.IR08.extension.for.QoS.declared.availability.md) OR [A.06.IR08.DQ_ConceptualConsistency.for.QoS.declared.availability](A.06.IR08.DQ_ConceptualConsistency.for.QoS.declared.availability.md) | |
| 9      | Indicate QoS for performance | [A.03.IR09.extension.for.QoS.declared.performance](A.03.IR09.extension.for.QoS.declared.performance.md) OR [A.07.IR09.DQ_ConceptualConsistency.for.QoS.declared.performance](A.07.IR09.DQ_ConceptualConsistency.for.QoS.declared.performance.md) | |
| 10     | Indicate QoS for capacity |[A.04.IR10.extension.for.QoS.declared.capacity](A.04.IR10.extension.for.QoS.declared.capacity.md) OR [A.08.IR10.DQ_ConceptualConsistency.for.QoS.declared.capacity](A.08.IR10.DQ_ConceptualConsistency.for.QoS.declared.capacity.md) | |
| 11     | Provide "custodian" contact point | [A.05.IR11.custodian.contact.point](A.05.IR11.custodian.contact.point.md) | |
| 12     | Constraints for access and use | not automatically testable |  |

## Tests

The ATS for the "TG Conformance Class 2:Spatial data services compliant with interoperability arrangements"
includes all the tests in the [ATS for TG Conformance Class 1, Invocable SDS](https://github.com/inspire-eu-validation/ats-invocable-sds), and additionally
the following tests:

| Identifier                                                        | Status   |
| ----------------------------------------------------------------- | -------- |
| [A.01.IR06.IR07.supported.crses.as.list](A.01.IR06.IR07.supported.crses.as.list.md) | missing |
| [A.02.IR08.extension.for.QoS.declared.availability](A.02.IR08.extension.for.QoS.declared.availability.md) | missing |
| [A.03.IR09.extension.for.QoS.declared.performance](A.03.IR09.extension.for.QoS.declared.performance.md) | missing |
| [A.04.IR10.extension.for.QoS.declared.capacity](A.04.IR10.extension.for.QoS.declared.capacity.md) | missing |
| [A.05.IR11.custodian.contact.point](A.05.IR11.custodian.contact.point.md) | missing |

## Tests (MIWP-8 alternative)

The ATS for the "TG Conformance Class 2:Spatial data services compliant with interoperability arrangements"
according to the alternative option for the QoS reporting proposed by MIWP-8, includes all the tests
in the [ATS for TG Conformance Class 1, Invocable SDS](https://github.com/inspire-eu-validation/ats-invocable-sds), and additionally
the following tests:

| Identifier                                                        | Status   |
| ----------------------------------------------------------------- | -------- |
| [A.01.IR06.IR07.supported.crses.as.list](A.01.IR06.IR07.supported.crses.as.list.md) | missing |
| [A.06.IR08.DQ_ConceptualConsistency.for.QoS.declared.availability](A.06.IR08.DQ_ConceptualConsistency.for.QoS.declared.availability.md) | missing |
| [A.07.IR09.DQ_ConceptualConsistency.for.QoS.declared.performance](A.07.IR09.DQ_ConceptualConsistency.for.QoS.declared.performance.md) | missing |
| [A.08.IR10.DQ_ConceptualConsistency.for.QoS.declared.capacity](A.08.IR10.DQ_ConceptualConsistency.for.QoS.declared.capacity.md) | missing |
| [A.05.IR11.custodian.contact.point](A.05.IR11.custodian.contact.point.md) | missing |


## XML namespace prefixes <a name="namespaces"></a>

The following prefixes are used to refer to the corresponding XML namespaces in all test descriptions:

Prefix         | Namespace
-------------- | -------------------------------------------------
gmd | http://www.isotc211.org/2005/gmd
gml | http://www.opengis.net/gml/3.2
srv | http://www.isotc211.org/2005/srv
inspire\_sds_gmd | [missing]
xlink          | http://www.w3.org/1999/xlink
