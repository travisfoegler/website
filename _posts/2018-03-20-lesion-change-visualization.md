---
ID: 7721
post_title: >
  Lesion Change Visualization with
  LesionQuant
author: 'Marilyn Maes - Applications Specialist'
post_excerpt: ""
layout: post
permalink: >
  https://www.cortechslabs.com/lesion-change-visualization/
published: true
post_date: 2018-03-20 05:31:14
---
Did you know that the <a href="http://www.cortechslabs.com/lesionquant">LesionQuant module</a> offers lesion change visualization images?

Lesion change visualization is available when a current and prior LesionQuant study have been processed and are available in the system. Change values of lesions are determined by using both 3D T1 and (2D or 3D) T2 FLAIR MRIs.

Similar to a heat map, regions are color-coded to identify increasing and decreasing image intensities between the current and prior scans.
<ul>
 	<li>Cyan/Dark blue indicates decreasing intensity, which may indicate decreasing lesion activity</li>
 	<li>Orange/Red indicates increasing intensity, which may indicate increasing lesion activity</li>
 	<li>Areas with no change in intensity are not colored</li>
</ul>
<img class="alignnone size-full wp-image-7723" src="https://www.cortechslabs.com/wp-content/uploads/2018/03/Intensity-changes.png" alt="" width="1723" height="600" />

<strong>Reproducibility and Comparison Best Practices:
</strong>It is best practice to perform the current MRI on the same MRI scanner and series protocol as the prior MRI. If different scanners and/or protocols are used, caution should be taken when interpreting the results.

<strong>When patient data is already in the system:
</strong>If an earlier scan for the patient has been processed by LesionQuant (same software version) and is available in the system, change volume images are automatically included in the output sent to the PACS/DICOM Viewer. The PatientID must match on both time points, and the StudyInstanceUID must match on the individual T1/FLAIR pair.

<strong>When patient data is no longer in the system or there has been a change in the software version from the current scan:
</strong>To obtain the change visualization, the user must reprocess the original scan pair, then send the new scan pair for processing to receive the change analysis and volumes. The PatientID must match on both time points, and the StudyInstanceUID must match on the individual T1/FLAIR pair.