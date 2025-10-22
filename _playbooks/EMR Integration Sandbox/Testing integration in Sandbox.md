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
<p>Explore specifications for NGEMR APIs from Epic on FHIR web portal, or
the equivalent APIs in HealthX Innovation Sandbox.</p>
<p><a href="https://fhir.epic.com/Specifications" rel="noopener noreferrer nofollow" target="_blank">Epic on FHIR API Specifications</a>
</p>
<p><a href="https://staging-lite.d119f02n40zgqp.amplifyapp.com/ngemr-apis/" rel="noopener noreferrer nofollow" target="_blank">NGEMR Sandbox APIs</a>
</p>
<h4>2. Explore our HealthX EMR demo app</h4>
<p>The HealthX EMR demo app is developed using the above APIs.</p>
<p>To try the app,visit <a href="https://hxemr.healthx.sg/" rel="noopener nofollow" target="_blank">HealthX EMR Demo App</a>
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