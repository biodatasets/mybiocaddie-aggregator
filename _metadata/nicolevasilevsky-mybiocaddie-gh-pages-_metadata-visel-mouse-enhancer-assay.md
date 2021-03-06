---
layout: dataset
index: biocaddie
type: http://purl.org/dc/dcmitype/Dataset
title: Visel Mouse Enhancer Assay
identifier: FB00000169
date: 2016-09-09
accessURL: "https://www.facebase.org/data/record/#1/legacy:dataset/id=4277"
page: https://www.facebase.org/
taxa:
 - NCBITaxon:10090
keywords:
 - Enhancer reporter gene assay
references:
  - PMID:18836445
Enhancer location: Mouse genome mm9, chr14:47230349-47231452 
Enhancer Name: mCF73 
Vista Enhancer ID: mm387
Nearest craniofacial gene or locus: BMP4 
Enhancer expression: positive 
Tissues where active:
 - branchial arch
 - facial mesenchyme
 - nose
 - limbs
 - neural tube 
Comment on OPT files: slightly damaged embryo 
---

This data set includes the following:

A .pdf file that summarizes the whole-mount data for the tested element. This file includes light microscopy whole-mount images of the LacZ reporter gene expression in mouse embryos, a summary of the annotation of the expression pattern, the DNA sequence of the tested element in Fasta format, and the sequences of the primers used to generate the test construct. Follow corresponding link in the External References section to see this information in the [http://vista.lbl.gov](Vista Enhancer Browser) at Lawrence Berkeley Laboratory

4 movie (.avi) files: A CLIP file that provides an overview of the 3-D model generated by Optical Projection Tomography (OPT). Thresholding-based false-color representation shows unstained regions of the embryo in green, LacZ signal in red. In addition, 3 movies representing a pass-through view of the OPT model in the coronal, sagittal, or transverse plane. See links in External Referece section to download the following movie files: Overview movie, Coronal plane movie, Sagittal plane movie, Transverse plane movie

4 files in .tgz format. Each of these corresponds to one of the .avi files and unzips to a set of .png files, each of which represents the individual frames of the movie (and, in case of the transverse/sagittal/coronal movies, can be used to retrieve individual virtual sections through features of interest in .png image format). [.tgz files can be unzipped with WinZip or Stuffit on a PC or Mac. On linux, treat the file as a gzipped .tar file: `gunzip < file.tgz | tar xvf - `


