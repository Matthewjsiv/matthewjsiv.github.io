---
title: Metadata Utils
tags: Class
type: article
cover: /assets/media/metadata/rotated-metadata_utils.png
show_date: false
show_edit_on_github: false
show_tags: false
footer: false
permalink: /projects/metadata_utils.html
show_subscribe: false
license: false
excerpt: "<ul> <li>Framework to automate the startup of modules for robot experiments/data-collection</li><li>Maintains metadata for easy data splitting/filtering to facilitate dataset creationc</li><ul>"
article_header:
  type: cover
  <!-- image:
    src: /assets/media/french_drone.png -->
---

<!-- *  Perception and high-level control system for drone to detect, track, and follow a person with onboard camera) -->
<!-- *  Uses Google's Posenet and hand-designed subject-visibility metrics -->

<!-- <p> preview excerpt </p> -->
<!-- - Bullet -->

<!--more-->

For running our off-road autonomy experiments, and even for data collection, we have several modules that need to be started. I came up with a tmux-based framework that allows you to pre-define an experiment beforehand, and run it with a single command once you're out in the field. It also maintains metadata that makes it easy to go back and find experiments based on various criteria. It's highly configurable, meaning that you can modify just a couple config files to integrate it into your own field-testing process.

At a high level it offers the following features:
*  Easy launching of experiments
*  A metadata system that is useful for organization and dataset creation
*  A "topics monitor" that makes sure all your information is being received at the expected rotate
*  A series of tools to organize the data

Our code can be found <a href="https://github.com/Matthewjsiv/metadata_utils" target="_blank"> <b> here</b></a>.


![](/assets/media/metadata/rotated-metadata_utils.png){: width="80%"}
