# CVPR-Challenge-Advanced-Scenarios-for-Unsupervised-Anomaly-Detection
The MVTec AD 2 Dataset: Advanced Scenarios for Unsupervised Anomaly Detection

Our project addresses the VAND 3.0 Challenge (CVPR
2025) under Category 1 — Adapt & Detect: Robust
Anomaly Detection in Real-World Applications. We develop a Prompt-Based Anomaly Detection (PromptAD) system leveraging CLIP’s vision-language embeddings to identify defects in industrial images, emphasizing robustness to
real-world distribution shifts such as lighting and camera
variations. Utilizing the MVTec AD dataset, our unsupervised approach trains on normal images and generalizes to
unseen conditions. The system integrates a frozen CLIP
backbone, learned prompts, and an anomaly localization
head, achieving 85.4% image-level AUC and 83.2% pixellevel AUC, demonstrating adaptability to diverse industrial
scenarios.
