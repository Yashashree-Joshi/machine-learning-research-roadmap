# Day 1 — What is Machine Learning Research?

> Part of the **Machine Learning Research Roadmap** series.

---

## 🤔 A Simple Question

Imagine you're working on the Titanic dataset.

Suppose you train a Random Forest model and obtain **84% accuracy**. Then, you train an XGBoost model and obtain **87% accuracy**.

*These numbers are hypothetical and are used only to illustrate the research process.*

Most people might stop at comparing the two accuracy scores.

Researchers ask:

> Why did XGBoost perform better in this experiment?

They investigate further:

- Did the models use the same training and testing data?
- Did hyperparameter settings affect the results?
- Which features contributed to the predictions?
- Would the performance difference remain consistent across different data splits?

That curiosity leads to a deeper investigation.

That is where machine learning research begins.

---

# 🧠 The Difference Between Using ML and Researching ML

Most Machine Learning learning paths look like this:

```text
Learn Algorithms
      ↓
Build Projects
      ↓
Participate in Kaggle
      ↓
Improve Accuracy
```

Research adds one extra step:

```text
Learn Algorithms
      ↓
Build Projects
      ↓
Ask Questions
      ↓
Run Experiments
      ↓
Generate Insights
```

Machine Learning projects focus on solving problems.

Machine Learning research focuses on understanding problems.

---

# 🔬 What is Machine Learning Research?

Machine Learning Research is the process of generating new knowledge through systematic experimentation.

Instead of asking:

> Can I build a model?

Researchers ask:

> Can I understand, improve, or extend existing methods?

Research is driven by curiosity.

Projects answer problems.

Research answers questions.

---

# ⚔️ ML Projects vs ML Research

| ML Project            | ML Research                   |
| --------------------- | ----------------------------- |
| Build a solution      | Investigate a question        |
| Focus on results      | Focus on understanding        |
| Accuracy is the goal  | Insight is the goal           |
| Uses existing methods | Evaluates or improves methods |
| Ends with a model     | Ends with a conclusion        |

---

## Example

### Project

Goal:

```text
Predict Titanic survival.
```

Approach:

* Train Random Forest
* Tune hyperparameters
* Improve accuracy

Outcome:

```text
A working model.
```

---

### Research

Question:

```text
Which missing-value imputation method
works best for Titanic prediction?
```

Approach:

* Mean Imputation
* Median Imputation
* KNN Imputation

Outcome:

```text
A new insight about preprocessing.
```

That's research.

---

# 🧪 What Do Researchers Actually Do?

Every research study follows a structured process.

```text
💡 Idea
   ↓
❓ Question
   ↓
📝 Hypothesis
   ↓
📊 Dataset
   ↓
⚙️ Experiment
   ↓
📈 Evaluation
   ↓
🔍 Insight
```

Throughout this roadmap, we'll explore each step of the machine learning research process, from formulating a research question to designing experiments and evaluating results.

---

# 📊 A Mini Research Example

Suppose we want to investigate:

> Does the choice of missing-value imputation method affect model performance?

For illustration, imagine conducting an experiment using three imputation methods while keeping the dataset, model, train-test split and evaluation procedure consistent.

*The following accuracy values are hypothetical and are included only to demonstrate how experimental results can be interpreted.*

| Imputation Method | Accuracy |
|---|---:|
| Mean Imputation | 81% |
| Median Imputation | 82% |
| KNN Imputation | 85% |

### Interpreting the Results

In this hypothetical experiment, KNN Imputation achieves the highest accuracy.

However, this does not prove that KNN Imputation is always the best method.

The result applies only to this particular experimental setup. Further experiments, such as testing different data splits and evaluation metrics, would help determine whether the observed difference is consistent.

We didn't create a new model.

We investigated how a preprocessing choice could affect model performance.

That is one way machine learning research generates useful insights.

---

# 🚀 Why Research Matters

Every major breakthrough in Machine Learning started as research.

```text
Logistic Regression
        ↓
Random Forest
        ↓
Gradient Boosting
        ↓
Transformers
        ↓
Large Language Models
```

Someone asked a question.

Someone ran experiments.

Someone discovered something useful.

Research is how Machine Learning evolves.

---

# 🎯 Day 1 Challenge

Choose a dataset that you would like to study throughout this roadmap.

Possible choices:

- Titanic
- House Prices
- Diabetes
- Credit Card Fraud

Write:

1. Problem Statement
2. Research Question
3. Hypothesis

You may revisit this dataset in future chapters as we learn research methodology and experimental design.

---

# ✅ Key Takeaways

* Machine Learning projects solve problems.
* Machine Learning research investigates questions.
* Research starts with curiosity.
* Experiments create evidence.
* Insights are more important than accuracy alone.

---

## 📓 Companion Kaggle Notebooks

This roadmap will be accompanied by practical Kaggle notebooks where research concepts are applied to real datasets.

Planned studies:

- Titanic Survival Prediction
- House Price Prediction
- Diabetes Classification
- Credit Card Fraud Detection

[Day 1 — What is Machine Learning Research?](https://www.kaggle.com/code/yashashree01/day-1-what-is-machine-learning-research)

---

# 📚 References

The concepts introduced in this chapter are based on foundational texts and educational resources in machine learning and research methodology.

1. Bishop, C. M. (2006). *Pattern Recognition and Machine Learning*. Springer.

2. Goodfellow, I., Bengio, Y., & Courville, A. (2016). *Deep Learning*. MIT Press.

3. Mitchell, T. M. (1997). *Machine Learning*. McGraw-Hill.

4. Russell, S., & Norvig, P. (2021). *Artificial Intelligence: A Modern Approach* (4th ed.). Pearson.

5. Murphy, K. P. (2022). *Probabilistic Machine Learning: An Introduction*. MIT Press.

6. Ng, A. (Machine Learning & AI Courses). DeepLearning.AI.

7. Scikit-learn Developers. *Scikit-learn User Guide*. https://scikit-learn.org/stable/user_guide.html

---

**Note:** This chapter is an educational introduction to machine learning research. Readers are encouraged to explore the referenced books and official documentation for deeper theoretical understanding and practical implementation.


# ⏭️ Next Chapter

## Day 2 — Research Workflow

Tomorrow we'll learn how researchers move from an idea to a scientifically validated conclusion.

[Day 2 — Machine Learning Research Workflow](https://github.com/Yashashree-Joshi/machine-learning-research-roadmap/tree/main/Phase-01-Research-Foundations/Day-02-The-ML-Research-Workflow)

---

⭐ If you're following this roadmap, consider starring the repository and joining the journey.
