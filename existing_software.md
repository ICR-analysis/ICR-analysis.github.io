---
layout: page
title: Existing Software
permalink: /existing-software/
---

## Choosing microscopy software
 

The microscopy facility in Chelsea has licenses for a number of image analysis packages, along with experience in using many different programs. If you are unsure about any aspect of image analysis, please <a href='mailto:adam.tyson@icr.ac.uk'>email</a>, or come to the facility.

It is also much easier to develop your analysis pipeline before acquiring most of your data, please plan ahead!

### Open-source software:

#### Advantages:
* **Free** – you can install the software on as many machines as you like, for as long as you like.
* **Reproducible** – any researcher, in any lab can reproduce, and build upon published research without having to pay for the software.
* **Dynamic** - new features are added constantly. New algorithms are often made available with the paper (or often with a preprint).
* **Open** – you and the community can understand all the analysis carried out on your images.
* **Little (or no) licensing** - likely possible (if not easy) to use in a high performance computing environment.

#### Disadvantages:
* **Ease of use** - some software can be daunting to use at first, and can be more difficult to install.
* **Support** - user support will vary (but sometimes better than commercial solutions).
* **Availabilty** - some algorithms do not have an open source version available.
 

**FIJI (ImageJ):** Perhaps the most popular image analysis software, with hundreds of plugins to carry out nearly every kind of image analysis. Fairly easy to use (with no prior experience needed), but requires some trial and error. Macros can be written to automate analysis, but it is designed to analyse one image at a time. 3D support is somewhat limited. Many different plugins can be added fairly easily, but their support varies from non-existent to exceptional.

**Cell Profiler and Cell Profiler Analyst:** Complementary to FIJI in that Cell Profiler allows automatic analysis of thousands or even millions of images, particularly from high-content, plate-based systems. Slightly easier to use than FIJI due to the extensive help documentation, and that most features are supported by one central team. Although cell profiler is less flexible than FIJI (fewer features), it is likely to be more suitable for many standard imaging experiments. 3D support is also somewhat limited.

Cell profiler analyst is designed to work with data processed with Cell Profiler and can be used for automatic, machine-learning based image classification.

**Vaa3D:** Less flexible than FIJI, and lower throughput than Cell Profiler, but designed for 3D (and above) datasets. Particularly useful for visualisation of 3D images and for tracing of projections, but a number of other plugins are available.

**Ilastik:** Has a number of features, but the unique feature is pixel-based classification. This is a machine learning approach which is useful when features of interest cannot be detected using intensity alone (such as brightfield images).
### Commercial software:

#### Advantages:
* **Ease of use** - often much easier to install and use. The software interface may be more familiar.
* **Specific** - works well with specific data types (i.e. MetaXpress with data from the ImageXpress).
* **Proprietary algorithms** - intellectual property means that some algorithms are not available elsewhere.
* **Support** - software may have a helpline etc. (this varys).

#### Disadvantages:

* **Often expensive** - ICR has licenses for some software packages, but these are limited.
* **Less reproducible** – other researchers can only replicate your method if they invest in expensive software.
You may need to continue to pay for the software to access analysis from old projects.
* **Less dynamic** – new developments can take a long time to be implemented, and may only be available for an additional cost.
* **Less flexible** – if you perfect your image analysis pipeline, but then move to another microscope, you may have to start from scratch.
* **Often proprietary** - also a disadvantage, you may not know exactly what analysis you are performing.
* **Restrictive licenses** - may not be possible to use on your own machine, or with high performance computing resources.

**SlideBook:** Image acquisition and analysis software from 3i, used on the spinning disks, wide-field and light-sheet systems. The easiest solution for some image processing (particularly light-sheet) and some basic image analysis and is currently very well supported both in-house and remotely by 3i. 

**Arivis:** Particularly useful for rendering of very large images (e.g. lightsheet).

**MetaXpress:** Operates the ImageXpress system, and can also be used for image analysis. A number of analysis modules exist, but new ones can be developed without much experience. The main advantage is that MetaXpress can read directly from the ImageXpress database and is probably the simplest way of analysing images from this system.

**Harmony:** Similar to MetaXpress, Harmony is the software used to run the Operetta system, and can be used for analysis.

**Columbus:** Separate analysis software from Perkin Elmer to analysis data from the Operetta, which can also be used for data from other systems.

**Celigo:** Operates the Celigo plate-based imager and can be used to analyse the data.
 
**Zen2009:** Used to operate the Zeiss 710 point-scanning confocal. Limited analysis options, but can be useful for some simple tasks.

**Volocity:** Flexible, if possibly outdated image analysis software for visualisation and analysis of data from any system.


