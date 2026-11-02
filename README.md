# MSHA-Accident-Narratives-Cause-Analysis

This repository contains the code, output reports, and validation materials for an NLP analysis of MSHA accident narratives. The study combines traditional text analytics, clustering, topic modeling, TF-IDF classification, and the locally executed Qwen2.5-7B-Instruct language model.

## Main Workflow

- Explores narrative terms, entities, clusters, and topics.
- Develops controlled ontologies for accident causes, contributing factors, and prevention themes.
- Applies the frozen classification system to 2,000 unseen narratives.
- Validates the results using 100 independently reviewed narratives.

The strongest results were obtained for primary accident causes. Contributing-factor and prevention-theme classifications should be treated as preliminary because short narratives often describe what happened without fully explaining why it happened.

This work is intended as a proof of concept for scalable, human-reviewed safety analytics. It is not an automated root-cause investigation or corrective-action approval system.
