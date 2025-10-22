---
title: NGEMR APIs
permalink: /ngemr-apis/
variant: tiptap
description: ""
third_nav_title: EMR Integration Sandbox
---
<h2><strong>FHIR APIs</strong></h2>
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
<p><a href="https://fhir.epic.com/Specifications?api=932" rel="noopener noreferrer nofollow" target="_blank"><u>Patient.Search</u></a>​</p>
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
<p><a href="https://fhir.epic.com/Specifications?api=947" rel="noopener noreferrer nofollow" target="_blank"><u>AllergyIntolerance.Search</u></a>​</p>
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
<p><a href="https://fhir.epic.com/Specifications?api=10141" rel="noopener noreferrer nofollow" target="_blank"><u>Condition.Search(Infection)</u></a>​</p>
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
<p><a href="https://fhir.epic.com/Specifications?api=10314" rel="noopener noreferrer nofollow" target="_blank"><u>Condition.Search(Medical History)</u></a>​</p>
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
<p><a href="https://fhir.epic.com/Specifications?api=953" rel="noopener noreferrer nofollow" target="_blank"><u>Condition.Search(Problems)</u></a>​</p>
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
<p><a href="https://fhir.epic.com/Specifications?api=976" rel="noopener noreferrer nofollow" target="_blank"><u>Procedure.Search(Orders)</u></a>
</p>
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
<a href="https://fhir.epic.com/Specifications?api=10042" class="Hyperlink" rel="noreferrer" target="_blank"><u>(Surgeries)</u>
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
<p><a href="https://fhir.epic.com/Specifications?api=10030" rel="noopener noreferrer nofollow" target="_blank"><u>Procedure.Search(Surgical History)</u></a>​</p>
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
<p><a href="https://fhir.epic.com/Specifications?api=10147" rel="noopener noreferrer nofollow" target="_blank"><u>List.Search(Allergies)</u></a>
</p>
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
<p><a href="https://fhir.epic.com/Specifications?api=10166" rel="noopener noreferrer nofollow" target="_blank"><u>Flag.Search(Patient FYI)</u></a>
</p>
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
<p><a href="https://fhir.epic.com/Specifications?api=997" rel="noopener noreferrer nofollow" target="_blank"><u>MedicationRequest.Search</u></a>
<a href="https://fhir.epic.com/Specifications?api=997" class="Hyperlink" rel="noreferrer" target="_blank"><u>(Signed Medication Order)</u>
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
<p><a href="https://fhir.epic.com/Specifications?api=909" rel="noopener noreferrer nofollow" target="_blank"><u>Encounter.Search</u></a>​</p>
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
<p><a href="https://fhir.epic.com/Specifications?api=963" class="Hyperlink" rel="noreferrer" target="_blank"><u>Observation.Create(Vitals)</u></a>​</p>
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
<p><a href="https://fhir.epic.com/Specifications?api=928" rel="noopener noreferrer nofollow" target="_blank"><u>Location.Read</u></a>​</p>
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
<p><a href="https://fhir.epic.com/Specifications?api=10469" rel="noopener noreferrer nofollow" target="_blank"><u>Appointment.Search</u></a>
</p>
</td>
<td rowspan="1" colspan="1">
<p>R4​</p>
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
<p><a href="https://fhir.epic.com/Specifications?api=936" rel="noopener noreferrer nofollow" target="_blank"><u>Practitioner.Search</u></a>
</p>
</td>
<td rowspan="1" colspan="1">
<p>R4​</p>
</td>
<td rowspan="1" colspan="1">
<p>Search and get information of a doctor​</p>
</td>
</tr>
</tbody>
</table>
<p>The equivalent FHIR APIs are available in <a href="https://apidocs.healthx.sg/ngemr" rel="noopener nofollow" target="_blank"><u>EMR Integration Sandbox APIs</u></a>.</p>
<h2>Health Level 7 Version 2 (HL7 v2)</h2>
<p>Another common way to connect Epic with third parties is to use <strong>Health Level 7 Version 2 protocol (HL7 v2)</strong>.
This is the most common standard used with Epic.</p>
<p>Refer to <a href="https://open.epic.com/Identity/HL7v2" rel="noopener noreferrer nofollow" target="_blank">Epic documentation</a> to
learn more about this standard.</p>