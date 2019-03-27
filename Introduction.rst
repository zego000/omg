Introduction
============
	This document describes the Little Hill Lab's initial requirements for an online
	application (Oh My Genes) which allows our scientists to upload gene expression files
	and quickly get differentially expressed genes.

Purpose
-------
	To identify differentially expressed genes given a gene expression file containing
	two cell samples.

Overview
--------
	

User characteristics
--------------------
	*	**clients:** Biologists who are using the web to get result of gene expression.
	*	**maintainers:** Biologists who have the knowledge of pythod and github.

Terminology&Glossary
--------------------
This Web application has a simple interface with only one button [upload and execute]. Ours
Scientists uploaded a plain text file containing two levels of gene expression.
Samples representing two experimental conditions. Accept documents, software
A differentially expressed gene list and a scatter map of these genes will be returned.
The X-axis is the control and the Y-axis is the therapeutic gene. If an invalid gene expression
If given, the Web application returns a page informing the user to provide
The format is correct.
Terminology
~~~~~~~~~~~ 
** Control sample * - Cell samples prepared under normal conditions.
** Processing Samples * - Cell Samples Treated with Special Chemicals, or Some of Their Genes
Changed.
Differentially expressed genes - genes with significant differences
The expression level between the two samples.
** Up * - If a gene
The treatment was better than the control group.

Glossary
~~~~~~~~
	*	*logFC* - log fold change of gene expression. log_2 [T/C], where T is the gene
	expression level from a treatment sample, while C is the gene expression level from a
	control sample.