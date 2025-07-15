---
permalink: /
title: "Brief Introduction"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Dr. Yang Li received his Ph.D. in Operations Research and Control Theory from the [School of Mathematics](https://www.math.sdu.edu.cn/) at [Shandong University](https://www.sdu.edu.cn/) in 2019, under the supervision of [Prof. Guojun Li](https://faculty.sdu.edu.cn/liguojun/zh_CN/index.htm). During his doctoral studies, he conducted joint research at the [Department of Bioinformatics and Genomics](https://cci.charlotte.edu/departments/department-of-bioinformatics-and-genomics/), [College of Computing and Informatics](https://cci.charlotte.edu/) at [The University of North Carolina at Charlotte](https://www.charlotte.edu/). He subsequently pursued postdoctoral training in the [Department of Biomedical Informatics](https://medicine.osu.edu/departments/biomedical-informatics), [College of Medicine](https://medicine.osu.edu/) at [The Ohio State University](https://www.osu.edu/) and later worked in R&D at [AstraZeneca plc](https://www.astrazeneca.com/). Since March 2024, he has been an assistant professor at the [School of Mathematics, Statistics and Mechanics](https://msm.bjut.edu.cn/), [Beijing University of Technology](https://www.bjut.edu.cn/). He is a recipient of the Beijing High-Level Youth Talent Award and has served as a guest editor for [*Frontiers in Genetics*](https://loop.frontiersin.org/people/2319558/overview).

Dr. Li’s research interests lie in gene regulatory network inference, transcription factor binding site prediction, and single-cell sequencing data analysis. He has authored [over 20 peer-reviewed publications](https://scholar.google.com/citations?user=yDq-Zf4AAAAJ&hl=zh-CN) in leading journals, including *Nature Communications*, *Nucleic Acids Research*, *Briefings in Bioinformatics*, *Bioinformatics*, and *iScience*. His work has been cited over 700 times ([Google Scholar](https://scholar.google.com/citations?user=yDq-Zf4AAAAJ&hl=zh-CN)), with a single article cited up to 190 times.

Research Experience
======
### **Assistant Professor**  
*Institute of Operations Research and Information Engineering*  
*School of Mathematics, Statistics and Mechanics*  
*Beijing University of Technology*  
*August 2024 – Present*  

**Research Focus:**  
- Developing algorithms using graph theory, combinatorial optimization, and machine learning to reconstruct regulatory networks driving cellular evolution from single-cell multi-omics data  
- Building combinatorial optimization and machine learning models to identify key features, interactions, and regulatory networks underlying phenotypes in single-cell multi-modal data  
- Designing deep learning methods for spatial transcriptomics to predict tissue modules and their regulatory networks  

### **Postdoctoral Researcher**  
*Chronic Obstructive Pulmonary Disease & Idiopathic Pulmonary Fibrosis R&D Unit*  
*AstraZeneca, Gaithersburg, MD, USA*  
*Supervisors: Mahboobeh Ghaedi (Principal Scientist), Rania Dagher (Associate Principal Scientist)*  
*March 2022 – April 2023*  

**Research Focus:**  
- Modeled pulmonary emphysema using iPSC-derived foam spheroid/COPD fibroblast co-culture systems with scRNA-seq analysis  
- Investigated susceptibility of alveolar type II progenitor cells in COPD using in vitro iPSC systems  
- Mapped cell lineage trajectories and key regulators in COPD and IPF via pseudotemporal analysis of scRNA-seq data  

### **Postdoctoral Researcher**  
*Departments of Biomedical Informatics & Neuroscience*  
*The Ohio State University Wexner Medical Center, Columbus, OH, USA*  
*Advisors: [Qin Ma (Professor)](https://cancer.osu.edu/find-a-researcher/search-researcher-directory/qin-ma), [Phillip G. Popovich (Professor and Chair of Neuroscience)](https://medicine.osu.edu/find-faculty/non-clinical/neuroscience/phillip-popovich-phd)*  
*January 2020 – March 2022*  

**Research Focus:**  
- Developed novel algorithms to construct gene regulatory networks, enhancer-driven regulons, and enhancer-driven GRNs from scRNA-seq and scATAC-seq data  
- Explored microglial roles in coordinating intercellular interactions for spinal cord injury repair via scRNA-seq  
- Studied vulnerability of the middle temporal gyrus in Alzheimer's disease through spatial transcriptomics analysis  
- Created deep learning models for simultaneous imputation and clustering of scRNA-seq data  
- Designed combinatorial biclustering algorithms for large-scale scRNA-seq and spatial transcriptomics data  
- Revealed differential regulation of chemokines in tumor-associated macrophages within tumor microenvironments  
- Built algorithms and DL models for transcription factor motif discovery from ChIP-seq, ChIP-exo, and ATAC-seq data 

Teaching Experience
======
### **Beijing University of Technology**  
*2024 – Present*  
- Instructed undergraduate and graduate courses in approximation algorithms, mathematical engineering, and integer programming  
- Developed specialized modules on mathematical applications in bioinformatics and intelligent radiotherapy  
- Led problem-solving sessions for engineering mathematics courses  

### **The Ohio State University**  
*2020 – 2021*  
- Taught computational genomics and machine learning courses for medical graduate students  
- Designed curriculum on single-cell epigenetics (scATAC-seq) and graph neural networks  
- Created modules on statistical pitfalls in bioinformatics for interdisciplinary data science courses  

### **Earlier Appointments**  
- Teaching assistant for international combinatorics course (UGA-SDU joint program, 2013)  
- TA for mathematical analysis in honors program (Shandong University, 2011) 

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
