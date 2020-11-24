---
permalink: /
title: "What is OVIS"
excerpt: "Home"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

### Overview

**OVIS** (short for **O**ccluded **V**ideo **I**nstance **S**egmentation) is a new large scale benchmark dataset for video instance segmentation task. It is designed with the philosophy of perceiving object occlusions in videos, which could reveal the complexity and the diversity of real-world scenes.

<!-- Explore OVIS:
====== -->

### OVIS Consists of:

- 151k high-quality instance masks
- 25 commonly seen semantic categories
- 280 videos with severe object occlusions
- 1,840 unique instances

Given a video, all the objects belonging to the pre-defined category set are exhaustively annotated. All the videos are annotated per 5 frames.

### Distinctive Properties

- **Severe occlusions.** The most distinctive property of our OVIS dataset is that it primarily collects videos, wherein objects are under various types of occlusions caused by different factors. The resulting mBOR is 0.23.
- **Long videos.** The average video duration and the average instance duration of OVIS are 19.02s and 14.22s respectively.
- **Crowded scenes.** On average, there are 6.57 instances per video and 5.10 objects per frame.

### Visualization

![Various types of occlusions](images/occlusions_singlecol_crop_30.png)
