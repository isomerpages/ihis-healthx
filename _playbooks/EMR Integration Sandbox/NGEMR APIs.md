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
</li>
</ol>
<p><strong>ADT^A01 Admit/Visit Notification</strong>&nbsp;</p>
<p>This trigger event is used when a patient is assigned a bed during admission
to a hospital or hospital outpatient department.&nbsp;</p>
<p>&nbsp;<strong>Context</strong>&nbsp;</p>
<p>Admitting a patient in Grand Central or rooming a patient in ASAP generates
an A01.&nbsp;</p>
<p>&nbsp;<strong>A01 Format Example</strong>&nbsp;</p>
<blockquote>
<p>MSH|^~\&amp;|EPIC|OUT|||20060107223644|TESTUSER|ADT^A01^ADT_A01|7431503|P|2.4||&nbsp;</p>
<p>EVN|A01|200601072236|||TESTUSER^USER^TEST^^^^^^SA^^^^^LOC|&nbsp;</p>
<p>PID|||ZZZ980019060^^^^EPI||TEST^MONICA^^^^||19001102|F||1|8878 TEST AVE^^BLUE
FIELD^MN^55104^US^^^&nbsp;</p>
<p>RAMSEY|RAMSEY|(608)271-9000^P^H^^^608^2719000||10|1|35|H27418|111-11-1111|||1||||||||N&nbsp;</p>
<p>PD1||||&nbsp;</p>
<p>NK1||TEST^CONTACT^^^^|SO||(608)271-9000^P^H^^^608^2719000|(608)271-9000^P^H^^^608^2719000|CONTACT1|||||||||||||||||||||||||||&nbsp;</p>
<p>PV1||I|UNIT^10^10^^^^LOC^^|2||||||MSURG||||7|||||C987604215&nbsp;</p>
<p>67|||||||||||||||||||||||||200601072236||||||&nbsp;</p>
<p>PV2||||||||||||||||||||||N||Adm*Conf||||||||||||||||&nbsp;</p>
<p>GT1|1|ZZZ587615|TEST^MONICA^^^^||8878 TEST AVE^^&nbsp;</p>
<p>BLUE FIELD^MN^55104^US^^^RAMSEY|(608)271-9000^P^H^^^608^2719000||19001102|F|P/F|15|111-11-1111|||||^^GREENPLAINS^MN^55408^US|||None|||||||||||&nbsp;</p>
<p>UB2|||||||&nbsp;</p>
</blockquote>
<p>&nbsp;</p>
<p><strong>ADT^A02 Transfer a Patient</strong>&nbsp;</p>
<p>This trigger event is used when a patient is transferred within the ADT
system.&nbsp;</p>
<p><strong>Context</strong>&nbsp;</p>
<p>Transferring a patient between hospital units, from the ED to a unit,
or transferring beds within the ED will generate an A02.&nbsp;</p>
<p><strong>A02 Format Example</strong>&nbsp;</p>
<blockquote>
<p>MSH|^~\&amp;|EPIC|EHS|||20170526133527|OBUTESTUSER|ADT^A02^ADT_A02|569|T|2.3&nbsp;
<br>EVN|A02|20170526133527||ADT_EVENT|OBUTESTUSER^OBSTETRICS^UNIT^CLERK^^^^^EHS^^^^^EHSMH|20170214152036&nbsp;
<br>PID|1||ZZZ44029^^^EPIC^MRN~ZZZ1203713^^^EPI^MR||TEST^DOLORES^^^^^D||19000210|F|||^^^^^US^L|||||||H4000544|111-11-1111|||||||||||N&nbsp;
<br>PD1|||TEST HOSPITAL^^10101&nbsp;
<br>PV1|1|INPATIENT|ZZZ10205^L\T\D TRIAGE-333^333-01^^R^^^^^^DEPID|EL||ZZZ10205^L\T\D
TRIAGE-332^332-01^^R^^^^^^DEPID||||Obstetrics||||Non-Healthcr|||||C42271003|SELF||||||||||||||||HOME|||||Adm*Conf|||20170210172000|||30650.88&nbsp;
<br>PV2||||||||||||||||||||||N&nbsp;&nbsp;</p>
</blockquote>
<p>&nbsp;<strong>ADT^A03 Discharge/End Visit</strong>&nbsp;</p>
<p>This trigger event is used when a patient is discharged from the ADT system.&nbsp;&nbsp;</p>
<p>&nbsp;<strong>A03 – Patient Discharge</strong>&nbsp;</p>
<p>Discharging a patient, either in ADT or via a batch job that closes Hospital
Outpatient Visits, generates an A03. The interface can also generate an
A03 message when a Cadence appointment is checked out or completed.&nbsp;</p>
<p>&nbsp;<strong>Application Configuration</strong>&nbsp;</p>
<p>The ADT Unit Type in the department record determines whether the department
is an ambulatory department (blank), an Inpatient Unit, an ED, or a Hospital
Service department.&nbsp;</p>
<ul>
<li>
<p><strong>Profile Variables</strong>&nbsp;
<br>APPT_CHECK_OUT [3046]&nbsp;</p>
</li>
</ul>
<p>&nbsp;<strong>A03 Message Filtering</strong>&nbsp;</p>
<p>By default, the interface filters an A03 message from being sent if an
A03 has already been sent for the encounter with the same mnemonic in EVN-4.
This prevents external systems from receiving multiple A03s for the same
encounter, which is often problematic for other systems. This situation
may occur because scheduling users are allowed to check out a patient multiple
times.&nbsp;</p>
<p>If a scheduling user checks out a patient twice for the same encounter,
the interface only sends one A03 message because the mnemonic in EVN-4
is the same. However, if another event for the encounter causes the interface
to generate an A03 message from another trigger set with a different mnemonic,
such as profile variable APPT_EOD_COMPLETE (6046), this A03 is sent from
the interface because it is considered different from the previous A03
due to the different mnemonic.&nbsp;</p>
<p>If necessary, you can configure your interface to use one of the following
A03 message filtering policies instead:&nbsp;</p>
<ul>
<li>
<p>Send only the first A03 message for an encounter. You might need to use
this filtering policy if your organization doesn't perform any selective
routing of A03 messages to specific external systems based on message characteristics.&nbsp;</p>
</li>
</ul>
<ul>
<li>
<p>Send all A03 messages. Most organizations don't need to use this option
because external systems typically can receive only one A03 for an encounter.&nbsp;</p>
</li>
</ul>
<p>In addition to specifying the A03 filtering policy, you can also define
exceptions to the policy by specifying which A03 messages are always sent
regardless of what A03s have already been sent for an encounter. When you
use this option, the interface always sends an A03 message if the mnemonic
in EVN-4 matches a mnemonic specified in profile variable A03FILTER_OVERRIDE_MNEMONICS
(5549).&nbsp;</p>
<ul>
<li>
<p><strong>Profile Variables</strong>&nbsp;
<br>A03FILTER_OVERRIDE_MNEMONICS [5549]&nbsp;
<br>ALLOW_MULTIPLE_A03 [5499]</p>
</li>
</ul>
<p><strong>A03 – Disassociate a Medication Management Device&nbsp;</strong>&nbsp;</p>
<p>The interface can generate an A03 when a patient, visit, and workstation
record should no longer be associated with advice that documents the administration
of intravenous drugs. These messages work in conjunction with the Incoming
Anesthesia Medication Documentation interface to file medication administration
information to the patient's MAR.&nbsp;</p>
<p>The receiving system uses the patient identifier from PID-3, the visit
identifier from PV-19, and the workstation sent in an OBX segment to associate
the patient to the device.&nbsp;</p>
<p>&nbsp;</p>
<p><strong>Application Configuration</strong>&nbsp;</p>
<p>&nbsp;To generate the appropriate device registration message for anesthesia
application events, work with your organization's Anesthesia analysts to
modify event records:&nbsp;</p>
<ol>
<li>
<p>In Hyperspace, open your Start Data Collection event.&nbsp;</p>
</li>
</ol>
<ol start="2">
<li>
<p>Search: Event Template Editor&nbsp;</p>
</li>
</ol>
<ol start="3">
<li>
<p>Path: Epic button &gt; Admin &gt; Anesthesia Admin &gt; Event Template
Editor.&nbsp;</p>
</li>
</ol>
<ol start="4">
<li>
<p>In the Filing extensions field, enter extension 89295-AN Intelliport Disassociate.&nbsp;</p>
</li>
</ol>
<p>&nbsp;</p>
<ul>
<li>
<p><strong>Profile Variables</strong>&nbsp;
<br>AN_INJ_DEV_DISASSOCIATION [50411]&nbsp;</p>
</li>
</ul>
<p>&nbsp;</p>
<ul>
<li>
<p><strong>Errors</strong>&nbsp;
<br>INVALID PATIENT ENCOUNTER [15525]&nbsp;</p>
</li>
</ul>
<p>INVALID INTERFACE ID [15526]&nbsp;</p>
<p>INVALID MNEMONIC [15528]&nbsp;</p>
<p>PATIENT ID INVALID [15905]&nbsp;</p>
<p>&nbsp;</p>
<ul>
<li>
<p><strong>Build</strong>&nbsp;
<br>Extensions (LPP)&nbsp;</p>
</li>
</ul>
<p>&nbsp;
<br>&nbsp;<strong>A03 Format Example</strong>&nbsp;</p>
<p>MSH|^~\&amp;|EPIC|ALEX|||20250212000507|BATCHCAD|ADT^A03|4386567|T|2.3||||||UNICODE
UTF-8|||||&nbsp;</p>
<p>EVN|A03|20250212000507||APPT_EOD_COMPLETE|BATCHCAD^CADENCE^BATCH^ONE^^^^^JHS^^^^^JMC||&nbsp;</p>
<p>PID|1|S9183800A^^^NRIC^NRIC|S9183800A^^^P||AH TEST PATIENT 02^^^^MR.||19961120|M||MY|277^^^ORCHARD
ROAD^238858^SG^P^ORCHARD GATEWAY~^^^^^^^~^^^^^^^~^^^^^^^||8492 8392^P^WORK|84928392^P^WORK|EL|4||1448629|S9183800A|||||||||SG||A||
ZPD|||||||N|||||||||||N||||||M||||||||N|N&nbsp;</p>
<p>NTE|1||No ACP|No ACP||20241120094648&nbsp;
<br>PV1|1|OP|LANICPAL^^^ALEX^^^^^^^|HC||||||LSNICOMM||||2|||||100700026173|SELF||||||||||||||||||||||^^^NTFH^^^^^^^||20250211222224|20241104235900|||||||||&nbsp;</p>
<p>PV2||||||||20241104100000||||2527||||||||||N|Intra-Dept referral Ward
(Sub) {INTRA WARD} (ZZZ0902)^D^^^^^^^^09~Intra-Dept referral Ward (Sub)
{INTRA WARD} (ZZZ0902)^D^^^^^^^^ZZZ0902|||||||||N||||||||SUB|||||||||&nbsp;</p>
<p>ZPV||||||||||||||||||||||||||||||||||||||||&nbsp;</p>
<p>OBX|1|TX|CITY^CITY|1|Singapore|||||||||||||||||||||||||||&nbsp;</p>
<p>OBX|2|TX|Treatment_Category^TREATMENT SERVICE CODE|1|NC|||||||||20241104||||||||||||||||||&nbsp;</p>
<p>OBX|3|TX|Stu_Indicator^STUDENT VISA?|1|N|||||||||||||||||||||||||||&nbsp;</p>
<p>OBX|4|TX|Admission_Reason_One^ADMITTING CATEGORY|1|1|||||||||20250212||||||||||||||||||&nbsp;</p>
<p>OBX|5|TX|Treatment_Room^APPT STAFF|1||||||||||20241104||||||||||||||||||&nbsp;</p>
<p>OBX|6|TX|Dept_Code^APPT PROCEDURES|1||||||||||20241104||||||||||||||||||&nbsp;</p>
<p>OBX|7|TX|Donor_Indicator^ADT - ORGAN DONOR|1|N|||||||||||||||||||||||||||&nbsp;</p>
<p>OBX|8|TX|FP_Program^REG ADDL PAT CATEGORY 2|1|N|||||||||||||||||||||||||||&nbsp;</p>
<p>OBX|9|DT|Downtime_Date^REG ADDL ENC DATE 2|1|20241104|||||||||20241104||||||||||||||||||&nbsp;</p>
<p>OBX|10|TM|Downtime_Time^REG ADDL ENC TIME 1|1|1000|||||||||20241104||||||||||||||||||&nbsp;</p>
<p>OBX|11|TX|Billing_Attending_Provider^BILLING ATTENDING PROVIDER|1||||||||||20241104||||||||||||||||||&nbsp;</p>
<p>OBX|12|TX|Sub_Doc_Number^SINGAPORE - SUBVENTION DOCUMENT ID|1|S9183800A|||||||||20241104||||||||||||||||||&nbsp;</p>
<p>OBX|13|TX|Sub_Doc_Type^SINGAPORE - SUBVENTION DOCUMENT TYPE|1|P|||||||||20241104||||||||||||||||||&nbsp;</p>
<p>OBX|14|DT|Sub_Doc_Expiry_Date^SINGAPORE - SUBVENTION DOCUMENT EXPIRATION
DATE|1|21001231|||||||||20241104||||||||||||||||||&nbsp;</p>
<p></p>