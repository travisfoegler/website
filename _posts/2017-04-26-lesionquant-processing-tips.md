---
ID: 7018
post_title: >
  Using LesionQuant? Follow these quick
  and easy processing tips for best
  results
author: 'Marilyn Maes - Applications Specialist'
post_excerpt: ""
layout: post
permalink: >
  https://www.cortechslabs.com/lesionquant-processing-tips/
published: true
post_date: 2017-04-26 05:49:34
---
<a href="https://www.cortechslabs.com/wp-content/uploads/2017/02/LQ_head-02.png"><img class="wp-image-6151  alignright" src="https://www.cortechslabs.com/wp-content/uploads/2017/02/LQ_head-02-238x300.png" alt="" width="126" height="159" /></a>The CorTechs Labs Support team is often asked why LesionQuant requires two different series - 3D T1 <u>and</u> 2D/3D FLAIR - to process. To address this question, we wanted to quickly review how LesionQuant processing works and provide some best practice quick tips.

<strong>But first, let’s quickly review how LesionQuant, a NeuroQuant product, works.</strong>

To begin, the LesionQuant module of NeuroQuant automatically processes the 3D T1 structural scan to provide volumetric information. During processing, the 3D T1 images are registered into NeuroQuant Dynamic Atlas space and anatomic brain structures are identified and labeled. Brain structure volumes are calculated and then normalized to ICV before comparison to age and gender specific normative reference data.

Next, LesionQuant uses the accompanying 2D or 3D FLAIR MR images to supplement and enhance lesion recognition and provide accurate, consistent and repeatable segmentation and quantification of lesions. Segmented lesions are aligned into patient brain space, based on the T1 segmentation, to allow regionalized reporting of lesion counts and volumes and are color-coded based on their anatomical location.

If more than one 3D T1 <u>and</u> 2D/3D FLAIR pair is provided, LesionQuant will report changes in lesion number and size and will provide an additional series as output with lesions color-coded to distinguish between increasing and decreasing volumes

<strong>And now, here are the LesionQuant processing best practices: </strong>
<ul>
 	<li>The Patient ID in the 3D T1 and FLAIR pair uploaded must match in order for LesionQuant processing to commence, and both series must be acquired in the same session (same StudyInstanceUID).</li>
 	<li>Both the 3D T1 and FLAIR scan must be sent to the same report type AETitle, matching the report desired (LesionQuant or LesionQuant PLUS).</li>
 	<li>The system will only start processing the data after both T1 and FLAIR series are received. If only one has been received the system will indicate which series is missing.</li>
 	<li>It may take up to several minutes for your series pair to be transferred (depending on network speed); once the upload completes, your series will automatically be queued for processing.</li>
 	<li>Check recommended scanner protocols for 2D or 3D FLAIR and 3D T1 MRI <a href="http://cortechslabs.com/resources/scanner_setup/">recommended scanner settings</a>.</li>
</ul>
<strong>Additional information about LesionQuant: </strong>
<ul>
 	<li>LesionQuant uses the additional image data available in the T2 FLAIR to supplement T1 based structural segmentation. This could result in subtle differences in structural volumes reported by LesionQuant when compared with NeuroQuant T1-only segmentations.</li>
 	<li>Lesion volumes are subtracted from brain structural volumes, which might also lead to small differences in reported brain volumes between LesionQuant and NeuroQuant.</li>
</ul>
<strong>Want more information about LesionQuant? Check out these blog posts:</strong>

<a href="https://www.cortechslabs.com/defining-lesions/">Defining and Classifying FLAIR Lesions in LesionQuant</a>

<a href="https://www.cortechslabs.com/quantitative-imaging-ms/">Quantitative Imaging in the Evaluation of Brain and Lesion Volumes</a>

<a href="https://www.cortechslabs.com/flair-lesion-visualization/">FLAIR Lesion Visualization with LesionQuant</a>

<a href="https://www.cortechslabs.com/lesionquant_webinar/">Watch Our Latest Webinar: An Introduction to LesionQuant</a>