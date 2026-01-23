<div align="center">

# 🎯 Real-Time Competitor Strategy Tracker for E-commerce

### *Intelligent Pricing Through AI-Powered Competitive Intelligence*

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![ML](https://img.shields.io/badge/ML-Deep%20Learning-orange.svg)
![LLM](https://img.shields.io/badge/LLM-Powered-green.svg)

</div>

---

## 💡 What is This Project?

An **end-to-end intelligent pricing system** that combines **web scraping, machine learning, deep learning, and Large Language Models (LLMs)** to analyze competitor book data from [BooksRun](https://booksrun.com/) and dynamically adjust pricing strategies for our e-commerce platform [Books to Scrape](https://books.toscrape.com/).

This system evolves through **four progressive milestones**, starting from foundational neural network implementation and culminating in **LLM-powered competitor intelligence and automated pricing decision-making**.

---

## 🗺️ Project Roadmap

```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│  Milestone 1    │ ─> │  Milestone 2    │ ─> │  Milestone 3    │ ─> │  Milestone 4    │
│  Neural Network │    │  Web Scraping   │    │  LLM Analysis   │    │  Dynamic Pricing│
│  from Scratch   │    │  & Extraction   │    │  & Sentiment    │    │  & Results      │
└─────────────────┘    └─────────────────┘    └─────────────────┘    └─────────────────┘
```

| Phase | Focus Area | Deliverable |
|-------|------------|-------------|
| **🧮 Phase 1** | Neural Network from Scratch | MNIST Classification Model |
| **🕷️ Phase 2** | Web Scraping & Data Extraction | Structured Product Dataset |
| **🤖 Phase 3** | LLM-Based Semantic & Sentiment Analysis | Enriched Intelligence Data |
| **💲 Phase 4** | Dynamic Pricing Logic & Results | Automated Pricing Decisions |

---

## ⚙️ Tech Stack

<table>
<tr>
<td valign="top" width="50%">

**Core Technologies**
- 🐍 Python 3.8+
- 🔢 NumPy & Pandas
- 📊 Matplotlib & Visualization

</td>
<td valign="top" width="50%">

**Specialized Tools**
- 🌐 Requests & BeautifulSoup
- 🖼️ Pillow (PIL)
- 🧠 LLMs (Gemini / GPT)
- 📁 CSV Data Pipelines

</td>
</tr>
</table>

---

## 🔬 Phase 1: Neural Network from Scratch

> **Goal:** Build a Deep Neural Network using only NumPy to understand core deep learning concepts without frameworks like TensorFlow or PyTorch.

### 🏗️ Architecture Design
```
INPUT LAYER (784) 
      ↓
HIDDEN LAYER 1 (128)
      ↓
HIDDEN LAYER 2 (64)
      ↓
OUTPUT LAYER (10)
```

### ⚡ Implementation Highlights
- ✅ **Forward Propagation** - Data flows through network layers
- ✅ **Backpropagation** - Gradient computation for weight updates
- ✅ **Stochastic Gradient Descent** - Optimization algorithm
- ✅ **Activation Functions** - Sigmoid, ReLU, Softmax
- ✅ **Loss Function** - Binary Cross-Entropy

### 📈 Performance Metrics
| Metric | Score |
|--------|-------|
| Training Accuracy | **99.90%** |
| Validation Accuracy | **97.45%** |

> 💎 **Key Insight:** ReLU activation demonstrated faster convergence and lower validation loss compared to sigmoid.

---

## 🔍 Phase 2: Web Scraping & Data Extraction

> **Target Platform:** [books.toscrape.com](https://books.toscrape.com/) — an educational e-commerce platform designed for web scraping practice.

### 📦 Extracted Data Points
| Category | Fields |
|----------|--------|
| **Product Info** | Book Title, Category/Genre, Product Description |
| **Pricing** | Price (GBP), Tax Details, Price Incl./Excl. Tax |
| **Inventory** | Stock Availability, UPC Code |
| **Quality** | Star Rating (1-5) |

### 🔄 Data Pipeline Workflow
```
1️⃣ Genre-wise Crawling → 2️⃣ Pagination Handling → 3️⃣ Product-level Extraction → 4️⃣ CSV Storage
```

---

## 🎨 Phase 3: LLM-Based Semantic & Sentiment Analysis

> **Purpose:** Leverage Large Language Models to extract semantic meaning and sentiment from product descriptions and metadata.

### 🧩 LLM Capabilities Applied
- 💬 **Contextual Understanding** of product descriptions
- 😊😐😞 **Sentiment Classification** (Positive / Neutral / Negative)
- 📊 **Demand Inference** using keywords and textual tone
- 🎯 **Context-aware Pricing** recommendations

### 🌟 Impact
LLM analysis transforms raw scraped data into **qualitative intelligence**, enabling informed and explainable pricing decisions that go beyond numeric features alone.

---

## 💰 Phase 4: Dynamic Pricing Logic & Results

### 🎛️ Pricing Strategy Engine

**Dynamic Adjustment Factors:**
- 🏪 Competitor pricing benchmarks
- 📦 Stock availability levels
- ⭐ Product ratings & reviews
- 🤖 LLM-generated sentiment scores
- 📈 Demand signals from descriptions

### 🔀 Decision Matrix

| Scenario | Action |
|----------|--------|
| ⭐ High Rating + 😊 Positive Sentiment | **↗️ Price Increase** |
| ⭐ Low Rating or 😞 Negative Sentiment | **↘️ Price Decrease** |
| 📦 Low Stock + 📈 High Demand | **💎 Premium Pricing** |
| 📦 Overstocked Items | **🏷️ Discount Pricing** |

### 📊 Deliverables
- ✅ Original vs Adjusted Price Comparison
- ✅ Pricing Decision Explanations
- ✅ CSV-based Pricing Reports
- ✅ Visualized Pricing Changes

---

## 🏛️ System Architecture Overview

**Modular Pipeline Design:**

```
┌──────────────┐     ┌──────────────┐     ┌──────────────┐     ┌──────────────┐
│   Data       │ --> │   Feature    │ --> │   LLM        │ --> │   Pricing    │
│  Collection  │     │  Extraction  │     │  Enrichment  │     │   Engine     │
└──────────────┘     └──────────────┘     └──────────────┘     └──────────────┘