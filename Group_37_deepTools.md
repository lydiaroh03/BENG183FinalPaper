# deepTools: a Powerful Tool to Analyze and Process Deep Sequencing Data
### By Haesol Jung, Meiqi Lai, Lydia Roh

## Content 
1. [Abstract](#011)
2. [Introduction](#211)
3. [Key Features](#3) <br>
   3.1. [File Conversion](#311)<br>
   3.2. [Signal Normalization](#321)<br>
   3.3. [Compute Matrix](#331)<br>
   3.4. [Visualization Tools](#341)<br>

4. [Work Flow](#4) <br>
   4.1. [Correlation between BAM Files](#411)<br>
   4.2. [Coverage Check](#421)<br>
   4.3. [GC-Bias Check](#431)<br>
   4.4. [Assessing the CHIP Strength](#441)<be>

5. [Conclusion](#511)
6. [References](#611)


## 01 Abstract<a name="011"></a>

Next-generation sequencing (NGS) technologies have revolutionized genomics research. This technology generates massive datasets that require tools for efficient analysis and visualization. deepTools is a collective bioinformatics tool designed to address these challenges, particularly for epigenomics and transcriptomics studies. This paper provides an in-depth overview of deepTools, its key features, and its application in workflows. With its ability to streamline the processing of genome-wide coverage files and generate high-quality visualizations, deepTools is a useful resource for researchers to navigate the complexities of high-throughput sequencing data.

## 02 Introduction<a name="211"></a>

deepTools is essentially a collection of tools, used primarily in the Bioinformatics field, designed for analysis and visualization of data obtained from Next Generation Sequencing Technologies[Chip-Seq, RNA-Seq, ATAC-Seq]. It is useful in the way that the design of the toolkit allows for it to handle large datasets, making it easier for researchers to use for processing, quality control as well as visualization purposes.

## 03 Key Features<a name="3"></a>

### 3.1 File Conversion <a name="311"></a>

One of the core functionalities of deepTools is the conversion of large, raw data files into smaller, more efficient formats. BAM files, which store aligned sequencing reads, are often unwieldy and challenging to work with for downstream analyses. deepTools provides tools like `bamCoverage` and `bamCompare` to convert BAM files into bigWig files, a binary format optimized for storage and visualization.

### 3.2 Signal Normalization <a name="321"></a>

Normalization ensures that data comparisons between samples, conditions, or replicates are biologically meaningful. Variations in sequencing depth, library size, or experimental conditions can introduce biases that skew results. deepTools supports several normalization methods, including Reads Per Kilobase per Million (RPKM), Counts Per Million (CPM), and SES (Simple Scaling).

### 3.3 Compute Matrix <a name="331"></a>

The `computeMatrix` tool prepares data for visualization by organizing signals from bigWig files around regions of interest defined in BED files. This step is essential for creating heatmaps and profile plots.

### 3.4 Visualization Tools <a name="341"></a>

deepTools includes powerful visualization options, such as `plotHeatmap` and `plotProfile`, which enable researchers to interpret complex datasets visually. Heatmaps, for example, can display enrichment patterns across multiple conditions or datasets, while profiles provide average signal distributions.

## Work Flow<a name="4"></a>
### 1) Correlation between BAM Files <a name="411"></a>
### 2) Coverage Check <a name="421"></a>
### 3) GC-Bias Check <a name="431"></a>
### 4) Assessing the CHIP Strength <a name="441"></a>


