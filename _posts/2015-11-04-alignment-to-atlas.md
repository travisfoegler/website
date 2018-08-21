---
ID: 6549
post_title: 'Case Study: Good Alignment to Atlas for NeuroQuant Accuracy'
author: 'Luc Champagne - Applications Specialist'
post_excerpt: ""
layout: post
permalink: >
  https://www.cortechslabs.com/alignment-to-atlas/
published: true
post_date: 2015-11-04 09:29:41
---
Previously, I discussed why using contrast agents is not necessary to achieve quality segmentation when using <a href="http://www.cortechslabs.com/neuroquant/">NeuroQuant</a>, and can, in fact, have a negative effect on the accuracy of the results, by degrading the technical quality of MR images. In this post,  I examine why good alignment to atlas is necessary for accurate NeuroQuant output and show two examples of NeuroQuant alignment to atlas error messages.

Alignment to atlas is an important step in NeuroQuant's analysis process. To achieve its high quality segmentation results, NeuroQuant aligns each patient's brain image to an atlas of the brain. A correct alignment is critical to the accuracy of the segmentation results and therefore, the accuracy of the calculated volumes. Cases where a patient's brain anatomy is significantly different than the brain atlas, can result in segmentation errors. To prevent such errors and protect the accuracy of the results, NeuroQuant is designed with a cut-off threshold for “goodness of fit” of alignment of a patient’s brain to a neuroanatomical atlas, thereby preventing analysis when anatomical anomalies exist.

It is important to note that NeuroQuant <a href="http://www.cortechslabs.com/autoalign/">automatically corrects</a> for a patient's head alignment in the scanner before doing its analysis, avoiding errors that could result from the position of the patient's head in the scanner.

In some cases, such as the first example below, gross structural abnormalities in a patient's brain make good alignment to atlas impossible.
<p style="text-align: center;"><a href="https://www.cortechslabs.com/wp-content/uploads/2017/02/large-ventricle.png"><img class="aligncenter size-full wp-image-6394" src="https://www.cortechslabs.com/wp-content/uploads/2017/02/large-ventricle.png" alt="" width="1710" height="647" /></a></p>
Some cases, such as the second example, can also generate this error message, but are still candidates for NeuroQuant. The criterion can be relaxed by enabling “Research Mode” in the NeuroQuant user interface, which may allow the scan to process correctly. However, segmentation output should be reviewed by a Radiologist to verify segmentation quality.

<a href="https://www.cortechslabs.com/wp-content/uploads/2017/02/small-ventricle.png"><img class="aligncenter size-full wp-image-6395" src="https://www.cortechslabs.com/wp-content/uploads/2017/02/small-ventricle.png" alt="" width="1293" height="1360" /></a>

More information about using  NeuroQuant can be found <a href="http://www.cortechslabs.com/resources/technical-information/">here.</a>