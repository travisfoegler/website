---
ID: 7728
post_title: Understanding Change Data in LesionQuant
author: 'Marilyn Maes - Applications Specialist'
post_excerpt: ""
layout: post
permalink: >
  https://www.cortechslabs.com/change-data/
published: true
post_date: 2018-04-03 05:08:59
---
Did you know that the <a href="http://www.cortechslabs.com/lesionquant">LesionQuant module</a> offers lesion and brain structure change data for review?

Lesion and brain structure change data is available when a current and prior LesionQuant study have been processed and are available in the system. Change values of lesions are determined by using both 3D T1 and (2D or 3D) T2 FLAIR MRIs.

<strong>Morphometry Results
</strong>The change calculation of brain structures provides the difference between the current and prior scan brain volumes, % ICV and normative percentile.

<img class="alignnone size-full wp-image-7730" src="https://www.cortechslabs.com/wp-content/uploads/2018/03/change-results.png" alt="" width="1349" height="430" />

Data from the prior study will also be included in the report for both lesions and brain volumes. Additionally, <a href="http://multi-time-point-plotting">multi time point plotting</a> displays the current and prior measurements on the same same report, allowing for ongoing patient evaluation with longitudinal tracking.

<strong>Lesion Results</strong>
<ul>
 	<li>Compare lesion count, volume and %ICV to prior scan</li>
 	<li>Review new and enlarging lesions, and the sum of the new and enlarging lesions</li>
 	<li>Evaluate where new and enlarging lesions are anatomically located, and examine the count of new lesions and the volume of new, enlarging and the sum of the new and enlarging lesions</li>
</ul>
<img class="alignnone size-full wp-image-7732" src="https://www.cortechslabs.com/wp-content/uploads/2018/03/lesion-results.png" alt="" width="1313" height="484" />

<strong><img class="wp-image-7731 alignright" src="https://www.cortechslabs.com/wp-content/uploads/2018/03/lesion-distribution.png" alt="" width="249" height="254" /></strong>

&nbsp;

<strong>Lesion Size Distribution Histogram
</strong>The histogram of lesion size distribution displays number of lesions within each lesion size bracket for current and prior scans. This data can characterize global lesion changes and provide an indication of disease progression.

<strong>Reproducibility and Comparison Best Practices
</strong>It is best practice to perform the current MRI on the same MRI scanner and series protocol as the prior MRI. If different scanners and/or protocols are used, caution should be taken when interpreting the results.

<strong>When patient data is already in the system
</strong>If an earlier scan for the patient has been processed by LesionQuant (same software version) and is available in the system, change volume images are automatically included in the output sent to the PACS/DICOM Viewer. The PatientID must match on both time points, and the StudyInstanceUID must match on the individual T1/FLAIR pair.

<strong>When patient data is no longer in the system or there has been a change in the software version from the current scan
</strong>To obtain the change visualization, the user must reprocess the prior scan pair, then send the current scan pair for processing to receive the change analysis and volumes. The PatientID must match on both time points, and the StudyInstanceUID must match on the individual T1/FLAIR pair.

If the prior study is sent to LesionQuant for comparison reprocessing, it is important that the prior T1/FLAIR pair is processed completely before submitting the current T1/FLAIR pair.