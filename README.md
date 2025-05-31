🧪 High School Project: Annotating Cell Types in Disease Using Scanpy

🗂️ Project Title
"Identifying Disease-Associated Cell Types in Single-Cell RNA-seq Data"

🎯 Project Goals
Learn basic principles of single-cell RNA-seq.


Use Scanpy to cluster and visualize cells from a disease dataset (e.g., cancer, autoimmune disease).


Annotate major cell types based on marker genes.


Identify cell populations that are enriched or altered in disease.



📊 Dataset Suggestions (Public & Well-Annotated)
Breast cancer tumor microenvironment
 GEO: GSE161529 — contains tumor and normal samples.


Lung adenocarcinoma immune landscape
 GEO: GSE131907 — includes immune cell profiling.


Ulcerative colitis
 HCA Data Portal: gut mucosa dataset


COVID-19 PBMCs (easy to interpret immune data)
 GEO: GSE150728


Let me know if you'd like help downloading or pre-processing one of these datasets.

🧬 Basic Analysis Workflow (Scanpy)
Preprocessing


Load .h5ad file or convert from .mtx or .loom


Filter cells and genes, normalize


Clustering & Dimensionality Reduction


PCA → UMAP


Leiden clustering


Marker Gene Identification


sc.tl.rank_genes_groups


Plot with sc.pl.rank_genes_groups_heatmap, dotplot, matrixplot


Annotation


Use canonical marker genes to label clusters


Cross-reference with databases like PanglaoDB, CellMarker


Disease-Relevant Insights


Identify cell types that are expanded, reduced, or uniquely present in disease



📅 Proposed Timeline (for ~4–5 weeks)
Week
Activities
1
Intro to single-cell data + Jupyter/Scanpy setup
2
Load & preprocess dataset; clustering & UMAP
3
Marker gene analysis; cell type annotation
4
Identify disease-associated populations
5
Finalize report or poster presentation


📘 Learning Materials
Scanpy tutorials


Webinars or videos from Chan Zuckerberg CELLxGENE


Optional: mini-lessons on Python, Pandas, Matplotlib, UMAP


