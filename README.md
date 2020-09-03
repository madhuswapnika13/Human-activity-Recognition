# Human-activity-Recognition

Research in Human Activity Recognition is in massive demand due to its applications in
Health care domain, Computer Vision, Household safety and Robot Learning. Human
Activity Recognition (HAR) aims to identify the actions carried out by a person given a set of
observations of him/her and the surrounding environment.
Human activity recognition (HAR) is a widely studied computer vision problem.
Applications of HAR include video surveillance, health care, and human-computer
interaction. As the imaging technique advances and the camera device upgrades, novel
approaches for HAR constantly emerge. This review aims to provide a comprehensive
introduction to the video-based human activity recognition, giving an overview of various
approaches as well as their evolutions by covering both the representative classical literatures
and the state-of-the-art approaches.

DATA EXPLORATION:

 The video dataset contains six types of human actions (boxing, handclapping,
handwaving, jogging, running and walking) performed several times by 25 different
subjects in 4 different scenarios - outdoors *s1*, outdoors with scale variation *s2*,
outdoors with different clothes *s3* and indoors *s4*. The model will be constructed
irrespective of these scenarios.
 The videos were captures at a frame rate of 25fps and each frame was down-sampled
to the resolution of 160x120 pixels.
 The dataset contains 599 videos – 100 videos for each of the 6 categories (with the
exception of Handclapping having 99 videos). Next, there are some sample frames for
some videos from the dataset.
