This dataset was obtained as per permission by Dr. Chack-Yung Yu of the Nationwide Children's Hospital in Columbus, Ohio.  

Background ------------------------------------------------------------------------------------------
 
Systemic Lupus Erythematosus (SLE) is an autoimmune disease, causing inflammation and damage to various organ systems of the body.  While environmental factors that influence the onset of SLE are unknown, the disease primarily affects women and those of African and Chinese descent. 

Ongoing research has linked abnormally low levels of the C3 and C4 proteins of the body’s complement immune system to the disease, of which is of particular genetic interest as the number of genes that encode for the C4 protein vary from person to person, in other words C4 has Copy Number Variants (CNVs) ranging from two copies to over eight copies. To add onto this, C4 has two isoforms, long and short, differentiated by the presence or lack of an inserted retrovirus into the gene.

504 Hong-Kong originated East Asian SLE patients were accessed for C4 and C3 protein levels over several clinical visits. The mean and range of C3/C4 protein levels were recorded, and blood samples from each patient allowed for the determination of the number of total number copies of C4 present (C4T), and the breakdown of long (C4L) and short (C4S) isoforms.

Variables ------------------------------------------------------------------------------------------

Variable		Description
--------------------------------
patient No. 		Identifier/Key
C4 mean  		Quantatitive variable attributing to the mean concentration level of the C4 protein
C4 mean <10  		Boolean/Nominal variable used for grouping on whether C4 mean <= 0.10.
C4 range  		Quantatitive variable attributing to the variance/range present among C4 protein levels.
C3 mean  		Quantatitive variable attributing to the mean concentration level of the C3 protein.
C3 range 		Quantatitive variable attributing to the variance/range present among C4 protein levels.
C3 mean <80 		Boolean/Nominal  variable used for grouping on whether C3 mean <= 0.80.
Low C3, C4<10; MEAN	Boolean/Nominal  variable used for grouping on whether C4 mean <= 0.10 AND C3 mean <= 0.80. 
LOW C4, NOR C3		Boolean/Nominal  variable used for grouping on whether C4 mean <= 0.10 but C3 mean > 0.80.
C4T gene		Quantatitive variable attributing to total copy number of C4 (T = A+B = S+L)
C4A gene		Quantatitive variable attributing to copy number of C4A 
C4B gene		Quantatitive variable attributing to copy number of C4B
C4L gene		Quantatitive variable attributing to copy number of C4S	(Short) 
C4S gene		Quantatitive variable attributing to copy number of C4L (Long)

Interaction ------------------------------------------------------------------------------------------

This visualization utilizes Brushing and Linking in which data on the scatterplots/bar charts can be brushed/highlighted, with corresponding visual indicators (color/size changes) aligned to the linked data per each chart.  From this it is possible to see relationships among patients who had varying protein levels of C3 and C4 and their relationships with their own copy number variants in order to possibly indicate whether or not copy number variants of C4T/A/B/S/L had a link to protein levels without resorting to the Boolean values.








