**1. Project Title**
SCM Optimization through Gen AI-Assisted Vendor Selection for Manufacturing a Particular Part

**2. Introduction**
This project applies generative AI models to optimize supply chain management (SCM) by improving vendor selection for manufacturing specific parts. It integrates clustering, process-to-technology mapping, and LLM evaluation to accurately infer technologies and rank vendors based on performance metrics.

**Key Features:**
Vendor Clustering and Visualization:

Clusters vendors based on their technological capabilities.
Provides 2D and 3D visualizations to understand vendor relationships.
Process-to-Technology Mapping:

Uses LLMs such as Llama, Qwen, GPT-Neo, and Custom GPT for mapping processes to technologies.
Employs few-shot prompting with reasoning for accurate mapping.
Model Evaluation:

Evaluates LLMs against ground truth data using metrics like accuracy and confusion matrices.
Refines training prompts and examples to improve performance.
Vendor Selection:

Matches technologies inferred by Custom GPT to vendor capabilities.
Supplements vendor ranking with QCD (Quality, Cost, Delivery) performance metrics.

**3. Installation Instructions**
Prerequisites:
Python 3.8+
Google Colab (optional for GPU acceleration)
Private datasets or sample data in the correct format (included in the data/ folder).
