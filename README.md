# spicyWorkBook: Spatial analysis of high dimensional in-situ imaging technologies

Recent advances in highly multiplexed cell imaging technologies such as PhenoCycler, 
IMC, CosMx, Xenium, and MERFISH (and many more) have fundamentally revolutionized our 
ability to observe complex cellular relationships in tissue. Where previous immunohistochemistry 
protocols only allowed the visualization of cells that could be characterized by two 
or three surface proteins, cutting-edge technologies characterize cells with upwards 
of 50 proteins or 1000s of RNA in situ. These technologies enable precise classification 
of cell sub-types and provide an unprecedented depiction of cellular heterogeneity in a 
tissue environment. These technical developments have necessitated the development of a 
variety of new analytical approaches that are required to harness these new imaging technologies. 
In this workflow we will demonstrate how packages in scdney can be used to provide new insights 
into complex biological systems and diseases.

## Scope

This workflow explains the use of common R/Bioconductor packages to pre-process and analyse single-cell data obtained from segmented multichannel images.
While we use imaging mass cytometry (IMC) data as an example, the concepts presented here can be applied to images obtained by other technologies (e.g. CODEX, MIBI, mIF, CyCIF, etc.).
The workflow can be largely divided into the following parts:

1. Preprocessing (reading in the data, spillover correction)
2. Image-, cell-, and batch-level quality control, low-dimensional visualization
3. Cell phenotyping via clustering or annotation
4. Insights into cell localisation
5. Insights into cellular niches
6. Insights into cell marker expression
7. Patient/image classification

## Feedback

We provide the workflow as an open-source resource. It does not mean that
this workflow is tested on all possible datasets or biological questions and 
there exist multiple ways of analysing data. It is therefore recommended to
check the results and question their biological interpretation.

If you notice an issue or missing information, please report an issue
[here](https://github.com/SydneyBioX/spicyWorkBook/issues). We also
welcome contributions in form of pull requests or feature requests in form of
issues. Have a look at the source code at:

[https://github.com/SydneyBioX/spicyWorkBook/issues](https://github.com/SydneyBioX/spicyWorkBook/issues)

## Contributors

[Alex Qin](https://github.com/alexrunqin)
