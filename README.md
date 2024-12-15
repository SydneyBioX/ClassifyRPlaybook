# ClassifyR: Comprehensive evaluation of classification and time-to-event modelling of multi-view and multi-omics data.

The classification of patients based on prognostic biomarkers is a cornerstone of precision medicine, enabling the stratification of individuals for personalized therapeutic interventions. However, intrinsic heterogeneity across patients, both molecularly and clinically, presents a persistent challenge to the development of robust and universally applicable classification models. Recent advances have highlighted the potential of incorporating clinico-pathologic features alongside molecular biomarkers to address this complexity and improve the accuracy of outcome prediction.

ClassifyR was first introduced in 2015 by (Strbenac et al. 2015) as a tool designed for evaluating classification performance in omics research, with an emphasis on transcriptomics. The package allowed researchers to assess and compare predictive models systematically, focusing on model accuracy and interpretability. Since its initial release, ClassifyR has undergone continuous development to expand its capabilities and enhance usability, making it a versatile tool for tackling modern challenges in precision medicine. Notable advancements in the package include:

-   **Cross-validation capabilities for robust performance assessment:** ClassifyR now enables repeated cross-validation to evaluate model stability, feature selection reliability, and per-sample prediction accuracy. In particular, the per-sample prediction accuracy makes it possible to quantify the classifiability of particular samples in a cohort, or those that are consistently easy or hard to classify.

-   **Integration of multi-modality data, including single-cell and spatially resolved features:** Leveraging the principles of multi-view learning, ClassifyR supports analysis across multiple omics data modalities, such as transcriptomics, proteomics at multiple resolutions. ClassifyR leverages feature engineering strategies generated from scFeatures (Cao et al. 2022) and others.

-   **Development of decision pathways for precision medicine:** Inspired by advancements in clinical diagnostics, ClassifyR now incorporates frameworks for constructing and optimizing multi-platform precision pathways, as described by (Tran et al. 2024). These pathways use confidence scores to simulate clinical decision-making, striking a balance between diagnostic accuracy and cost-effectiveness.

-   **Evaluation of model transferability:** Cohorts can be different. ClassifyR makes it possible to at-scale evaluate the effectiveness of models built from one cohort on multiple independent cohorts. Further, it facilitates the construction of transferable models across cohorts (COP, TOP) that are robust to technical and cohort specific qualities.

## Feedback

If you notice an issue or missing information, please report an issue [here](https://github.com/SydneyBioX/spicyWorkBook/issues). We also welcome contributions in form of pull requests or feature requests in form of issues. Have a look at the source code at: <https://github.com/SydneyBioX/spicyWorkBook/issues>

## Contributors

[Ellis Patrick](https://github.com/ellispatrick)
