# 🧪 Day 4 — Hypothesis Creation

Part of the Machine Learning Research Roadmap series.

> A research question identifies what we want to investigate. A hypothesis predicts what we expect to happen.

---

In Day 3, we learned how to formulate strong research questions.

A research question alone is not enough.

Researchers also need a hypothesis — a testable prediction that can be evaluated using evidence.

In this chapter, we'll learn how to create strong hypotheses and connect them to research questions.
---
# 🤔 Why Do Researchers Need Hypotheses?

Imagine we observe the following pattern in the Titanic dataset:

Women appear to survive more often than men.

---

Several explanations are possible:

### Explanation A

Women were prioritized during evacuation.

### Explanation B

Women happened to be younger on average.

### Explanation C

Passenger class influenced the outcome rather than gender.

---

At this stage, we do not know which explanation is correct.

---
# 🔮 A Hypothesis is a Testable Prediction

A hypothesis is a statement that predicts what we expect to happen.

Unlike observations, hypotheses can be tested using evidence.

---

## Observation

Female passengers appear to survive more often than male passengers.

---

## Hypothesis

Female passengers will have a higher survival probability than male passengers.

---

## Future Experiment

Use Titanic data

↓

Analyze survival rates

↓

Accept or reject the prediction

---

### Key Idea

A good hypothesis can be proven wrong.

If a statement cannot be tested, it is not a scientific hypothesis.

---

# ❌ Weak vs ✅ Strong Hypotheses

## Weak Hypothesis

```text
Machine learning is useful.
```

Problems:

- Too vague
- Not measurable
- Difficult to test

---

## Strong Hypothesis

```text
Feature selection will improve Titanic survival prediction performance.
```

Why it is better:

- Specific
- Measurable
- Testable
- Directly connected to an experiment

---

### Quick Rule

A good hypothesis should make a clear prediction that can be supported or rejected using data.

---
# 🛠️ How to Create a Hypothesis

Creating a hypothesis is a structured process.

---

## Step 1 — Start with an Observation

Example:

Female passengers appear to survive more often than male passengers.

---

## Step 2 — Ask a Research Question

Example:

Does passenger gender influence survival probability?

---

## Step 3 — Make a Prediction

Example:

Female passengers will have a higher survival probability than male passengers.

---

## Step 4 — Write the Hypothesis

Example:

Passenger gender significantly influences survival probability.

---

### Formula

Observation

↓

Research Question

↓

Prediction

↓

Hypothesis

---

## Another Example

Observation:

Older passengers appear less likely to survive.

Research Question:

Does age influence survival probability?

Prediction:

Younger passengers will have higher survival rates.

Hypothesis:

Passenger age significantly influences survival probability.

---



Researchers need a way to transform observations into testable predictions.

This is where hypotheses become important.

---
# ⚖️ Null Hypothesis vs Alternative Hypothesis

Researchers rarely test a hypothesis directly.

Instead, they compare two competing statements.

---

## Null Hypothesis (H₀)

The null hypothesis assumes that there is no effect or relationship.

### Titanic Example

```text
Passenger gender has no effect on survival probability.
```

---

## Alternative Hypothesis (H₁)

The alternative hypothesis assumes that an effect or relationship exists.

### Titanic Example

```text
Passenger gender influences survival probability.
```

---

## Another Example

Research Question:

```text
Does feature selection improve Titanic survival prediction performance?
```

### H₀

```text
Feature selection has no effect on model performance.
```

### H₁

```text
Feature selection improves model performance.
```

---

### Why Do We Need Both?

Research is not about proving ourselves right.

Research is about collecting evidence and determining which statement is better supported by data.

---

# 🎯 Building H₀ and H₁ Step-by-Step

Research Question:

```text
Does passenger class influence survival probability?
```

---

### Step 1 — Create H₀

```text
Passenger class has no effect on survival probability.
```

---

### Step 2 — Create H₁

```text
Passenger class influences survival probability.
```

---

### Another Example

Research Question:

```text
Does age influence survival probability?
```

### H₀

```text
Age has no effect on survival probability.
```

### H₁

```text
Age influences survival probability.
```

---

### Quick Rule

H₀ usually represents:

- No effect
- No difference
- No relationship

H₁ usually represents:

- An effect exists
- A difference exists
- A relationship exists

---
# ⚠️ Common Beginner Mistakes

Many beginners struggle with hypothesis creation.

---

## ❌ Confusing a Question with a Hypothesis

Question:

```text
Does passenger gender influence survival probability?
```

Hypothesis:

```text
Passenger gender influences survival probability.
```

A question is not a hypothesis.

---

## ❌ Making Predictions That Cannot Be Tested

Example:

```text
Machine learning will change the world.
```

Problem:

- Too broad
- Cannot be measured
- Difficult to test

---

## ❌ Being Too Vague

Example:

```text
Age is important.
```

Better:

```text
Passenger age significantly influences survival probability.
```

---

## ❌ Writing Biased Hypotheses

Researchers should create testable predictions rather than assumptions they want to prove.

The goal is evidence, not confirmation.\

---

# 🎯 Day 4 Challenge

Using the Titanic dataset, create hypotheses for the following research questions.

---

## Question 1

Does passenger age influence survival probability?

### Your Hypothesis

_____________________________

---

## Question 2

Does passenger class influence survival probability?

### Your Hypothesis

_____________________________

---

## Question 3

Does passenger gender influence survival probability?

### Your Hypothesis

_____________________________



### Bonus Challenge

For one of the questions above:

- Write H₀
- Write H₁
---

# ✅ Key Takeaways

- A hypothesis is a testable prediction.
- Research questions and hypotheses are not the same thing.
- Strong hypotheses are specific, measurable, and testable.
- Researchers often create both H₀ and H₁.
- Evidence determines whether a hypothesis is supported or rejected.

---

### Remember

Observation

↓

Research Question

↓

Prediction

↓

Hypothesis

↓

Experiment

---

# 🚀 Next Chapter

## Day 5 — Literature Review

Researchers do not work in isolation.

Before conducting a study, they examine existing research to understand:

- What is already known
- What has already been tested
- What gaps still exist

In the next chapter, we'll learn how to perform an effective literature review and avoid reinventing work that already exists.

---
# 📓 Companion Kaggle Notebook

A practical notebook version of this chapter will be available on Kaggle.

🔗 Kaggle Notebook: *([Day 4 kaggle Notebook](https://www.kaggle.com/code/yashashree01/day-4-hypothesis-creation))*

The notebook will include:

- Creating hypotheses from real Titanic observations
- Good vs Bad Hypotheses
- Null vs Alternative Hypotheses
- Hypothesis-building exercises
- Data-driven prediction examples
---

## 🚀 Continue the Journey

### Previous Chapter

← [Day 3 — Research Question Formulation](../Day-03-Research-Question-Formulation)

---

### Next Chapter

➡️ Day 5 — Literature Review

https://github.com/Yashashree-Joshi/machine-learning-research-roadmap/tree/main/Day-05-Literature-Review

---

## 📚 Machine Learning Research Roadmap

🏠 [Repository Homepage](../README.md)
