---
title: "Administrative Issues and Workshop Layout"
teaching: 3
exercises: 0
questions:
- "How to make sure you get credit for this workshop?"
- "Where are the web pages for this presentation?"
- "What are the prerequisites for this workshop?"
- "What are the ideas behind the workshop and how is it structured?"
objectives:
- "Make sure you are signed up for the class."
- "Make sure you have the course material (the web pages)."
- "Make sure you know the prerequisites for this class."
- "Understand the exercises and how they relate to two ARC clusters."
keypoints:
- "Although we do not go into all of the details here, most
of the workshop uses the Tinkercliffs cluster, but because of how we
do the exercises, most/all of the material should also be directly applicable
to the Owl cluster."
---



## Sign Up Sheet

The instructor should provide you with a URL for this workshop.

Sign up there.


## Web Pages

This workshop has two major means to convey information:
- web pages.
- watch the instructor invoke commands.

The web pages can be downloaded.

## Prequisites for this Workshop

None, if you want to watch the workshop presentation.
There is value in just listening.

To do the exercises, you will need to

- have an account on ARC.
- know how to ssh and log onto the ARC cluster Tinkercliffs (TC); and Owl cluster.
- know how to edit text files with a command-line text editor such as `nano` or `vi`
- know how to create and move around directories on a Linux cluster (e.g. Unix Shell Basics)
- know how to transfer files back and forth between your personal computer and the ARC clusters.

## Accessing the Clusters On and Off Campus

- VPN (virtual private network) needed for connections from off-campus
   - https://www.nis.vt.edu/ServicePortfolio/Network/RemoteAccess-VPN.html 
- Nearly all ARC services require being on the campus network or VPN
- Use “VT Traffic over SSL VPN” connection 


## How to Extract the Web Pages.

* ***************** _this has to change with every delivery of this workshop_ ************************ *

1.  The files for the course are here:  _https://profdev-lms.tlos.vt.edu/courses/4381/files_
    - Download the latest _archive-job-monitoring-2024-11-08-v02.zip_.
2.  To follow along with the slides/web pages.
    - On your laptop, move the zip file to a new directory.
    - unzip the file.
    - under the \_site directory, you will see a file:  _index.html_.
    - double-click on that file.  It will show in your browser and you
can browse to all pages thereafter.
3.  If you want to do the exercises along with the instructor.
    - ssh to log in to Tinkercliffs (TC).
    - Create a new directory on TC where you want to work for this workshop.
    - We'll go through the steps from here.
    - ssh to log into Owl, and again we will go through instructions.
4.  Note:  Almost all files that we need for the exercises are in the web pages of the workshop materials.
    - This makes things more portable and more easily maintained.
5.  The web pages for this workshop have been designed to enable students to work on their own.
That is, they provide a fair amount of detail. 

~~~
ssh owl063
~~~
{:  .language-bash}

~~~
output from commands will appear like this, i.e., without a heading.
~~~
{:  .data}

## Overview

- ARC systems run software that spans the full spectrum of modern research computing.
- SLURM (Simple Linux Utility for Resource Management) is a key tool used to manage cluster resources and job scheduling.
- This workshop addresses basic Slurm scheduler interaction, cluster inspection, and job options.
- The demonstrations will be predominantly via the Linux shell command line interface and will make use of "software modules" system.
- Participants who already have ARC accounts are invited to follow along with the demonstrations if desired.


## How to Use These Workshop Materials


We will use the Owl cluster for almost all of the examples/exercises in this
workshop.


{% include links.md %}

