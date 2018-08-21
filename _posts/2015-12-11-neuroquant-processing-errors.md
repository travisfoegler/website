---
ID: 6546
post_title: 'Case Study: How to Ensure Accurate NeuroQuant Processing Results'
author: 'Luc Champagne - Applications Specialist'
post_excerpt: ""
layout: post
permalink: >
  https://www.cortechslabs.com/neuroquant-processing-errors/
published: true
post_date: 2015-12-11 06:00:32
---
In this post, I review additional causes affecting goodness of fit which can result in NeuroQuant being unable to segment specific brain structures and issuing a processing error message. Previous posts discussed why <a href="/contrast-agents">contrast agents</a> are not used to achieve quality segmentation with <a href="http://www.cortechslabs.com/neuroquant/">NeuroQuant</a>, and examined why <a href="/alignment-to-atlas">good alignment to atlas</a> is necessary for accurate NeuroQuant output.

Ensuring proper processing is an important factor in NeuroQuant's analysis process. To achieve its high quality segmentation results, NeuroQuant verifies each patient's brain image can be processed correctly. This safeguards the accuracy of the segmentation results and therefore, the accuracy of the calculated volumes.

Patients who have shunts, implants or other artifacts or inherent abnormalities, can potentially generate segmentation misregistration. To prevent such errors and protect the accuracy of the results, NeuroQuant prevents analysis when such artifacts or anatomical anomalies are present.

In some cases, such as the first example below, a shunt in the patient’s brain made good alignment to atlas impossible, resulting in a processing failure.

<a href="https://www.cortechslabs.com/wp-content/uploads/2015/12/shunt.jpg"><img class="aligncenter size-full wp-image-6346" src="https://www.cortechslabs.com/wp-content/uploads/2015/12/shunt.jpg" alt="" width="558" height="298" /></a>In the second example, a patient's excess cranial tissue prevented proper processing and resulted in an error message.

<a href="https://www.cortechslabs.com/wp-content/uploads/2015/12/excess_tissue.jpg"><img class="aligncenter size-full wp-image-6345" src="https://www.cortechslabs.com/wp-content/uploads/2015/12/excess_tissue.jpg" alt="" width="568" height="298" /></a>More information about using and processing NeuroQuant can be found <a href="http://www.cortechslabs.com/resources/technical-information/">here.</a>