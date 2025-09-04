# One-Class Lightweight Interpretable Filtering For Academic Profiles and Strategic Themes Affinity

- Marcos Paulo Silva Gôlo (ICMC/USP) | marcosgolo@usp.br
- Matheus Yasuo Ribeiro Utino (ICMC/USP) | matheusutino@usp.br

# Citing:

Under Review in LeanDL-HPC 2025

# Abstract 

Filtering affinity between strategic themes and academic profiles plays a key role in public policies, mainly in Brazil. Although large language models (LLMs) currently represent the state-of-the-art in text mining, they suffer from limitations such as high computational and financial costs, as well as substantial electricity consumption, leading to significant carbon emissions. These factors highlight the need for lightweight filtering mechanisms to avoid unnecessary LLM calls. Unsupervised similarity-based filters and binary classifiers also face challenges, including a lack of theme specificity and the requirement for large amounts of labeled data. To address these issues, we propose the use of theme-specific one-class learning, where classifiers are trained using only positive high-affinity examples, combined with the theme description and its keywords. This approach aims to reduce carbon emissions while maintaining filter performance. It requires only a small amount of labeled data, making it suitable even for themes with few known profiles, and provides theme-specific adaptability. We leverage embeddings derived from language models to ensure computational efficiency, and project these embeddings into two dimensions to guarantee interpretability, enabling visualization of the decision function and supporting parameter tuning. Our experiments demonstrate that the proposed approach outperforms a textual similarity baseline with similar carbon emissions, achieving higher f1-scores in identifying relevant pairs. Additionally, the method's interpretability proved valuable for understanding model decisions and generating insights into the data.
