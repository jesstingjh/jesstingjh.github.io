## About Me
I’m a Master’s student in Computational Data Analytics at Georgia Tech, with a strong foundation in economics and statistics from the National University of Singapore. Prior to grad school, I worked as a Senior Economist at Singapore’s Ministry of Trade and Industry, where I applied econometric modeling and data analytics to inform national policy decisions.

I enjoy applying machine learning and statistical techniques to uncover patterns, improve predictions, and generate actionable insights from complex datasets. Recently, I’ve been working on deep learning projects involving facial image reconstruction using diffusion models, LLM-based sentiment analysis, and schema-aware prompt generation from structured metadata. These are part of my broader effort to deepen technical skills through coursework and hands-on projects.

Outside of work, I enjoy puzzle games, bouldering, weightlifting, and trying new coffee brews. I also recently picked up scuba diving.

---

## Technical Skills
***Programming & Tools:*** Python (NumPy, Pandas, Scikit-learn, PyTorch, Matplotlib, Hugging Face, Mediapipe, dlib, pdf2image, pypdf), SQL, R, STATA, Tableau, Git; exposure to JS, D3
***Cloud/Big Data***: AWS, GCP, PySpark, Azure ML, Databricks   
***Statistics & ML***: 
- <u>Causal Inference</u>: DiD, Matching [CEM, PSM], RD, Synthetic Controls, A/B Testing, Survival Analysis
- <u>Machine Learning / Deep Learning</u>: Supervised/Unsupervised Learning, Neural Networks, Regression, Classification, Clustering, Random Forest, Anomaly Detection, Time Series, Image Reconstruction [DDPM], Prompt Engineering, Network Analysis
- <u>NLP & LLMs</u>: Sentiment/Topic Analysis, Transformers [BERT, DistilBERT], Token Augmentation, Schema-Aware Prompting, SHAP

---

## Projects
Below are some of the projects I have worked on as part of my coursework or personal interest. This section will be updated as I complete new projects      

***SLB – Knowledge Extraction Pipeline & Prompt Automation (Practicum Project)***
- Contributed to a modular data pipeline for extracting and structuring technical document content using OCR, pdf2image, pypdf, and layout-aware models, supporting LLM-based document querying
- Designed a Cognite-style Data Model based on sensor-derived activity recognition data to simulate SLB’s internal use cases, and developed schema-aware prompt generation functions for downstream, context-specific document retrieval

***Image Reconstruction with Structured Masking and Adaptive Noise***
- Trained a DDPM with U-Net backbone to reconstruct occluded facial images, using the FFHQ dataset with landmark-based region detection (Mediapipe, dlib), structured masking and adaptive noise to simulate realistic occlusions and enhance reconstruction and inpainting quality

