# Change History #


### Version: 1.0; Status: Draft B #

**Examples**

The following examples were added to the Domain Message Specification:-

- DDS-Report-Specimen-1-0-Ex02: This example shows an example of a cervical smear specimen.
- DDS-Report-Patient-1-0-Ex02: A female patient.
- DDS-Report-Organization-1-0-Ex02: An NHS Trust Pathology Services Organisation example for Diagnostic Data Services.
- DDS-Report-Organization-1-0-Ex03: A Pharmaceutical company organisation example for Diagnostic Data Services.
- DDS-Report-Observation-1-0-BT: An example for a Blood Transfusion Blood typing test.
- DDS-Report-Observation-1-0-Microbiology: An example for a Microbiology Hepatitis B screening test.
- DDS-Report-Observation-1-0-Histopathology: An example for a Cytology cervical screening test result. 


### Version: 1.0; Status: Draft A #


First draft of Diagnostic Data Services Domain Message Specification.

**Profiles**

The following profiles have been created as initial drafts for the Domain Message Specification (DMS):-

- DDS-Request-1-0: This shows details of the original request, for example for a Diagnostic test on a patient.
- DDS-Report-1-0: This is the Diagnostic report, for example showing a report relating to a Diagnostic test.
- DDS-Report-Specimen-1-0: This shows a specimen for a Diagnostic test.
- DDS-Report-Substance-1-0: This describes a substance in the context of Diagnostic services and any ingredients that it may comprise of.
- DDS-Report-Patient-1-0: This describes a patient who is the subject of activities, such as tests, within a Diagnostic services' context.
- DDS-Report-Health-Care-Professional-1-0: This shows a health care professional in a Diagnostic services'context.
- DDS-Report-Organization-1-0: This profile shows a Diagnostic services' organisation.
- DDS-Report-Device-1-0: This device profile describes devices which may be used in the Diagnostic services' context.
- DDS-Report-Supporting-Information-1-0: This is a constrained FHIR observation resource used to show any relevant supporting information relating to the subject of the observation.
- DDS-Report-Family-Member-History-1-0: A profile which shows significant health events and conditions for a particular individual related to the subject.
- DDS-Report-Observation-1-0: A profile which shows a constrained FHIR observation resource representing observations, such as results of laboratory and other tests in a Diagnostic Data Services context. 

**Architecture**

An informational page showing the proposed architecture for this DMS has been published.

**Examples**

The following xml examples have been created as initial drafts:-

- DDS-Request-1-0-Ex01: This describes a request for a Diagnostic services' test.
- DDS-Report-1-0-Ex-01: This shows a Diagnostic report relating to the results of a Diagnostic test.
- DDS-Report-Specimen-Ex01: An example showing a blood sample specimen.
- DDS-Report-Substance-1-0-Ex01: This describes a substance used in Diagnostic services context, in this a tablet listing its ingredients.
- DDS-Report-Patient-1-0-Ex01: A male patient.
- DDS-Report-Health-Care-Professional-1-0-Ex01: A health care practitioner example, in this case a medical practitioner.
- DDS-Report-Organization-1-0-Ex01: An example describing a Diagnostic services' related organisation, in this case a sample GP practice.
- DDS-Report-Device-1-0: This shows a device in the Diagnostic services' context.
- DDS-Report-Supporting-Information-Observation-1-0: An example of supporting information for an observation, in this case a test cancelled due to sample damage.
- DDS-Report-Family-Member-History-1-0: This example shows relevant family history for the subject of a Diagnostic services' test.
- DDS-Report-Observation-1-0-FBC: This observation describes a full blood count test.
