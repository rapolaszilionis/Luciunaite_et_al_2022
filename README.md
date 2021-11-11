# ScRNAseq-related analyses for Luciunaite et al 2022 [1]


### Data
Large data files used by the code in this repository are stored on [GEO](link_to_add_when_avail)[GEO repository not set up yet].


### Methods

#### From reads to counts
The [solo-indrop](https://github.com/jsimonas/solo-in-drops) pipeline, which is a wrapper around [STARsolo](https://github.com/alexdobin/STAR/blob/master/docs/STARsolo.md), was used for obtain cells x genes matrices.
STARsolo expects as input two fastq files per library, one containing the barcode information and the other the transcript information. Meanwhile, the custom scRNAseq protocol used in the current study outputs 3 fastq files per library: barcode1, barcode2, and transcript. Solo-indrop prepares the data for compatibility with STARsolo.


#### Filtering, visualization and annotation
The first 4 notebooks describe analysis steps from raw counts to visualized (UMAP) and annotated filtered data.
	
#### Analyses using annotated data
The rest of the notebooks describe analyses using annotated data, such as enriched gene identification, population abundance comparisons, cell cycle scoring.

### References   
[1] To be updated after publication 
