Domain adaptation on the unlabeled data

Phase 1: Domain Adaptation (Unsupervised) - Utilize TSDAE on a domain-related corpus to enable the model to comprehend the domain-specific language and syntax.
Phase 2: Supervised Fine-Tuning - Fine-tune the TSDAE-adapted model on a sentence similarity task using a supervised dataset (like natural-questions).
