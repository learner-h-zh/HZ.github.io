---
title: "Rotation-Invariant Feature Enhancement with Dual-Aspect Loss for Arbitrary-Oriented Object Detection in Remote Sensing"
collection: publications
category: manuscripts
permalink: /publication/2025-05-07-paper-Applied Sciences-number-1
excerpt: 'This paper proposes RFE-FCOS, which focuses on improving object detection in remote sensing imagery by incorporating multi-angle rotation-invariant learning. The method significantly enhances detection performance, particularly for arbitrarily oriented objects, achieving robust results on the DIOR-R and HRSC2016 benchmarks.'
date: 2025-05-07
venue: 'May 7'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://github.com/learner-h-zh/HZ.github.io/raw/master/files/RFE-FCOS.pdf'
bibtexurl: 'https://github.com/learner-h-zh/HZ.github.io/raw/master/files/RFE-FCOS.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Abstract: Object detection in remote sensing imagery plays a pivotal role in various applications, including aerial surveillance and urban planning. Despite its significance, the task remains challenging due to cluttered backgrounds, the arbitrary orientations of objects, and substantial scale variations across targets. To address these issues, we proposed RFE-FCOS, a novel framework that synergizes rotation-invariant feature extraction with adaptive multi-scale fusion. Specifically, we introduce a rotation-invariant learning (RIL) module, which employs adaptive rotation transformations to enhance shallow feature representations, thereby effectively mitigating interference from complex backgrounds and boosting geometric robustness. Furthermore, a rotation feature fusion (RFF) module propagates these rotation-aware features across hierarchical levels through an attention-guided fusion strategy, resulting in richer, more discriminative representations at multiple scales. Finally, we propose a novel dual-aspect RIoU loss (DARIoU) that simultaneously optimizes horizontal and angular regression tasks, facilitating stable training and the precise alignment of arbitrarily oriented bounding boxes. Evaluated on the DIOR-R and HRSC2016 benchmarks, our method demonstrates robust detection capabilities for arbitrarily oriented objects, achieving competitive performance in both accuracy and efficiency. This work provides a versatile solution for advancing object detection in real-world remote sensing scenarios.
Keywords: remote sensing images; object detection; rotation-invariant learning; feature fusion; dual-aspect loss; anchor-free network
<!-- Add the Download Link here in HTML format -->
<a href="{{ page.paperurl }}" download="RFE-FCOS-paper.pdf" class="download-button">
    Download
</a>
