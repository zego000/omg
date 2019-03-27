Functional requirements
=======================

Input
-----
	The valid gene expression documents submitted are in the following format. This is a label.
A delimited plain text file with three columns (completeExample). The file contains an optional title line followed by each gene'Control samples (e.g. control samples) and treatment samples 

	=========	=============		==============
	gene_id		ControlSample		KnockOutSample
	=========	=============		==============
	AT1G01010       1.198558083        	2.036161827
 	AT1G01020       13.75736234             13.370796 
 	AT1G01030       0.833779536             0.203616183 
 	AT1G01040       9.58846466              7.126566394 
 	AT1G01046       0                       0 
     	AT1G01050       23.81482799             21.10821094 

        AT1G01060       0.625334652        	1.221697096 

	AT1G01070       1.719670292        	0.950208853 

	AT1G01080       28.34850421             25.24840665 
        
	AT1G01090       58.26034505             42.96301455 
	
        AT1G01100       1066.508249             1308.030358 

        AT1G01110       2.709783491             1.425313279

	========= 	=============		==============

Output
------
	The web application displays a table and a scatter plot given a gene expression file.
	The table contains a list of differentially expressed genes with the following
	format:

	========= =============== ============= ==========
	gene_id   control_sample  treat_sample  log_2[FC]
	========= =============== ============= ==========
	AT1G01010 1.198558083     2.036161827   0.76
	========= =============== ============= ==========

	The scatter plot showed different expressed genes. The X-axis is the control axis, and
The Y axis is treatment.
Replace "control" and "treatment" with the appropriate column name (if
Upload files. Up-regulated genes are expressed as red dots, down-regulated genes are expressed as red dots.
Genes are expressed in blue.
	

