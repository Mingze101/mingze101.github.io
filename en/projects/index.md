---
title: "Projects"
layout: single
author_profile: true
toc: false
permalink: /en/projects/
---

> BUILD-CHECK: 42a7

## Karlsruhe Institute of Technology (KIT)

{% capture mt_content %}
- Designed and implemented an iterative **multi-agent debating** system to refine prompts for a mental-health support chatbot.
- Grounded the system in **Design Science Research**, with design principles informed by **Cognitive Load Theory** and **Adaptive Structuration Theory**.
- Automated **synthetic dialogue generation** and **GPTScore-based evaluation**, keeping domain experts in the loop via an interactive web interface.
- Conducted a **mixed-methods user study** (experts & lay users; **PHQ-9**, **NASA-TLX**, qualitative feedback) and derived prescriptive design implications.
{% endcapture %}
{% include details title="11/2024 – 04/2025 · Master Thesis — *Designing an Iterative Prompt Optimization System for Domain-Specific Chatbots*" content=mt_content open=true %}

{% capture ba_content %}
- Developed a BA chatbot using a **Retrieval-Augmented Generation (RAG)** pipeline and a **fine-tuned GPT-3.5** model.
- Implemented **mood tracking**, **personalized activity recommendations**, four **incentive mechanisms**, and **schedule management** via the Google Calendar API to support sustained engagement.
- Ran a **SurveyMonkey** user study *(n = 25)* to evaluate usability, mood-tracking accuracy, and impact on BA, showing positive effects on users’ self-management and well-being.
{% endcapture %}
{% include details title="11/2023 – 03/2024 · Behavioral Activation Chatbot" content=ba_content %}

{% capture eis_content %}
- Collected **multimodal data** (eye-tracking, HR, PPG, accelerometer, mouse clicks & movement) on an **ABB operator-training simulator** to study workload and performance in a realistic workplace.
- Designed analyses and visual reports to give operators and supervisors feedback on **stress**, **attention**, and **performance**.
- Prototyped a **biosignal-adaptive smartwatch interface**, exploring how physiological data can be integrated into everyday work to support safer and more efficient operation.
{% endcapture %}
{% include details title="11/2023 – 03/2024 · Engineering Interactive Systems & EIS Capstone Project" content=eis_content %}

{% capture kg_content %}
- Implemented **entity/relation extraction** from questions and **SPARQL** over a domain KG.
- Verbalized relevant triples and conducted **prompt engineering**.
- Evaluated with **SBERT similarity**, **ROUGE**, and **BLEU**.
- Improved **factuality** and grounding of our **KG-Mistral** pipeline vs. baselines.
{% endcapture %}
{% include details title="11/2023 – 03/2024 · Boosting the Performance of LLMs for QA with Knowledge Graph Integration [1]" content=kg_content %}

---

## FZI Forschungszentrum Informatik, Karlsruhe · HiWi (Student Research Assistant)

{% capture hv_content %}
- **Data preprocessing** and **data augmentation** for dermatology images.
- **FCN** model fine-tuning for **skin** and **psoriasis** mask segmentation.
- Built a pipeline for **ArUco marker** identification and **psoriasis area** calculation.
- **Clinical handover** and result interpretation with clinical and industry partners.
{% endcapture %}
{% include details title="07/2024 – 06/2025 · HybridVITA Project  [2]" content=hv_content open=true %}

---

{% capture okti_content %}
- Simulated **fixational eye movements** for dataset generation in **retinal OCT** B-scan volumes.
- Trained and evaluated **3D U-Net with CBAM** for **motion artifact correction**.
{% endcapture %}
{% include details title="06/2025 – Present · OKTI Project" content=okti_content %}

---

<small>
[1] **KGMistral** — OpenReview: <https://openreview.net/forum?id=JzL0qm3YA8>  
[2] **Perfusion Analysis for Telemedical Long-Term Monitoring of Patients with Chronic Skin Diseases** — IEEE Xplore: <https://ieeexplore.ieee.org/abstract/document/11166425/>
</small>
