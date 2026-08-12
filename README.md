# Introducing TransAddAttUnet

> A Deep Learning Framework for Enhanced Brain Tumor Segmentation

## 📌 Overview

## ✨ Key Contributions

## 🏗️ Proposed Architecture
## Proposed Architecture

<p align="center">
  <img src="assets/architecture.png" alt="TransAddAttUnet Architecture" width="100%">
</p>

### Architecture Workflow

```text
                         ┌─────────────────────┐
                         │      MRI Input      │
                         └──────────┬──────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │    Preprocessing    │
                         └──────────┬──────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │      Encoder        │
                         └──────────┬──────────┘
                                    │
                         ┌──────────┴──────────┐
                         ▼                     ▼
              ┌──────────────────┐  ┌──────────────────┐
              │ Transformer Self │  │ Global Spatial   │
              │ Attention (TSA)  │  │ Attention (GSA)  │
              └────────┬─────────┘  └────────┬─────────┘
                       └──────────┬──────────┘
                                  ▼
                       ┌─────────────────────┐
                       │        AAM          │
                       │  Feature Aggregation│
                       └──────────┬──────────┘
                                  │
                                  ▼
                    ┌───────────────────────────┐
                    │ Multi-scale Skip Features│
                    └─────────────┬─────────────┘
                                  │
                                  ▼
                       ┌─────────────────────┐
                       │      Decoder        │
                       └──────────┬──────────┘
                                  │
                                  ▼
                       ┌─────────────────────┐
                       │ Additive Attention  │
                       └──────────┬──────────┘
                                  │
                                  ▼
                       ┌─────────────────────┐
                       │  Tumor Segmentation │
                       └─────────────────────┘



## 🔬 Methodology

## 🧠 Model Components

- Transformer Self-Attention (TSA)
- Global Spatial Attention (GSA)
- Additional Aggregation Module (AAM)
- Additive Attention

## 🗂️ Dataset

## ⚙️ Preprocessing

## 📐 Loss Function

## 🧪 Experimental Setup

## 📊 Results

## 📈 Comparison with Existing Models

## 🖼️ Qualitative Segmentation Results

## 🔍 Visualization

## 🚀 Installation

## ▶️ Usage

## 📁 Repository Structure

## 📚 Citation

## 🙏 Acknowledgement

## 📄 License
