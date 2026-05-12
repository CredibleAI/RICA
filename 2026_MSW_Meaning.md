# From Actions to Meaning: Do AI Models Build World Models?

**Mentor**: Dr. [Maciej Świechowski](https://scholar.google.pl/citations?user=VR1gtbMAAAAJ&hl=en&oi=ao)

The departure point and inspiration for this project is the work “Revisiting the Othello World Model Hypothesis.” PDF is available at: https://openreview.net/pdf?id=0x6LFXvQz9

The Othello World Model Hypothesis states that language models trained solely on sequences of legal Othello moves, without access to the game board, rules, or any explicit spatial or visual information, can nonetheless induce an internal model of the game. The world model refers to some kind of internal representation of an environment that enables a system to understand, simulate, and predict how that environment evolves over time, particularly in response to actions or events.

The goal of this project is to extend research on world models in at least one of the following directions:

- *Interactive probing of learned representations.* Develop automated methods for interactively querying machine learning models (not necessarily LLMs) to determine, with some confidence, whether their outputs are purely mechanical / pattern-based or the model has built an internal world model within a given domain.
- *Exploration of alternative domains.* Conduct empirical studies in environments other than Othello, inspired by the above work. These domains need not be games and may include real-world or abstract systems.
- *Learning world models as an optimization objective.* Design and evaluate methods that explicitly incorporate world model learning into the training objective, rather than treating it as an emergent property.

*Additional motivation why:*

By maintaining an explicit or implicitly structured representation of how an environment evolves in response to actions, models equipped with world representations can generate explanations that go beyond surface-level correlations and instead reflect causal or mechanistic reasoning. This helps for more transparent decision-making, where outputs can be traced back to understandable concepts characteristic to a given domain.