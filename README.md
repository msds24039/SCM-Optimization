**1. Project Title**
SCM Optimization through Gen AI-Assisted Vendor Selection for Manufacturing a Particular Part

**2. Introduction**
This project applies generative AI models to optimize supply chain management (SCM) by improving vendor selection for manufacturing specific parts. It integrates clustering, process-to-technology mapping, and LLM evaluation to accurately infer technologies and rank vendors based on performance metrics.

**Key Features:**
_Vendor Clustering and Visualization:_
Clusters vendors based on their technological capabilities.
Provides 2D and 3D visualizations to understand vendor relationships.

_Process-to-Technology Mapping:_
Uses LLMs such as Llama, Qwen, GPT-Neo, and Custom GPT for mapping processes to technologies.
Employs few-shot prompting with reasoning for accurate mapping.

_Model Evaluation:_
Evaluates LLMs against ground truth data using metrics like accuracy and confusion matrices.
Refines training prompts and examples to improve performance.

_Vendor Selection:_
Matches technologies inferred by Custom GPT to vendor capabilities.
Supplements vendor ranking with QCD (Quality, Cost, Delivery) performance metrics.

**3. Installation Instructions**
Prerequisites:
Python 3.8+
Google Colab (optional for GPU acceleration)
Private datasets or sample data in the correct format (included in the data/ folder).

**4. Usage Guide**
Navigate to the notebooks/ folder.
Open a notebook SCM v5.ipynb which contains complete code for all sections.
Follow the cell instructions to replicate results.

**5. Results and Visuals**
**Vendor Clustering:**
2D Visualization and 3D Visualization are stored in results.
**Process-to-Technology Mapping:**
Results of each LLM responses are saved in results/gpt_neo_1_3b_predictions.xlsx etc
**Model Evaluation:**
Evaluation metrics, including confusion matrices and accuracy scores, are available in results.
**Vendor Ranking:**
Final rankings and QCD scores are stored in results.

**6. License Information**
N/A
