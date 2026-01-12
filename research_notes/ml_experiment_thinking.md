# Machine Learning Experiment Thinking Framework

## Why this exists
Machine learning is not about models — it is about experiments.  
Every model is a hypothesis.  
Every training run is a test.

This framework captures how I think about designing and evaluating ML experiments in a structured, scientific way.

---

## 1. Problem Definition
Before touching any model, I define:
- What question am I actually trying to answer?
- What does “success” mean numerically?
- What data is available and what are its limitations?

If these are unclear, any result is meaningless.

---

## 2. Hypothesis
Every experiment starts with a belief.

I write down:
- What I expect to happen
- Why I think it will happen
- What outcome would prove me wrong

This prevents me from just running models blindly.

---

## 3. Experimental Design
I explicitly separate:
- baseline model
- variables I will change
- what stays fixed
- how many times I will repeat the experiment

Example structure:
```python
experiment = {
    "baseline": "simple_model",
    "variables": ["learning_rate", "batch_size"],
    "controls": ["random_seed", "dataset_split"],
    "runs": 5
}
