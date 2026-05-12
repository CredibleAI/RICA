# Stress-testing AI solutions in LDCT lung cancer diagnostics

**Mentor**: [Bartlomiej Sobieski](https://scholar.google.pl/citations?user=ZDCPqL8AAAAJ&hl=en&oi=ao)

Medical imaging stands at the frontier of computer vision applications with real-world impact. Early diagnosis of lung cancer, the most lethal cancer type, remains an unsolved challenge even for the most experienced experts. Today, advanced AI solutions stand out as the most promising approach. However, their adoption comes at a cost; the complexity of these models introduces the risk of relying on spurious correlations and medically unjustified artifacts, potentially causing more harm than good in the long run.

Our latest work, [recently accepted to ICML 2026](https://arxiv.org/abs/2602.02560), proposes a comprehensive auditing framework, S(H)NAP. It adapts the latest generative techniques, based on recent advances in diffusion models, to provide generative interventional attributions at the level of modular semantic units, such as pulmonary nodules. We apply S(H)NAP to Sybil, a foundation model for lung cancer risk prediction based on a single LDCT scan, and show how the resulting explanations provide an extremely simplified and faithful interpretation. Our framework reveals critical misalignments with domain knowledge: reliance on clinically unjustified artifacts, systematic biases, and inconsistent temporal behaviors. Contrary to prior work, S(H)NAP highlights that even the most commonly applied solutions are not ready for clinical deployment. It provides an excellent starting point for developing a comprehensive, unified audit tool that will verifiably stress-test emerging AI solutions for lung cancer diagnostics, provide a systemic benchmark, and function as a real-time assistant for expert radiologists.

Work on this project will utilize a multi-faceted approach:
- Unifying and extending the initial implementation for broader applicability to arbitrary types of predictive models.
- Conducting foundational research on the underlying principles of the S(H)NAP framework and extending the methodology.
- Advancing the underlying generative diffusion-based techniques to obtain more accurate explanations faster.


Prerequisites include:
- Proficiency in PyTorch and a deep understanding of implementing deep learning models.
- Familiarity with basic XAI techniques, with particular emphasis on SHAP.
- Experience working with diffusion models.

Knowledge of basic medical imaging formats is a plus. Note that not all prerequisites are required to apply; these are the main pillars the project will be based on.
