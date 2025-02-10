# Vision Pipeline for Self-Driving Cars
This repository contains the submitted version of my dissertation for my final year project at Swansea University, Computer Science.
The project consisted of a vision-based pipeline for 3D reconstruction in the context of self-driving cars. Unfortunately, I'm currently unable to share the source code for the pipeline.

## Abstract
Abstract
Perception and scene understanding is one of the key components of self-driving cars. Over the
years, many traditional techniques for reconstructing the environment have been introduced,
followed by innovative methods exploiting the advancements in Deep Learning. Moreover, we
have seen the transition to more vision-based approaches, as cameras are a crucial exterocep-
tive sensor due to their range of benefits for the self-driving cars domain - they are cheap and
suitable for many Computer Vision applications, such as object detection or visual localisation.
In this document, we demonstrate the importance of Computer Vision and 3D reconstruction
research not only in the context of autonomous driving. Emphasis is placed on the use of
stereo visual input and leveraging Deep Learning techniques to enable perception in 3D space,
rather than being limited to the 2D image space. We present a comprehensive survey of various
methods used in typical reconstruction systems and show specific instances in both industry and
academia. Furthermore, we demonstrate a system for generating dense and accurate 3D recon-
struction of large-scale environments. Our system uses a modular pipeline consisting mainly
of modules for localisation, depth estimation, and semantic segmentation. The reconstructed
environment is integrated into a volumetric data structure with a multi-value hash map back-
end that uses parallelizable and spatial hashing for implicit surface representation. While our
processing pipeline prototype is far from being real-time, we provide an implementation using
modern methods and libraries that allow for faster performance via hardware acceleration and
parallelization. Our results mainly provide a proof of concept and demonstrate the usefulness
and importance of our method. We evaluate our results on the KITTI benchmark suite and
present suggestions for future work.
