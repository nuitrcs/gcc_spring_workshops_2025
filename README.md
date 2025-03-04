# GCC Spring Workshops
This is a landing page for Genomics Compute Cluster workshops for spring quarter of 2025. From here individual workshop repositories and registration pages are linked.

This workshop series is designed to cover topics of interest to the research community that uses the Genomics Compute Cluster (GCC) at Northwestern. Most workshops can be attended ad hoc, but some of the content builds on itself from week-to-week, and some require attendance at the first workshop of the series, ‘Command line introduction’, so please read the description of each. These workshops will be held in-person on the Chicago campus. To participate fully, you will need to bring a laptop with you to each workshop.

## [Command line introduction](https://github.com/nuitrcs/gcc_command_line)

Working from the command line gives computational biologists access to many analysis tools and enables the creation of reproducible scripts. This workshop will introduce commands for file system navigation, teach attendees how to create and edit scripts from the terminal with the text editor nano, and introduce utilities for interacting with our high-performance computer cluster, Quest.

Prerequisites: This workshop assumes no prior knowledge of these tools but requires a laptop with a terminal application installed. Installation instructions will be emailed upon registration. This workshop is a prerequisite for many of the other GCC workshops this quarter.

Registration: <https://www.eventbrite.com/e/gcc-command-line-introduction-chicago-tickets-1245387119399?aff=oddtdtcreator>

## [STAR RNA-seq aligner](https://github.com/nuitrcs/star_aligner_workshop)

Read alignment or mapping is a computational process to determine where in the reference genome the short RNA reads originated from. This workshop will introduce how to perform read alignment using STAR (Spliced Transcripts Alignment to a Reference), a splice-aware aligner designed to specifically tackle many challenges involved in RNA-seq data mapping. We will introduce STAR’s alignment strategy and interactively work through each step of alignment using an example dataset. We will also discuss how STAR is incorporated in many Nextflow pipelines (for example nf-core/rnaseq).

Prerequisites: This workshop assumes no prior knowledge related to RNA-seq data processing but requires a laptop with a terminal application installed , and expects familiarity with working from the command line or attendance at the ‘Command Line Introduction’ workshop.

Registration: <https://www.eventbrite.com/e/gcc-star-rna-seq-aligner-in-person-tickets-1245400579659?aff=oddtdtcreator>

## [Peak calling with MACS2](https://github.com/nuitrcs/MACS2_workshop)

Peak calling is a computational method used to identify areas in the genome that have been enriched with aligned reads in ChIPseq and ATACseq datasets. This workshop will introduce Model-based Analysis of ChIP-Seq (MACS2), one of the commonly used peak callers, and demonstrate how to call peaks from aligned reads on Quest. We will introduce some basic MACS2 parameters and interactively work through each step of peak calling using an example dataset.

Prerequisites: This workshop requires a laptop with a terminal application installed and basic knowledge of working from the command line, or attendance at the ‘Command Line Introduction’ workshop.

Registration: <https://www.eventbrite.com/e/gcc-peak-calling-with-macs2-chicago-tickets-1245401281759?aff=oddtdtcreator>

## [Scaling up for high-throughput computing](https://github.com/nuitrcs/high_throughput_computing)

Computational genomics workflows are most useful when they handle many samples. This workshop will introduce bash variables and job arrays to help you scale up as efficiently as possible with the SLURM scheduling software on Quest. We will interactively work through converting scripts that analyze one sample to analyze any number of samples, so you can launch one script that will handle all your sequencing files.

Prerequisites: This workshop requires a laptop with a terminal application installed and basic knowledge of working from the command line, or attendance at the ‘Command Line Introduction’ workshop. A basic knowledge of running jobs on GCC is recommended but not required.

Registration: <https://www.eventbrite.com/e/gcc-scaling-up-for-high-throughput-computing-chicago-tickets-1245402896589?aff=oddtdtcreator>

## [Virtual environments for single-cell analysis](https://github.com/nuitrcs/virtual_environments_for_single_cell_analysis)

The number of software packages designed for single-cell RNA-seq analysis has increased dramatically since the advent of both the sequencing technology and more widely available GPUs. Setting up an environment with the correct software to use the GPUs on Quest requires attention to specific versions. In this workshop, we will walk through setting up a software environment with mamba that can be used on our GPUs from both the command line and from JupyterLab via Quest OnDemand, and we will discuss software version control more generally. Attendees will leave with a software environment that works for the ‘Spatial transcriptomics with Scanpy’ workshop the following week.

Prerequisites: This workshop requires a laptop with a terminal application installed and basic knowledge of working from the command line, or attendance at the ‘Command Line Introduction’ workshop.

Registration: <https://www.eventbrite.com/e/gcc-virtual-environments-for-single-cell-analysis-chicago-tickets-1245404862469?aff=oddtdtcreator>

## Spatial transcriptomics with Scanpy

Scanpy (single-cell analysis in Python) is a toolkit for single-cell gene expression data analysis using the programming language Python. This workshop will cover a basic tutorial for the use of Scanpy and related packages for analysis and visualization of spatial single-cell gene expression data, with a focus on explaining data types, and how to find and adjust different parameters of the included functions.

Prerequisites: This workshop requires a laptop. Attendance at the previous workshop, ‘Virtual environments for single-cell analysis’, is recommended but not required.

Registration: <https://www.eventbrite.com/e/gcc-spatial-transcriptomics-with-scanpy-chicago-tickets-1245404872499?aff=oddtdtcreator>


