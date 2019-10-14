# Efficient Graph Based Algorithm

While object detection has impacted several industries,
much remains unanswered in cancer cell detection using
Pap smear microscopy. This project introduces a
machine learning algorithm that detects and crops
regions of interest (ROI) before scrutinizing cells for
abnormal traits. Using digital images of cervical cells, we
automatically detect ROI’s following 3 main steps: (I) non
linear filters applied to RGB micrographs; (II) graph
based clustering using Felsenszwalb’s [1]; (III) definition
of super pixels with Isodata binary classification. This
process yielded the identification of the ROI with a
precision average of 92% and a recall average of 95%.
The resulting algorithm is at the core of the driver that
controls the motorized stage of our future smart
microscope that will enable scanning of full glass slides.

See Efficient_Graph_Poster_19.pdf
