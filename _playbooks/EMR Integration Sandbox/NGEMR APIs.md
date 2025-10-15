---
title: NGEMR APIs
permalink: /ngemr-apis/
variant: tiptap
description: ""
third_nav_title: EMR Integration Sandbox
---
<h3><strong>FHIR APIs</strong></h3>
<p>NGEMR primarily uses the following Epic APIs for integration. These include
clinical, scheduling, medication, practitioner, and patient information
endpoints.</p>
<table style="minWidth: 100px">
<colgroup>
<col>
<col>
<col>
<col>
</colgroup>
<tbody>
<tr>
<td rowspan="1" colspan="1">
<p><strong>Category</strong>​</p>
</td>
<td rowspan="1" colspan="1">
<p><strong>FHIR API</strong>​</p>
</td>
<td rowspan="1" colspan="1">
<p><strong>FHIR Version</strong>​</p>
</td>
<td rowspan="1" colspan="1">
<p><strong>Description</strong>​</p>
</td>
</tr>
<tr>
<td rowspan="2" colspan="1">
<p><strong>Patient Profile</strong>​</p>
<p>​</p>
</td>
<td rowspan="1" colspan="1">
<p><a href="https://fhir.epic.com/Sandbox?api=930" class="Hyperlink" rel="noreferrer" target="_blank"><u>Patient.Create</u></a>​</p>
</td>
<td rowspan="1" colspan="1">
<p>R4​</p>
</td>
<td rowspan="1" colspan="1">
<p>Create a Patient resource​</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><a href="https://fhir.epic.com/Sandbox?api=930" rel="noopener noreferrer nofollow" target="_blank"><u>Patient.Search</u></a>​</p>
</td>
<td rowspan="1" colspan="1">
<p>R4​</p>
</td>
<td rowspan="1" colspan="1">
<p>Search for a patient using parameters like name, address, identifier,
etc.,​</p>
</td>
</tr>
<tr>
<td rowspan="9" colspan="1">
<p><strong>Clinical Information</strong>​</p>
<p>​</p>
</td>
<td rowspan="1" colspan="1">
<p><a href="https://fhir.epic.com/Sandbox?api=930" rel="noopener noreferrer nofollow" target="_blank"><u>AllergyIntolerance.Search</u></a>​</p>
</td>
<td rowspan="1" colspan="1">
<p>R4​</p>
</td>
<td rowspan="1" colspan="1">
<p>Find clinical information about a patient's allergic response to a substance​</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><a href="https://fhir.epic.com/Sandbox?api=930" rel="noopener noreferrer nofollow" target="_blank"><u>Condition.Search</u></a>
<a href="https://fhir.epic.com/Sandbox?api=10140" class="Hyperlink" rel="noreferrer" target="_blank"><u> (Infection)</u>
</a>​</p>
</td>
<td rowspan="1" colspan="1">
<p>R4​</p>
</td>
<td rowspan="1" colspan="1">
<p>Retrieve an infection from a patient's chart.​</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><a href="https://fhir.epic.com/Sandbox?api=930" rel="noopener noreferrer nofollow" target="_blank"><u>Condition.Search</u></a>
<a href="https://fhir.epic.com/Sandbox?api=10302" class="Hyperlink" rel="noreferrer" target="_blank"><u> (Medical History)</u>
</a>​</p>
</td>
<td rowspan="1" colspan="1">
<p>R4​</p>
</td>
<td rowspan="1" colspan="1">
<p>Retrieve a single medical history problem or pertinent negative from a
patient’s chart.​</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><a href="https://fhir.epic.com/Sandbox?api=930" rel="noopener noreferrer nofollow" target="_blank"><u>Condition.Search</u></a>
<a href="https://fhir.epic.com/Sandbox?api=951" class="Hyperlink" rel="noreferrer" target="_blank"><u> (Problems)</u>
</a>​</p>
</td>
<td rowspan="1" colspan="1">
<p>R4​</p>
</td>
<td rowspan="1" colspan="1">
<p>Retrieve a single problem from a patient's chart​</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><a href="https://fhir.epic.com/Sandbox?api=930" rel="noopener noreferrer nofollow" target="_blank"><u>Procedure.Search</u></a>
<a href="https://fhir.epic.com/Sandbox?api=976" class="Hyperlink" rel="noreferrer" target="_blank"><u> (Orders)</u>
</a>​</p>
</td>
<td rowspan="1" colspan="1">
<p>R4​</p>
</td>
<td rowspan="1" colspan="1">
<p>Get list of surgeries and procedures performed, including endoscopies
and biopsies, as well as less invasive actions like counseling and physiotherapy,
for a patient​</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><a href="https://fhir.epic.com/Sandbox?api=930" rel="noopener noreferrer nofollow" target="_blank"><u>Procedure.Search</u></a>
<a href="https://fhir.epic.com/Sandbox?api=10042" class="Hyperlink" rel="noreferrer" target="_blank"><u> (Surgeries)</u>
</a>​</p>
</td>
<td rowspan="1" colspan="1">
<p>R4​</p>
</td>
<td rowspan="1" colspan="1">
<p>Get summary of any performed surgical procedures for a patient.​</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><a href="https://fhir.epic.com/Sandbox?api=930" rel="noopener noreferrer nofollow" target="_blank"><u>Procedure.Search</u></a>
<a href="https://fhir.epic.com/Sandbox?api=10030" class="Hyperlink" rel="noreferrer" target="_blank"><u> (Surgical History)</u>
</a>​</p>
</td>
<td rowspan="1" colspan="1">
<p>R4​</p>
</td>
<td rowspan="1" colspan="1">
<p>Get summary of historical surgical procedures a patient has had, as well
as pertinent negatives (indicating a patient has not had a particular surgery).​</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><a href="https://fhir.epic.com/Sandbox?api=930" rel="noopener noreferrer nofollow" target="_blank"><u>List.Search</u></a>
<a href="https://fhir.epic.com/Sandbox?api=10147" class="Hyperlink" rel="noreferrer" target="_blank"><u> (Allergies)</u>
</a>​</p>
</td>
<td rowspan="1" colspan="1">
<p>R4​</p>
</td>
<td rowspan="1" colspan="1">
<p>Retrieve current allergies in a patient’s Allergy list in their chart​</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><a href="https://fhir.epic.com/Sandbox?api=930" rel="noopener noreferrer nofollow" target="_blank"><u>Flag.Search</u></a>
<a href="https://fhir.epic.com/Sandbox?api=10165" class="Hyperlink" rel="noreferrer" target="_blank"><u> (Patient FYI)</u>
</a>​</p>
</td>
<td rowspan="1" colspan="1">
<p>R4​</p>
</td>
<td rowspan="1" colspan="1">
<p>Retrieves patient FYI flags from the patient's chart. Patient FYIs are
short, free-text notes associated with a patient record. ​</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><strong>Medication Order</strong>​</p>
</td>
<td rowspan="1" colspan="1">
<p><a href="https://fhir.epic.com/Sandbox?api=930" rel="noopener noreferrer nofollow" target="_blank"><u>MedicationRequest.Search</u></a>
<a href="https://fhir.epic.com/Sandbox?api=997" class="Hyperlink" rel="noreferrer" target="_blank"><u> (Signed Medication Order)</u>
</a>​</p>
</td>
<td rowspan="1" colspan="1">
<p>R4​</p>
</td>
<td rowspan="1" colspan="1">
<p>Query for medication orders based on a patient and optionally status or
category​</p>
</td>
</tr>
<tr>
<td rowspan="3" colspan="1">
<p><strong>Encounters</strong>​</p>
<p>​</p>
</td>
<td rowspan="1" colspan="1">
<p><a href="https://fhir.epic.com/Sandbox?api=930" rel="noopener noreferrer nofollow" target="_blank"><u>Encounter.Search</u></a>​</p>
</td>
<td rowspan="1" colspan="1">
<p>R4​</p>
</td>
<td rowspan="1" colspan="1">
<p>Retrieve all inpatient encounters in the specified time period​</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><a href="https://fhir.epic.com/Sandbox?api=963" class="Hyperlink" rel="noreferrer" target="_blank"><u>Observation.Create (Vitals)</u></a>​</p>
</td>
<td rowspan="1" colspan="1">
<p>R4​</p>
</td>
<td rowspan="1" colspan="1">
<p>Write vital signs observations of a patient​</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><a href="https://fhir.epic.com/Sandbox?api=930" rel="noopener noreferrer nofollow" target="_blank"><u>Location.Read</u></a>​</p>
</td>
<td rowspan="1" colspan="1">
<p>R4​</p>
</td>
<td rowspan="1" colspan="1">
<p>Retrieves details and position information for a physical place where
resources and participants can be found.​</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><strong>Appointments</strong>​</p>
</td>
<td rowspan="1" colspan="1">
<p><a href="https://fhir.epic.com/Sandbox?api=930" rel="noopener noreferrer nofollow" target="_blank"><u>Appointment.Search</u></a>
<a href="https://fhir.epic.com/Sandbox?api=10189" class="Hyperlink" rel="noreferrer" target="_blank"><u> (Appointments)</u>
</a>​</p>
</td>
<td rowspan="1" colspan="1">
<p>STU3​</p>
</td>
<td rowspan="1" colspan="1">
<p>Search for appointment Info​</p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p><strong>Practitioner Profile</strong>​</p>
</td>
<td rowspan="1" colspan="1">
<p><a href="https://fhir.epic.com/Sandbox?api=930" rel="noopener noreferrer nofollow" target="_blank"><u>Practitioner.Search</u></a>​</p>
</td>
<td rowspan="1" colspan="1">
<p>STU3​</p>
</td>
<td rowspan="1" colspan="1">
<p>Search and get information of a doctor​</p>
</td>
</tr>
</tbody>
</table>
<p>The equivalent FHIR APIs are available in <a href="https://apidocs.healthx.sg/ngemr" rel="noopener nofollow" target="_blank"><u>EMR Integration Sandbox APIs</u></a>.</p>
<h3>Health Level 7 Version 2 (HL7 v2)</h3>
<p>Another common way to connect Epic with third parties is to use <strong>Health Level 7 Version 2 protocol (HL7 v2)</strong>.
This is the most common standard used with Epic.</p>
<h4>HL7 Message Type</h4>
<p>Given below are the message types currently sent out by Epic in NGEMR
context.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="" src="/images/HL7_MeesageTypes_01.png">
</div>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="" src="/images/HL7_MeesageTypes_02.png">
</div>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="" src="/images/HL7_MeesageTypes_03.png">
</div>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="" src="/images/HL7_MeesageTypes_04.png">
</div>
<h4>Example use-cases for HL7 v2</h4>
<ol data-tight="true" class="tight">
<li>
<p><strong>Outgoing Patient Administration – Registration and ADT Interface&nbsp;</strong>&nbsp;</p>
</li>
</ol>
<p>Informs external systems of new patient creation, changes to patient demographic
information, visits (ADT), registration (guarantors and insurance coverage),
allergies, and bed status updates. You can trigger these messages from
many of Epic's applications. The ability to send allergy updates is only
applicable if you are using the Allergy activity and need to send allergy
updates to an external system.&nbsp;</p>
<p>&nbsp;<strong>Communication Methods</strong>&nbsp;</p>
<p>Epic recommends using the Outgoing TCP/IP Using Database Servers communication
method.&nbsp;</p>
<p>Other supported communications methods include:&nbsp;</p>
<ol>
<li>
<p>Outgoing TCP/IP Using Interconnect&nbsp;</p>
</li>
</ol>
<ol start="2">
<li>
<p>HL7v2 Batch Using Database Server&nbsp;</p>
</li>
</ol>
<ol start="3">
<li>
<p>Outgoing HL7v2 Over HTTPS Using Interconnect&nbsp;</p>
</li>
</ol>
<ol start="4">
<li>
<p>Outgoing DIRECT Using Interconnect&nbsp;</p>
<p></p>
</li>
</ol>
<p><strong>ADT^A01 Admit/Visit Notification</strong>&nbsp;</p>
<p>This trigger event is used when a patient is assigned a bed during admission
to a hospital or hospital outpatient department.&nbsp;</p>
<p>&nbsp;<strong>Context</strong>&nbsp;</p>
<p>Admitting a patient in Grand Central or rooming a patient in ASAP generates
an A01.&nbsp;</p>
<p>&nbsp;<strong>A01 Format Example</strong>&nbsp;</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="" src="/images/A01_Example.png">
</div>
<p></p>
<p><strong>ADT^A02 Transfer a Patient</strong>&nbsp;</p>
<p>This trigger event is used when a patient is transferred within the ADT
system.&nbsp;</p>
<p><strong>Context</strong>&nbsp;</p>
<p>Transferring a patient between hospital units, from the ED to a unit,
or transferring beds within the ED will generate an A02.&nbsp;</p>
<p><strong>A02 Format Example</strong>&nbsp;</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="" src="/images/A02_Example.png">
</div>
<p>&nbsp;</p>
<p><strong>ADT^A03 Discharge/End Visit</strong>&nbsp;</p>
<p>This trigger event is used when a patient is discharged from the ADT system.&nbsp;&nbsp;</p>
<p><strong>A03 – Patient Discharge</strong>&nbsp;</p>
<p>Discharging a patient, either in ADT or via a batch job that closes Hospital
Outpatient Visits, generates an A03. The interface can also generate an
A03 message when a Cadence appointment is checked out or completed.&nbsp;</p>
<p><strong>A03 – Disassociate a Medication Management Device&nbsp;</strong>&nbsp;</p>
<p>The interface can generate an A03 when a patient, visit, and workstation
record should no longer be associated with advice that documents the administration
of intravenous drugs. These messages work in conjunction with the Incoming
Anesthesia Medication Documentation interface to file medication administration
information to the patient's MAR.&nbsp;</p>
<p>The receiving system uses the patient identifier from PID-3, the visit
identifier from PV-19, and the workstation sent in an OBX segment to associate
the patient to the device.&nbsp;</p>
<p><strong>A03 Format Example</strong>&nbsp;</p>
<p></p>