***Context-Aware Sentiment Analysis of Yelp Reviews using Fine-Tuned DistilBERT*** [github](https://github.com/jesstingjh/contextual-sentiment-yelp)  
- Fine-tuned an LLM (DistilBERT) to predict positive reviews (4+ stars), incorporating contextual tokens from user and business data. Used stratified sampling, class-weighted loss, and F1-optimized thresholds to handle class imbalance
- Improved accuracy from 71% to 93%, and F1 score from 74% to 95%; used TF-IDF to identify key sentiment drivers across time, location, and business traits

***Cox Communications – Outage Detection using Customer Interaction Data*** 
- Placed 3rd in cohort-wide competition (MSA Project Week)
- Processed high-volume multichannel customer interaction logs and used anomaly detection models (MSTL, Isolation Forest) to detect latent outages not explicitly labeled in the data
- Developed a rolling-window Random Forest model for near real-time outage prediction, enabling faster remediation

***Hierarchical Clustering of Music Tracks for Better Genre Representation***      
(Group project for data and visual analytics class)
- Scraped 220k tracks using Spotify's API and applied stratified sampling and feature engineering (e.g., winsorization, PCA) to improve data quality and ensure balanced genre representation. 
- Implemented HDBSCAN and MBD-BIRCH clustering algorithms on a 128k track sample with parameter tuning, and developed an interactive dashboard to visualize and compare hierarchical clusters and track features
<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
    <img src="/assets/dva/dva_dashboard1.png" alt="Top Part" style="max-width: 100%; width: 200px;"/>
    <img src="/assets/dva/dva_dashboard2.png" alt="Bottom Part" style="max-width: 100%; width: 200px"/>
</div>      


***SNAP US Patent Citation Network Analysis*** [github](https://github.com/jesstingjh/patent-citation-network)
- Analyzed the citation network of US patents (1975-1999) using community detection and influence analysis techniques (Louvain & PageRank algorithms) on a dataset of 3.7 million patent nodes and 16.5 million directed citation edges
- Employed data sampling and preprocessing to handle computational complexity while preserving the network's structural integrity

***Network Monitoring*** [github](https://github.com/jesstingjh/network-monitoring)     
- Optimization project for water distribution network sensor placement using Python, Gurobi Solver and operations research / linear programming techniques 
- Formulated integer programs to place sensors across an 811-sensor, 1123-pipe network, minimizing sensor count while maximizing detection probability and prioritizing critical infrastructure locations 

---

## Education
**Georgia Institute of Technology**   
***MS Computastional Data Analytics, CGPA: 4.0/4.0*** *(2024-2025)*  
- Relevant coursework: Operations Research for Supply Chains (Linear Programming, Optimization), Machine Learning, Data and Visual Analytics, Graduate Algorithms, High-dimensional Data Analytics (Splines, Image, Tensor Analysis), Deep Learning (CNNs, RNNs. Attention, Transformers, PyTorch)   

**National University of Singapore**  
***BSc Economics (Honors), Highest Distinction, GPA: 4.88/5.00*** *(2015-2019)*   
- Specialisation: Quantitative Economics; Minor: Statistics; Special Program: University Scholars Program 
- Honors Thesis: "Dynamic Conditional Score Models: Forecasting Volatility of Exchange Rates"  
- Awards:  Faculty of Arts and Social Sciences Dean’s Scholars List (2 semesters), Dean’s List (4 semesters); University Scholars Program Honor Roll (2016), Senior Honor Roll (2017), and President’s Honor Roll (2019)   

---

## Work Experience
**Senior Economist** *(2020-2024)*    
***Ministry of Trade and Industry, Singapore***          
*Promoted from Economist to Senior Economist in 2024*    
- Drove data-intensive research involving causal inference and statistical modeling (R, STATA, Tableau) to support evidence-based policy; partnered with cross-functional and cross-agency teams to translate and contextualize research findings for senior management
- Formulated macroeconomic assumptions and scenarios for national long-term infrastructure planning
- Developed analytical frameworks by synthesizing economic literature to guide and enhance policy thinking and analysis processes
- Mentored interns in coding practices, policy contexts and econometric methodologies for research projects, strengthening team research capabilities and producing deliverables that shaped policy prioritization
- Contributed to high-impact organizational workstreams including the 2023 Budget and Committee of Supply debates, review of training material for new officers, and the development of the Economist Service competency framework

---

## Articles
- ["Increases in Autonomous University Cohort Participation Rate and the Labour Market"](https://www.mti.gov.sg/-/media/MTI/Resources/Economic-Survey-of-Singapore/2024/Economic-Survey-of-Singapore-First-Quarter-2024/FA_1Q24.pdf) *(2024)*
- ["The Contribution of Intangible Assets to Labour Productivity Growth in Singapore"](https://www.mti.gov.sg/-/media/MTI/Resources/Economic-Survey-of-Singapore/2022/Economic-Survey-of-Singapore-First-Quarter-2022/FA2_1Q22.pdf) *(2022)*
- ["Drivers of Labour Productivity Growth in Singapore"](https://www.mti.gov.sg/-/media/MTI/Resources/Economic-Survey-of-Singapore/2020/Economic-Survey-of-Singapore-Third-Quarter-2020/FA_3Q20.pdf) *(2020)*

---

## Professional Development
- Python Programming and Unstructured Text Analytics (Civil Service College Singapore) *(Feb 2023)*
- Machine Learning and Big Data Continuing Education Programme (American Economic Association) *(Jan 2023)*
- Using Text as Data: Methods and Applications (Barcelona School of Economics) *(Jul 2022)*
- Audited PhD Empirical Research Project Course (Singapore Management University) *(Jan 2022-Apr 2022)*
- Audited PhD Labor Economics Course (Singapore Management University) *(Mar 2021-May 2021)*