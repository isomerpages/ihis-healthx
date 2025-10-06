---
title: Testing integration in Sandbox
permalink: /testing-integration-in-sandbox/
variant: tiptap
description: ""
third_nav_title: EMR Integration Sandbox
---
<h3>Testing integration in Sandbox</h3>
<p>To test integrations with NGEMR in a sandbox, two main environments are
available:</p>
<p>1. <a href="https://fhir.epic.com/Documentation?docId=testpatients" rel="noopener nofollow" target="_blank">Epic Sandbox</a> –
Provides access to Epic’s standard sandbox environment and APIs.</p>
<p>2. <a href="https://apidocs.healthx.sg/ngemr" rel="noopener nofollow" target="_blank">HealthX Innovation Sandbox</a> –
A sandbox environment that simulates NGEMR with equivalent APIs, synthetic
data, and workflows for innovators to test safely.</p>
<h3>EMR Integration in HealthX Innovation Sandbox</h3>
<p>The HealthX Innovation Sandbox offers an open-source demo EMR application
and the sandbox APIs to experiment the integration with EMR. Follow the
steps given below to explore the integration.</p>
<h4>1. Explore APIs</h4>
<p><strong>FHIR APIs</strong>
</p>
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
<p></p>
<h4>2. Explore our HealthX EMR demo app</h4>
<p>The HealthX EMR demo app is developed using the above APIs.</p>
<p>To try the app,visit <a href="https://userapps.healthx.sg/apps/7e55a7f9-5f47-4b6d-84c3-7c754778b367" rel="noopener nofollow" target="_blank">HealthX EMR Demo App</a>
</p>
<p>Login using the following demo credentials:</p>
<p>Email:<strong> demo@healthx.sg</strong>
</p>
<p>Password: <strong>demo123</strong>
</p>
<p></p>
<h4>3. Build &amp; host your app in HealthX Innovation Sandbox</h4>
<p><strong>Create an App in HealthX Develop Portal</strong>
</p>
<ol data-tight="true" class="tight">
<li>
<p>Request for a HealthX Developer Account via <a href="https://form.gov.sg/6451bef4d0f2470011ddf40a" rel="noopener noreferrer nofollow" target="_blank">HealthX Innovation Sandbox Application Form</a>
</p>
</li>
<li>
<p>Once the account is created, create an App from the dashboard.</p>
</li>
</ol>
<p><strong>Refer to the source code to build your own app</strong>
</p>
<ol data-tight="true" class="tight">
<li>
<p>Clone our GitHub repository <a href="https://github.com/HealthTechSG/HXIS-Integration-Sandbox" rel="noopener noreferrer nofollow" target="_blank">https://github.com/HealthTechSG/HXIS-Integration-Sandbox</a>
</p>
</li>
<li>
<p>Update your app credentials in the .env file</p>
</li>
<li>
<p>Follow the steps provided in the readme file to customize and run the
application</p>
</li>
</ol>
<p><strong>Deploy your client-side-rendering web application</strong>
</p>
<ol data-tight="true" class="tight">
<li>
<p>Go to your App Dashboard</p>
</li>
<li>
<p>Click on upload to open the upload box</p>
</li>
<li>
<p>Upload your zipped source code</p>
</li>
<li>
<p>After vulnerability scanning the app will be available to use</p>
</li>
<li>
<p>Use the app URL from the app dashboard.</p>
</li>
</ol>
<p></p>