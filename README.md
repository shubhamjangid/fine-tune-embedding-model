Domain adaptation on the unlabeled data

🧩 Phase 1: Domain Adaptation (Unsupervised)
	•	Use TSDAE on domain related corpus to make the model understand the domain language and syntax.

🧪 Phase 2: Supervised Fine-Tuning
	•	Fine-tune the TSDAE-adapted model on a sentence similarity task using a supervised dataset (like natural-questions).
