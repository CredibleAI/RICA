# Training an RLHF agent to play Ortho at the Copernicus Science Centre

**Mentor**: [Przemyslaw Biecek](https://scholar.google.pl/citations?user=Af0O75cAAAAJ&hl=en&oi=ao)


Games have long served as a proving ground for artificial intelligence, from chess and Go to modern video games. Beyond benchmarks, however, games deployed in public spaces offer something far more valuable: a setting where AI agents interact with real, non-expert humans. Ortho, an interactive game featured at the[Copernicus Science Centre in Warsaw, provides exactly such a setting — a compact, well-defined game played by visitors of all ages and skill levels every day.

This project will build an RLHF-trained agent for Ortho, intended as a engaging collaborator in the Copernicus Science Centre environment. The work will combine foundational reinforcement learning with the design and collection of human preference data, and culminate in an evaluation of the resulting agent against both algorithmic baselines and human players.

Work on this project will follow a multi-stage approach:
- Implementing a baseline Ortho-playing agent using standard techniques, to serve as both a starting point and a comparison baseline.
- Designing a human preference collection protocol suited to the science centre context, and using the resulting data to train a reward model over agent trajectories.
- Fine-tuning the agent and analyzing how the human-feedback signal shapes its play style, difficulty calibration, and behavioral diversity compared to the self-play baseline.

Prerequisites include:
- Proficiency in Python and PyTorch, and a working understanding of deep learning.
- Familiarity with reinforcement learning fundamentals (policy gradients, self-play).
- Interest in the human-feedback side of modern AI training pipelines (RLHF, reward modeling, preference learning).

Experience with game-playing AI, multi-agent systems, or designing user studies is a plus. Note that not all prerequisites are required to apply; these are the main pillars the project will be based on.

