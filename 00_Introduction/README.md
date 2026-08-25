# Introduction to Machine Learning

## Overview

Machine Learning (ML) is an important area of modern software development and is a subset of **Artificial Intelligence (AI)**. It focuses on enabling computer systems to perform tasks by learning patterns from data rather than relying entirely on explicitly written instructions.

This chapter provides an introduction to Machine Learning and explains its basic concept, relationship with Artificial Intelligence, traditional programming vs. Machine Learning, training data, and how machines learn from examples.

---

## What is Machine Learning?

Machine Learning is the scientific study of **algorithms and statistical models** that allow computer systems to perform specific tasks effectively without being explicitly programmed for every situation.

Instead of providing every instruction manually, Machine Learning systems:

1. Receive data as input.
2. Study the available data.
3. Identify patterns and relationships.
4. Build a model based on the data.
5. Use the learned patterns to make predictions or decisions.

The lecture describes Machine Learning as a process where the machine uses data and patterns to create the algorithm or model required to achieve the desired output.

---

##  Traditional Programming vs Machine Learning

### Traditional Programming

In traditional programming, a human programmer creates a specific set of instructions or an algorithm.

The basic process is:

```text
Input + Program/Instructions → Output
```

The programmer develops the algorithm, provides the input, and the program produces the desired output.

### Machine Learning

In Machine Learning, the approach is different. Instead of manually writing all the rules, we provide data and expected results, and the machine learns patterns from that data.

A simplified representation is:

```text
Input + Output Examples → Machine Learning → Learned Model
```

The learned model can then be used to produce predictions for new inputs.

### Comparison

| Traditional Programming                        | Machine Learning                               |
| ---------------------------------------------- | ---------------------------------------------- |
| Rules are explicitly written by the programmer | Patterns are learned from data                 |
| Programmer creates the algorithm               | Machine learns a model from examples           |
| Input + Instructions → Output                  | Data → Learning → Model → Prediction           |
| Works according to predefined instructions     | Can make predictions based on learned patterns |

---

## Machine Learning and Artificial Intelligence

Machine Learning is a **subset of Artificial Intelligence (AI)**.

Artificial Intelligence aims to replicate aspects of human intelligence using computer systems.

```text
Artificial Intelligence
        │
        ├── Machine Learning
        │
        └── Other AI areas
```

The lecture specifically describes Machine Learning as a subset of Artificial Intelligence and explains AI as an attempt to replicate human intelligence.

---

## Training Data

Machine Learning algorithms build a mathematical model using **sample data**.

This sample data is called **training data**.

Training data is used by the machine to learn patterns that can later be used to make predictions or decisions.

For example:

```text
Training Data
     ↓
Machine Learning Algorithm
     ↓
Learn Patterns
     ↓
Build Model
     ↓
Make Predictions
```

---

## Human Learning vs Machine Learning

A simple way to understand Machine Learning is to compare it with how a child learns.

Suppose a child is taught alphabets:

```text
Learn Alphabets
      ↓
Create Words
      ↓
See More Examples
      ↓
Gain More Knowledge
      ↓
Improve Understanding
```

As the child receives more examples and information, their ability to recognize and understand words improves.

Similarly, a Machine Learning system receives data and learns from the examples provided to it. More relevant training examples can help the system learn the underlying patterns required for making predictions.

---

## Input and Output in Machine Learning

Machine Learning can be understood using the relationship between **input (X)** and **output (Y)**.

For example:

```text
X → Y
```

The machine receives examples of inputs and their corresponding outputs and learns the relationship between them.

After learning from multiple examples, the model can use the learned relationship to predict an output for a new input.

```text
Training Examples
X₁ → Y₁
X₂ → Y₂
X₃ → Y₃
     ↓
Machine Learning
     ↓
Learned Pattern
     ↓
New X → Predicted Y
```

This learning process forms the basis for prediction in Machine Learning.

---

## Key Terms

| Term                        | Meaning                                                                                     |
| --------------------------- | ------------------------------------------------------------------------------------------- |
| **Machine Learning**        | A method where computer systems learn patterns from data to perform tasks.                  |
| **Artificial Intelligence** | The broader field concerned with replicating aspects of human intelligence using computers. |
| **Algorithm**               | A set of instructions or a procedure used to solve a problem or perform a task.             |
| **Training Data**           | Sample data used by a Machine Learning algorithm to learn.                                  |
| **Model**                   | A mathematical representation learned from training data.                                   |
| **Input (X)**               | Data provided to the Machine Learning system.                                               |
| **Output (Y)**              | The expected or predicted result associated with an input.                                  |
| **Prediction**              | The output generated by a trained Machine Learning model for new input.                     |
| **Pattern**                 | A relationship or regularity identified from data.                                          |

---

## Summary

* Machine Learning is a **subset of Artificial Intelligence**.
* Machine Learning allows computers to learn from data rather than relying entirely on explicitly written instructions.
* Traditional programming depends on algorithms created by programmers.
* Machine Learning uses data to learn patterns and build models.
* **Training data** is used to train Machine Learning algorithms.
* Machine Learning algorithms can build mathematical models from sample data.
* Human learning can be used as a simple analogy for understanding Machine Learning.
* Machine Learning can learn relationships between inputs and outputs.
* Learned models can be used to make predictions on new inputs.
* The lecture introduces Machine Learning with **Python** as the programming environment for the upcoming learning series.
