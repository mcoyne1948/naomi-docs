---
title: Installation Overview
source: https://github.com/naomiproject/naomi-docs/blob/dev/installation/index.md
currentVersion: 3.0
currentMilestoneVersion: 3.1.M0
currentNightlyVersion: Naomi-Nightly
meta:
  - property: og:title
    content: "Installation Overview"
  - property: og:description
    content: Naomi, The privacy focused personal assistant
---

# Installation Overview

Naomi is based on the Jasper framework and is fully written in Python.
As such, it only depends on a python installation, which is available for many platforms.
Although this should make it executable on different platforms, such as, **macOS** and **Windows** and different variants of **Linux** to date it has only been thoroughly tested on Raspberry Pi OS and Debian Buster.

If you are coming from Jasper please be aware of the fact that Naomi is programmed on a new base and introduces new concepts.
Therefore, tutorials and help you may find on the internet for Jasper **WILL** be outdated in respect to Naomi!

## Prerequisites

- **Hardware Platform**
  - RPi3 or recommended RPi4 or less than 7 year old laptop or desktop. The [Raspberry Pi (RPi)](rasppi.html) is our system recommendation, in large part because of its performance, popularity and cost effectiveness. In particular it offer a quick and relatively painless setup with our [Naobian](naobian.html) version of the Raspberry Pi OS with Naomi built in. However Naomi has been shown to work well on other platform desktop and laptop options running the Debian OS.
  - Speaker or headphones - Built in if available usual okay.
  - Microphone - Built in if available usual okay.
  - Or, voice all in one - Examples: USB headset or RPi SEED 2mic board plus a speaker work.
  - Internet - Optional, connection used for some plugins, such as, the weather forecast.
- **Software Environment**
  - Debian or RaspberryPi OS, recommend Buster. Please check the menu to the left for all currently available installation options.
  - Due to the way we have structured the setup of Naomi, there are no software prerequisites (Naomi handles all of that for you!). All you need to run Naomi is compatible hardware & OS.  

## Setup variants

Before you can start, two decisions have to be made:

1. Naomi is available as a platform independent archive file or through a package:
    - **Manual setup:** Download and extract a platform independent zip archive: [RPI](rasppi.html), [Linux](linux.html).
    - **Packaged setup:** Install though a package repository, built images, or an All-in-One Application: [Naobian](naobian.html), [Virtual Box](virtualbox.html), & [Docker](docker.html).

2. Stable release, Monthly release, or cutting edge:
    - **Stable:** (Current: **{{$page.frontmatter.currentVersion}}**) are thoroughly tested semi-annual official releases of Naomi. Use the stable version for your production environment if you don't need the latest enhancements and prefer a robust system.
    - **Milestone:** (Current: **{{$page.frontmatter.currentMilestoneVersion}}**) are intermediary releases of the next Naomi version, released about once a month, and they include the new recently added features and bug fixes. They are a good compromise between the current stable version and the bleeding-edge and potentially unstable nightly version. Milestones releases are **Highly Recommended** for most users.
    - **Nightly:** At most 1 or 2 days old and include the latest code. Use nightly for testing out very recent changes, but be aware some nightly versions might be unstable. Use in production at your own risk!

## Installation

Please follow the instructions in the installation page matching your platform (see the menu to the left). Once you have completed your installation you will find additional post-install assistance in the Setup and Usage section [here](./setup/index.md).

## Help

If you run into any problems, use the search function or open a new thread with your detailed question on the [Naomi Community Forum](https://support.projectnaomi.com).

<DocPreviousVersions/>
<EditPageLink/>
