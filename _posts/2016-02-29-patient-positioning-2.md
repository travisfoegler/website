---
ID: 6556
post_title: 'Case Study: The Importance of Patient Positioning for Accurate NeuroQuant Analysis'
author: 'Luc Champagne - Applications Specialist'
post_excerpt: ""
layout: post
permalink: >
  https://www.cortechslabs.com/patient-positioning-2/
published: true
post_date: 2016-02-29 16:30:00
---
In this post we discuss a case study detailing the importance of properly positioning and land marking the patient when performing a <span style="color: #c8042c;"><a href="http://www.cortechslabs.com/neuroquant"><span style="color: #c8042c;">NeuroQuant®</span></a></span> volumetric analysis.

<img style="float: right; width: 120px;" src="https://www.cortechslabs.com/wp-content/uploads/2017/02/glabellar.png?t=1486616743416&amp;width=120&amp;name=glabellar.png" alt="glabellar" width="120" align="right" />When positioning a patient on the MRI table, land marking the X, Y and Z coordinates in the glabellar region is critical (see image). Land marking the patient in this region of the head, specifically the area between the eyebrows and above the nose, allows the center of the brain to align with the isocenter of the magnetic field. Magnetic field inhomogeneties are at their smallest magnitudes in isocenter. Therefore, positioning the head away from the isocenter in the + or – direction will cause greater distortion introduced by gradient nonlinearity.

If a sequence is acquired and uploaded to NeuroQuant with any of the X, Y or Z coordinates outside +/-100mm, automated volumetric analysis cannot be performed. An error message will be returned to the queue monitor and/or PACS. Below is an example of the NeuroQuant error message that would be generated in this case.

<a href="https://www.cortechslabs.com/wp-content/uploads/2016/02/error_message.png"><img class="aligncenter size-full wp-image-6319" src="https://www.cortechslabs.com/wp-content/uploads/2016/02/error_message.png" alt="" width="757" height="302" /></a>

Automated volumetric analysis is not possible in these instances. If NeuroQuant returns such an error message, re-scanning the patient with the scan origin centered appropriately is advisable.

<strong>Important note</strong>: If your patient is having an MRI performed on a body part other than the brain (i.e. cervical, thoracic, lumbar spine) it is very important to re-establish the glabellar region of the head as isocenter prior to acquiring the NeuroQuant volumetric scan.

<strong>Interested in learning more about how to ensure accurate NeuroQuant output results?</strong>
<ul>
 	<li>Explore the importance of using a 3D T1 sagittal MRI sequences for NeuroQuant analysis. You can read that blog post <span style="color: #c8042c;"><a style="color: #c8042c;" href="/3d-t1-sequences">here.</a></span></li>
 	<li>Review how to ensure accurate NeuroQuant processing results. You can read that blog post <span style="color: #c8042c;"><a style="color: #c8042c;" href="/neuroquant-processing-errors">here.</a></span></li>
 	<li>Understand why contrast agents are not used to achieve quality segmentation with NeuroQuant. You can read that blog post <a href="/contrast-agents"><span style="color: #c8042c;">here</span>.</a></li>
 	<li>Examine why good alignment to atlas is necessary. You can read that blog post <a href="/alignment-to-atlas"><span style="color: #c8042c;">here.</span></a></li>
</ul>
Additionally, more information about using and processing NeuroQuant can be found <a href="http://www.cortechslabs.com/resources/technical-information/"><span style="color: #c8042c;">here</span>.</a>

References:
<ol>
 	<li>Caramanos Z. et al. Gradient distortions in MRI: characterizing and correcting for their effects on SIENNA-generated measure of brain volume change. Neuroimage, 2010, Jan15:49(2):1601-11.</li>
</ol>
<ol start="2">
 	<li>Velthuizen R. et al. Review and evaluation of MRI nonuniformity for brain tumor response measurements. Med. phys. 25, 1655(1998).</li>
</ol>
<img style="min-height: 1px!important; width: 1px!important; border-width: 0!important; padding: 0!important; margin: 0!important;" src="http://track.hubspot.com/__ptq.gif?a=343740&amp;k=14&amp;r=http%3A%2F%2Fcortechsnews.cortechslabs.com%2Fpatient-positioning&amp;bu=http%253A%252F%252Fcortechsnews.cortechslabs.com&amp;bvt=rss" alt="" width="1" height="1" />