# 📚 Day 01 — Machine Learning Fundamentals

Today I learned the basic concepts of Artificial Intelligence, Machine Learning, and Deep Learning, along with different ways Machine Learning models can learn from data.

---

## 1. What is Artificial Intelligence?

Artificial Intelligence (AI) is the broader field of creating systems that can perform tasks that normally require human intelligence.

Examples:

* Understanding language
* Recognizing images
* Making decisions
* Speech recognition
* Recommendation systems

---

## 2. What is Machine Learning?

Machine Learning (ML) is a subset of AI where computers learn patterns from data and use those patterns to make predictions or decisions without being explicitly programmed for every situation.

### Example

Instead of manually writing rules to identify spam emails, we provide the model with examples of spam and non-spam emails. The model learns patterns from the data and predicts whether a new email is spam.

---

## 3. What is Deep Learning?

Deep Learning (DL) is a subset of Machine Learning that uses neural networks with multiple layers to learn complex patterns from large amounts of data.

Deep Learning is commonly used in:

* Image recognition
* Speech recognition
* Natural Language Processing
* Computer Vision
* Generative AI

---

## 4. AI vs ML vs DL

The relationship can be understood as:

**Artificial Intelligence → Machine Learning → Deep Learning**

AI is the broader field.

ML is a part of AI that learns from data.

DL is a part of ML that uses deep neural networks.

---

## 5. Types of Machine Learning

The major types I learned are:

### Supervised Learning

The model learns from labeled data.

Examples:

* Classification
* Regression

### Unsupervised Learning

The model learns patterns from data without labeled outputs.

Examples:

* Clustering
* Dimensionality Reduction

### Reinforcement Learning

An agent learns by interacting with an environment and receiving rewards or penalties.

---

## 6. Batch Learning

In Batch Learning, the model is trained using the available training data as a batch.

The model is trained periodically using a large amount of data rather than continuously learning from individual incoming data points.

### Example

A company collects customer data for one month and then retrains its recommendation model using the collected data.

### Advantages

* Suitable when data changes slowly
* Can process large amounts of data together

### Limitation

The model does not immediately learn from newly arriving data.

---

## 7. Online Learning

In Online Learning, the model learns incrementally from data as it becomes available.

Instead of retraining the model from the entire dataset, new data can be used to update the model.

### Example

A system receives new transaction data continuously and updates its model as new data arrives.

### Advantages

* Can adapt to changing data
* Useful for continuously arriving data
* Can work with large or continuously growing datasets

### Limitation

The model can be affected by noisy or incorrect incoming data.

---

## 🧠 My Key Takeaways

* AI is the broader concept of machines performing intelligent tasks.
* Machine Learning is a subset of AI that learns from data.
* Deep Learning is a subset of ML based on deep neural networks.
* Machine Learning can be broadly divided into supervised, unsupervised, and reinforcement learning.
* Batch Learning trains using data in batches.
* Online Learning updates the model incrementally as new data arrives.

---

## 💡 What I Understood

The main idea I understood today is that **AI is the broader field, ML is one approach used to achieve AI, and Deep Learning is a specialized approach within ML.**

I also learned that ML models can differ not only in *what* they learn, but also in *how they receive and learn from data*, such as through Batch Learning or Online Learning.

---

## 📌 Next

Continue with the next Machine Learning topic and add my learnings to this 100-day journey.
