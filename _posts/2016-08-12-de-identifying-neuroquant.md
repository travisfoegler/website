---
ID: 6567
post_title: 'When De-Identifying your NeuroQuant data: Things to consider'
author: 'Luc Champagne - Applications Specialist'
post_excerpt: ""
layout: post
permalink: >
  https://www.cortechslabs.com/de-identifying-neuroquant/
published: true
post_date: 2016-08-12 12:00:00
---
Did you know NeuroQuant can process de-identified data and CorTechs Labs’ products can even de-identify data for you in one step?

Have you ever run into the situation where you wanted to share a specific case during a conference or a talk, but hesitate knowing that de-identifying data can be painful if done after the fact, and that using DICOM* viewers to de-identify can remove DICOM tags from the data (which are essential to the success of NeuroQuant processing)? The end result = process failures.

<img style="width: 337px; float: right;" src="https://www.cortechslabs.com/wp-content/uploads/2017/02/3_ctxnode.png?t=1486616743416&amp;width=337&amp;name=3_ctxnode.png" alt="3_ctxnode.png" width="337" />

To help make de-identifying data easy and painless, CorTechs Labs added a feature to <span style="color: #c8042c;"><a style="color: #c8042c;" href="http://www.cortechslabs.com/resources/ctxnode/">CTXNode</a></span> (our secure cloud processing system)  so that that MRI scan data can be easily de-identified during the process of uploading to NeuroQuant, ensuring all required DICOM tags stay intact, while removing patient identifiers** not necessary for processing. When using CTXNode, configuring <strong>Privacy</strong> tab allows MRI scan data to be effortlessly anonymized. More infomation can be found in our <span style="color: #c8042c;"><a style="color: #c8042c;" href="http://www.cortechslabs.com/resources/ctxnode/">Quick Start Guide.</a></span>

If you are not using CorTechs Labs’ products for data de-identification, or you received an anonymized data set and have difficulty processing using NeuroQuant, as a first step, we recommend reviewing the required DICOM tags are present and have valid inputs. The DICOM tags are available in the <span style="color: #c8042c;"><a style="color: #c8042c;" href="http://www.cortechslabs.com/resources/technical-information/">CorTechs Labs DICOM conformance statement</a></span>*** If these tags are missing or the fields are empty, NeuroQuant will be unable to perform the proper calculations:

Patient module tags:
<ul>
 	<li>PatientsBirthDate (Only required for some reports if PatientsAge tag is missing)</li>
 	<li>PatientsSex (Only required for some reports)</li>
 	<li>PatientsAge (Only required for some reports if PatientsBirthDate tag and none of AcquisitionDate, ContentDate, StudyDate, or SeriesDate tags are set)</li>
</ul>
General equipment module tags:
<ul>
 	<li>Manufacturer (Required, unless data quality checks are disabled)</li>
 	<li>ManufacturersModelName (Required, unless data quality checks are disabled)</li>
</ul>
<strong>Questions?</strong>
If you need more information or are interested learning more about NeuroQuant DICOM tags, please <span style="color: #c8042c;"><a style="color: #c8042c;" href="http://www.cortechslabs.com/contact-support/">contact us</a></span>.

Like this post? You might also find these helpful.
<ul>
 	<li><span style="color: #c8042c;"><a style="color: #c8042c;" href="/dicom-image-viewers">Top 4 DICOM Image Viewers for NeuroQuant</a></span></li>
 	<li><span style="color: #c8042c;"><a style="color: #c8042c;" href="/neuroquant-in-research">Are You Using Neuroquant in Research?</a></span></li>
 	<li><span style="color: #c8042c;"><a style="color: #c8042c;" href="/ctxnode">Giving a Nod to the Node: Why You Should Be Using CTXNode</a></span></li>
</ul>
* DICOM (Digital Imaging and Communications in Medicine) supplies the industry standard for the exchange of medical images and related image information to facilitate the connection and communication of information between medical devices and systems.

** The NeuroQuant PDF output reports (and images contained within the PDF output report) are de-identified, however the DICOM file returned to users is not de-identified, as it still contains DICOM tags that may be used to identify the patient.

*** DICOM conformance statements provide a basis in determining and assessing the connectivity and operability between two products. DICOM conformance statement tags provides the necessary information needed to ensure smooth communication between systems and prevent loss of necessary or required files.

<img style="min-height: 1px!important; width: 1px!important; border-width: 0!important; padding: 0!important; margin: 0!important;" src="http://track.hubspot.com/__ptq.gif?a=343740&amp;k=14&amp;r=http%3A%2F%2Fcortechsnews.cortechslabs.com%2Fde-identifying-neuroquant&amp;bu=http%253A%252F%252Fcortechsnews.cortechslabs.com&amp;bvt=rss" alt="" width="1" height="1" />