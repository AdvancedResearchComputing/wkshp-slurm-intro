---
title: "Administrative Issues and Workshop Layout"
teaching: 3
exercises: 0
questions:
- "What is SLURM?"
- "What are the prerequisites for this workshop?"
- "What topics will we cover?"
objectives:
- Understand the basic scope of SLURM for clusters.
- Make sure you have the course material (the web pages).
- Make sure you know the prerequisites for this class.
keypoints:
- Simple Linux Utility for Resource Management (SLURM)
- Resource management refers to tracking the status of cluster resources.
- Cluster resources include compute nodes and their CPUSs, memory, and GPUs.
- SLURM also provides workload scheduling functionality.
---



## Sign Up Sheet

The instructor should provide you with a URL for this workshop.

Sign up there.

## Prequisites for this Workshop

To follow along, you need to:

- have an account on ARC
- know how to ssh and log onto the ARC cluster Tinkercliffs (TC); and Owl cluster
- know how to edit text files with a command-line text editor such as `nano` or `vi`
- know how to create and move around directories on a Linux cluster (e.g. Unix Shell Basics)

## Accessing the Clusters On and Off Campus
- ARC clusters are only accessible from VT network.
- [VPN](https://www.nis.vt.edu/ServicePortfolio/Network/RemoteAccess-VPN.html) (virtual private network) needed for connections from off-campus
    - “VT Traffic over SSL VPN” connection recommended for most uses
- [Open OnDemand](https://ood.arc.vt.edu) provide shell access to clusters in a web browser.

~~~
ssh owl063
~~~
{:  .language-bash}

~~~
output from commands will appear like this, i.e., without a heading.
~~~
{:  .data}

## Overview

ARC systems run software that spans the full spectrum of modern research computing. SLURM (Simple Linux Utility for Resource Management) is a key tool used to manage cluster resources and job scheduling and is arguably the most commonly used scheduler/resource manager among HPC centers.

This workshop addresses basic Slurm scheduler interaction, cluster inspection, and job options. The demonstrations will be predominantly via the Linux shell command line interface and will make use of "software modules" system. Participants who already have ARC accounts are invited to follow along with the demonstrations if desired.


## How to Use These Workshop Materials


We will use the [Owl](https://docs.arc.vt.edu/resources/compute/01owl.html) cluster in this workshop, but the same commands and concepts will generally work on any ARC cluster.


{% include links.md %}

