# Decoding-EGX-Price-Action
This `README.md` is designed to be the professional face of the repository. It combines technical depth with a clear project vision, perfect for a portfolio.

---

# 💹 EGX-Vision: Decoding "Whale" Price Action

**EGX-Vision** is a Quantitative Research project focused on automating the "visual intuition" of elite traders. By converting the **Egyptian Exchange (EGX)** price action into high-dimensional images, we train Deep Learning agents to spot the subtle footprints left by institutional "Whales" before a major trend begins.

---

## 🎯 The Mission

In the volatile landscape of the EGX, raw numerical data often fails to capture the "emotional" state of the market. This project aims to determine whether **Convolutional Neural Networks (CNNs)** or the newer **Vision Transformers (ViTs)** are more effective at "reading" the visual geometry of candlestick charts to predict future price direction.

---

## 🔬 Core Methodology

### 1. The "Quant" Transformation

We do not use standard screenshots. To preserve the mathematical integrity of time-series data, we utilize **Gramian Angular Fields (GAF)**. This technique transforms 1D price movements into 2D polar-coordinate matrices, allowing the model to "see" temporal correlations across different time scales.

### 2. The Architecture Showdown

* **CNN (ResNet/EfficientNet):** Focused on localized pattern extraction (e.g., a sharp V-bottom).
* **ViT (Vision Transformer):** Utilizing "Global Self-Attention" to understand the broader market context (e.g., identifying a 60-day Head-and-Shoulders pattern).

### 3. Synthetic Data Scaling

Because high-probability patterns are rare, we employ a **Synthetic Market Simulator** to generate 50,000+ labeled trading scenarios, injecting "Egyptian Market Noise" to ensure real-world robustness.

---

## 📈 Visual Taxonomy (The AI's Library)

The models are trained to classify the following patterns across EGX blue-chips (CIB, Fawry, EFG Hermes):

* **Reversal:** Bullish/Bearish Engulfing, Morning/Evening Stars, Hammers.
* **Continuation:** Rising/Falling Three Methods, Bullish/Bearish Flags.
* **Structural:** Support/Resistance Liquidity Walls, Double Bottoms.

---

## 🛠️ Tech Stack

* **Language:** Python 3.9+
* **Deep Learning:** PyTorch / TensorFlow
* **Computer Vision:** OpenCV, `pyts` (Gramian Fields), `torchvision`
* **Data Science:** Pandas, NumPy, Matplotlib, TA-Lib
* **Market Data:** YFinance API (EGX Data)

---

## 🗺️ Roadmap

* [ ] **Phase 1: Research & Taxonomy** – Literature review of DL in finance and candlestick theory.
* [ ] **Phase 2: Signal Engineering** – Developing the GAF transformation pipeline.
* [ ] **Phase 3: Training & Battle** – Performance comparison of CNN vs. ViT architectures.
* [ ] **Phase 4: Live Backtesting** – Deploying the winner on 2024-2026 EGX historical data.

---

## 📂 Repository Structure

```bash
├── research/           # Literature reviews and Pattern definitions
├── data_gen/           # Synthetic market simulation scripts
├── transformation/     # GAF (Gramian Angular Field) encoders
├── models/             # CNN and ViT implementation files
├── evaluation/         # Backtesting results and Heatmaps
└── README.md

```

---

## 🏷️ Keywords

`Deep Learning` • `Quantitative Finance` • `Computer Vision` • `Vision Transformers` • `EGX` • `Technical Analysis` • `Price Action` • `Gramian Angular Fields`

---

