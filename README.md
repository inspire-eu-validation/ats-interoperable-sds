ats-interoperable-sds
===========================

Abstract Test Suite for "Interoperable Spatial Data Services"
as defined in the Technical Guidance for INSPIRE Spatial Data Services and services allowing spatial data services to be invoked.

*Note*: This ATS is in ready-for-review stage, none of the tests have an official INSPIRE MIG approval.

## External document references

| Abbreviation | Document name                       |
| ------------ | ----------------------------------- |
| INSPIRE <a name="ref_INSPIRE"></a> | [Directive 2007/2/EC of the European Parliament and of the Council of 14 March 2007 establishing an Infrastructure for Spatial Information in the European Community (INSPIRE)](http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32007L0002&from=EN)
| INT SDS <a name="ref_INT_SDS"></a> | [Commission Regulation (EU) No 1089/2010 of 23 November 2010 implementing Directive 2007/2/EC of the European Parliament and of the Council as regards interoperability of spatial data sets and services](http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=OJ:L:2010:323:FULL&from=EN)
| INT SDS AMD <a name="ref_INT_SDS_AMD"></a> | [Commission Regulation (EU) No 1312/2014 of 10 December 2014 amending Regulation (EU) No 1089/2010 implementing Directive 2007/2/EC of the European Parliament and of the Council as regards interoperability of spatial data services](http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32014R1312&from=EN)
| IR MD <a name="ref_IR_MD"></a> | [Commission Regulation (EC) No 1205/2008 of 3 December 2008 implementing Directive 2007/2/EC of the European Parliament and of the Council as regards metadata (Text with EEA relevance)](http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32008R1205&from=EN)
| IR NS <a name="ref_IR_NS"></a>   | [Commission Regulation (EC) No 976/2009 of 19 October 2009 implementing Directive 2007/2/EC of the European Parliament and of the Council as regards the Network Services](http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32009R0976&from=EN)
| IR NS AMD <a name="ref_IR_NS_AMD"></a> | [Commission Regulation (EU) No 1311/2014 of 10 December 2014 amending Regulation (EC) No 976/2009 as regards the definition of an INSPIRE metadata element](http://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32014R1311&from=EN)
| TG SDS <a name="ref_TG_SDS"></a> | [Technical Guidance for INSPIRE Spatial Data Services and services allowing spatial data services to be invoked](http://inspire.jrc.ec.europa.eu/documents/Spatial_Data_Services/TG_for_INSPIRE_SDS_3_1.pdf)
| SDS ALT <a name="ref_SDS_alt"></a> | Alternative approaches to implement Metadata for Spatial data services (not published?)
| DS CRS <a name="ref_DS_CRS"></a> | [D2.8.I.1 Data Specification on Coordinate Reference Systems – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_RS_v3.2.pdf)

## TG Requirement coverage

Based on requirement numbering in [TG SDS](#ref_TG_SDS).

| Req#   | Description                          | Covered by test(s)                 | IR reference(s)                  |
| ------ | ------------------------------------ | ---------------------------------- | -------------------------------- |
| 6      | Supported CRSes as a list | [A.01.IR06.IR07.supported.crses.as.list](a-01-ir06-ir07-supported-crses-as-list.md)| |
| 7      | CRS identifiers | [A.01.IR06.IR07.supported.crses.as.list](a-01-ir06-ir07-supported-crses-as-list.md) | |
| 8      | Indicate QoS for availability | [A.02.IR08.extension.for.QoS.declared.availability](a-02-ir08-extension-for-qos-declared-availability.md) or [a.06.ir08.dq_conceptualconsistency.for.qos.declared.availability](a.06.ir08.dq_conceptualconsistency.for.qos.declared.availability.md) | |
| 9      | Indicate QoS for performance | [A.03.IR09.extension.for.QoS.declared.performance](a-03-ir09-extension-for-qos-declared-performance.md) or [a.07.ir09.dq_conceptualconsistency.for.qos.declared.performance](a.07.ir09.dq_conceptualconsistency.for.qos.declared.performance.md) | |
| 10     | Indicate QoS for capacity |[A.04.IR10.extension.for.QoS.declared.capacity](a-04-ir10-extension-for-qos-declared-capacity.md) or [a.08.ir10.dq_conceptualconsistency.for.qos.declared.capacity](a.08.ir10.dq_conceptualconsistency.for.qos.declared.capacity.md) | |
| 11     | Provide "custodian" contact point | [A.05.IR11.custodian.contact.point](a-05-ir11-custodian-contact-point.md) | |
| 12     | Constraints for access and use | not automatically testable |  |

## Tests

The ATS for the "TG Conformance Class 2:Spatial data services compliant with interoperability arrangements"
includes all the tests in the [ATS for TG Conformance Class 1, Invocable SDS](https://github.com/inspire-eu-validation/ats-invocable-sds), and additionally
the following tests:

| Identifier                                                        | Status   |
| ----------------------------------------------------------------- | -------- |
| [A.01.IR06.IR07.supported.crses.as.list](a-01-ir06-ir07-supported-crses-as-list.md) | ready for review |
| [A.02.IR08.extension.for.QoS.declared.availability](a-02-ir08-extension-for-qos-declared-availability.md) | ready for review |
| [A.03.IR09.extension.for.QoS.declared.performance](a-03-ir09-extension-for-qos-declared-performance.md) | ready for review |
| [A.04.IR10.extension.for.QoS.declared.capacity](a-04-ir10-extension-for-qos-declared-capacity.md) | ready for review |
| [A.05.IR11.custodian.contact.point](a-05-ir11-custodian-contact-point.md) | ready for review |
| [A.09.IR01.SDS.SV_ServiceIdentification](a.09.ir01.sds.sv_serviceidentification.md) | ready for review |

## Tests (MIWP-8 alternative)

The ATS for the "TG Conformance Class 2:Spatial data services compliant with interoperability arrangements"
according to the alternative option for the QoS reporting proposed by MIWP-8, includes all the tests
in the [ATS for TG Conformance Class 1, Invocable SDS](https://github.com/inspire-eu-validation/ats-invocable-sds), and additionally
the following tests:

| Identifier                                                        | Status   |
| ----------------------------------------------------------------- | -------- |
| [A.01.IR06.IR07.supported.crses.as.list](a-01-ir06-ir07-supported-crses-as-list.md) | ready for review |
| [A.06.IR08.DQ_ConceptualConsistency.for.QoS.declared.availability](a.06.ir08.dq_conceptualconsistency.for.qos.declared.availability.md) | ready for review |
| [A.07.IR09.DQ_ConceptualConsistency.for.QoS.declared.performance](a.07.ir09.dq_conceptualconsistency.for.qos.declared.performance.md) |ready for review |
| [A.08.IR10.DQ_ConceptualConsistency.for.QoS.declared.capacity](a.08.ir10.dq_conceptualconsistency.for.qos.declared.capacity.md) | ready for review |
| [A.05.IR11.custodian.contact.point](a-05-ir11-custodian-contact-point.md) | ready for review |
| [A.10.IR01.DQ_DomainConsistency.report.for.classification](a.10.ir01.dq_domainconsistency.report.for.classification.md) | ready for review |

## Open issues
* The extension to the ISO 19119 metadata class ```SV_ServiceIdentification``` is defined twice in [TG SDS](#ref_TG_SDS): in Annex A just the ```category``` as a mandatory property is added, and in Annex C just the ```qualityOfService``` mandatory property is added. This means that the neither of these extended classes can be used to fulfill both the requirements IR 1 and IR 8, IR 9 or IR 10 at the same time.
* The XML Schema for the inspire_sds_gmd has not been published yet, so the XML Schema validation is not possible.

## XML namespace prefixes <a name="namespaces"></a>

The following prefixes are used to refer to the corresponding XML namespaces in all test descriptions:

Prefix         | Namespace
-------------- | -------------------------------------------------
gmd | http://www.isotc211.org/2005/gmd
gml | http://www.opengis.net/gml/3.2
srv | http://www.isotc211.org/2005/srv
inspire\_sds\_gmd | [missing]
xlink          | http://www.w3.org/1999/xlink
