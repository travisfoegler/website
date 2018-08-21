---
ID: 7304
post_title: 'Your Questions Answered: Alignment to Atlas Explained'
author: 'Luc Champagne - Applications Specialist'
post_excerpt: ""
layout: post
permalink: >
  https://www.cortechslabs.com/atlas-alignment/
published: true
post_date: 2017-09-20 05:15:27
---
The CorTechs Labs Support team is often asked to clarify error messages when a series of images cannot be processed by NeuroQuant software. The #1 question we receive has to do with alignment of brain to atlas being reported as unsuccessful.

<strong>Why is Alignment to Atlas Important?</strong>
To achieve high quality segmentation results, NeuroQuant aligns each patient’s brain image to an atlas of the brain. Segmentation accuracy can be affected when the patient's brain deviates from the reference brain atlas. Since correct brain atlas alignment is critical to the accuracy of the segmentation results, it is also critical to the accuracy of the calculated volumes.

<strong>What Does “Processing Failed: Alignment of Brain to Atlas Unsuccessful” Indicate?</strong>
This message will be displayed in cases where a patient’s brain anatomy is significantly different than the brain atlas, such as in patients with brain tumors, surgical resections, very large lesions, or severe asymmetry. Further processing of the scan may result in inaccurate segmentation. To ensure segmentation accuracy, NeuroQuant is designed with a quality check ensuring goodness of fit to neuroanatomical atlas

<strong>What is the Measurement Index?</strong>
The measurement index (MI) is a numerical measure of the similarity (or differences) between a patient’s brain scan and the anatomical brain atlas. The MI serves as a quality check to confirm goodness of fit to the brain atlas. The measurement index uses a cutoff value to reject any scan that can likely result in segmentation errors due to the brain atlas mismatch. For clinical use, the MI must be ≤5. Exceeding this alignment error threshold will cause processing to halt and an error report to be generated. A MI &gt;5 prevents NeuroQuant analysis of a patient’s brain, indicating brain anatomy that is significantly different than the brain atlas based on the quality check.

<strong>Can Images Still Be Processed by NeuroQuant if the MI is &gt;5?</strong>
In some cases, yes. When the MI is between 5 and 6, turning on Research Mode allows NeuroQuant to process images for research/non-clinical needs with relaxed atlas alignment checks, like in cases, for example, that failed due to the brain atlas alignment error. Research mode generates reports marked NOT FOR CLINICAL USE. The Research Mode setting increases tolerance for certain alignment errors, but requires careful review of segmentation output by the radiologist to verify segmentation quality.

In the example below, gross structural abnormalities in a patient’s brain make good alignment to atlas impossible.

<a href="https://www.cortechslabs.com/wp-content/uploads/2017/09/not-good-fit-for-NQ.png"><img class="alignnone size-full wp-image-7305" src="https://www.cortechslabs.com/wp-content/uploads/2017/09/not-good-fit-for-NQ.png" alt="" width="800" height="297" /></a>

Some cases, such as the second example, can also generate this error message, but are still candidates for NeuroQuant, when processed in Research Mode.

<a href="https://www.cortechslabs.com/wp-content/uploads/2017/09/research-mode.png"><img class="alignnone size-full wp-image-7306" src="https://www.cortechslabs.com/wp-content/uploads/2017/09/research-mode.png" alt="" width="800" height="265" /></a>

More information about using NeuroQuant can be found your user manual.