# HAB-Detection
GAN Synthesized Dataset for Early Detection of Harmful Algal Blooms using Machine Learning models
This attribute set forms a robust framework for detecting Harmful Algal Blooms (HABs), combining key indicators like Bloom_Index, chlorophyll levels, and sea surface temperature anomalies. The parameters cover a range of biogeochemical factors crucial for HAB formation and impact assessment, including nutrient levels (Total_Nitrogen, Total_Phosphorus) and water quality metrics (Dissolved_Oxygen, pH).
The system's primary use is in HAB detection and monitoring in coastal waters. However, it has versatile applications:
1.	Fisheries Management: Helps predict potential fish kill events by tracking Dissolved_Oxygen levels and Bloom_Index, allowing for timely interventions.
2.	Climate Change Research: The Rolling_SST_Anomaly and long-term pH trends can contribute to studies on ocean warming and acidification impacts on marine ecosystems.
The model's training using Generative Adversarial Networks (GANs) is a significant innovation. GANs synthesize realistic datasets, addressing the challenge of limited real-world HAB data. This approach:
•	Expands the training dataset with diverse, simulated HAB scenarios
•	Improves the model's ability to detect rare or extreme events
•	Enhances overall prediction accuracy by exposing the model to a wider range of potential HAB conditions
By combining real observations with GAN-generated data, the model achieves better generalization and robustness in HAB detection across varied marine environments.
