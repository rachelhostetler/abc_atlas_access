# Whole adult mouse brain taxonomy of cell types

The Mouse Aging dataset [Jin et al] is a comprehensive single-cell RNA
sequencing (scRNA-seq) dataset containing ~1.2 million high-quality single-cell
transcriptomes of brain cells from young adult and aged mice of both sexes,
from regions spanning the forebrain, midbrain, and hindbrain. The 847 clusters
identified in this dataset are presented here with mappings into the [Whole
Mouse Brain Taxonomy](WMB-taxonomy.md).

The associated metadata is hosted on AWS S3 bucket as a AWS Public Dataset:

| Component | Current Version                                                                                                                                                                 | Size |
|---|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--|
| Metadata | [s3://allen-brain-cell-atlas/metadata/Zeng-Aging-Mouse-taxonomy/20241115](https://allen-brain-cell-atlas.s3.us-west-2.amazonaws.com/index.html#metadata/Zeng-Aging-Mouse-taxonomy/20241115/) | 0.01 GB |

Data is being share under the CC BY NC 4.0 license.

Related resources :
* Gene expression data and metadata ([Zeng Aging Mouse 10Xv3](Zeng_Aging_Mouse_10Xv3))

Associated notebooks:
* [**Getting started**](../notebooks/getting_started.ipynb): Learn how to use
  the AbcPorjectCache to facilitate data download and usage.
* [**10x scRNA-seq clustering analysis and annotation**](../notebooks/Zeng_Aging_Mouse_clustering_analysis_and_annotation.ipynb):
  Learn the aging mouse dataset metadata through some example use cases and
  visualization.
* [**10x scRNA-seq gene expression and ageDE genes**](../notebooks/Zeng_Aging_Mouse_10x_snRNASeq_tutorial.ipynb):
  Learn about the aging mouse gene expression and age differential expression
  genes through some example use cases and visualization.

