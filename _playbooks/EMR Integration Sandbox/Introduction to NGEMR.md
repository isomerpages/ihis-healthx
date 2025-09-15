---
title: Introduction to NGEMR
permalink: /introduction-to-ngemr/
variant: tiptap
description: ""
third_nav_title: EMR Integration Sandbox
---
<h3>Introduction</h3>
<p>The <strong>Next Generation Electronic Medical Record (NGEMR)</strong> is
Singapore’s national EMR platform, powered by the Epic system, and implemented
across the public healthcare clusters. NGEMR serves as the single, integrated
record for patient care, ensuring consistency, safety, and continuity across
institutions</p>
<h3>Integration Standards</h3>
<p>NGEMR supports integration through widely adopted healthcare data standards:</p>
<ul data-tight="true" class="tight">
<li>
<p><strong>HL7 v2</strong> – for clinical messaging and data exchange.</p>
</li>
<li>
<p><strong>FHIR (Fast Healthcare Interoperability Resources)</strong> – for
modern, standards-based APIs.</p>
</li>
</ul>
<p>These standards enable external applications and systems to interoperate
securely with NGEMR.</p>
<h3>Testing Integration</h3>
<p>To test integrations with NGEMR, two main environments are available:</p>
<p>1. <a href="https://fhir.epic.com/Documentation?docId=testpatients" rel="noopener nofollow" target="_blank">Epic Sandbox</a> –
Provides access to Epic’s standard sandbox environment and APIs.</p>
<p>2. <a href="https://apidocs.healthx.sg/ngemr" rel="noopener nofollow" target="_blank">HealthX Innovation Sandbox APIs</a> –
A local environment that mirrors NGEMR with equivalent APIs, synthetic
data, and workflows for innovators to test safely.</p>
<h3>Epic APIs</h3>
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
<p>
<br>Refer to <a href="https://open.epic.com" class="fui-Link ___1q1shib f2hkw1w f3rmtva f1ewtqcl fyind8e f1k6fduh f1w7gpdv fk6fouc fjoy568 figsok6 f1s184ao f1mk8lai fnbmjn9 f1o700av f13mvf36 f1cmlufx f9n3di6 f1ids18y f1tx3yz7 f1deo86v f1eh06m1 f1iescvh fhgqx19 f1olyrje f1p93eir f1nev41a f1h8hb77 f1lqvz6u f10aw75t fsle3fq f17ae5zn" rel="noreferrer noopener" target="_blank">Open.Epic</a> for the official API documentation
and details.
<br>Equivalent APIs are also made available in the <a href="https://apidocs.healthx.sg/ngemr" rel="noopener nofollow" target="_blank">HealthX Innovation Sandbox APIs</a> to
support testing and validation.</p>
<p></p>
<p></p>
<p></p>
<p></p>
<p>
<br>
</p>
<p></p>