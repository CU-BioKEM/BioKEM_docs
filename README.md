# BioKEM_docs

## Goal
This guide will introduce new and existing users of the CU-Boulder BioKEM facility to processing EM data on GPU compute nodes hosted on Blanca.

## Contents

0. Overview
0. Getting started
0. Running software on Blanca with SBGrid

## Overview
The BioKEM computing server consists of three main parts: Petalibrary, Blanca, and SBGrid. In order to use the server, you will need to gain access to all three of these resources. Information on how to do this can be found in the [Getting started](README.md/#getting-started) section. In brief, you will host your dataset on Petalibrary, process it on GPUs within the Blanca computing cluster using software managed through SBGrid.

## Getting started

### Petalibrary
Petalibrary is CU's Research Computing (RC) files storage system. This service can be used to safely and securely store 100's of TBs of data for a modest cost. This system is well backed up, so you don't have to worry about losing valuable data. The other important aspect of this service is that you can securely mount it to other RC resources like Blanca for super fast file transfer.

You will need to request and allocation for you lab and have RC create a BioKEM-deposit folder that can be used to deposit images taken from the Krios. See [https://www.colorado.edu/rc/resources/petalibrary](https://www.colorado.edu/rc/resources/petalibrary) for more information and email [rc-help@colorado.edu](rc-help@colorado.edu) to requestion and allocation. We recommend requesting an allocation of about ~20TB/actively processing dataset. This service could also be a good long term storage option for already processed datasets.

### Blanca

### SBGrid

## Running software on Blanca with SBGrid
