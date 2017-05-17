## FHIR Messaging Implementation and Architecture ##


**Diagnostic Data Services**

This section provides Diagnostic Data Services implementers with the information required to utilise the Diagnostic Data Services Domain Message Specification.

**Message Patterns and Message Structure**

The Diagnostic Data Services FHIR interface is based on the [HL7 FHIR DSTU2 1.0.1 Messaging Implementation] (Sept 2015) Messaging Implementation and supports one interaction. 

**Message acknowledgements and responses:**

Information to follow at a later date

**RPT-DiagnosticDataServicesReport-1-0 Interaction** 

The sender (Request Fulfiller) will construct a Diagnostic Data Services Report message and send it to the receiver (Request Placer) system.

- **Sender:** (Request Fulfiller):Diagnostic Data Services Report Message Originating System
- **Receiver:** (Request Placer):*Diagnostic Data Services Request Message Originating System
- **Message:** **Wire Format**: DiagnosticDataServicesReport-1-0

**Diagnostic Data Services Interaction Diagram**

The diagram shows the Diagnostic Data Services Interactions:

<div style="display: block;"><img  src="DiagnosticDataServicesInteractions.png" alt="DDAInteractions"></div>  