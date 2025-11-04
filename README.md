🌀 FreqPose: Frequency-Aware Diffusion with Fractional Gabor Filters and Global Pose-Semantic Alignment

🚧 Code Coming Soon | Paper Under Review
🔗 Project Page (for visualization only): https://github.com/bing32475/FreqPose

🧩 Overview
FreqPose is a diffusion-based framework for Pose-Guided Person Image Synthesis (PGPIS) that addresses two long-standing challenges:
1.High-frequency texture loss (e.g., hair, fabric wrinkles) during pose transfer.

2.Semantic inconsistency between the source appearance and target pose.

To overcome these issues, we propose two key modules:

·🌀 Multi-Level Fractional Gabor Frequency Network (MLGFN)
Extracts and reconstructs fine-grained texture features through fractional-order Gabor filtering and complex-domain attention, enhancing detail fidelity across scales.

·🔗 Global Semantic Pose Alignment Module (GSPAM)
Builds a cross-modal attention bridge between pose and appearance features, ensuring global semantic alignment and identity consistency.
Together, these components form an end-to-end diffusion framework capable of high-fidelity, structure-preserving person synthesis even under large pose variations.

🌟 Key Features
·Frequency-Aware Texture Modeling:

Uses fractional-order Gabor filters to capture amplitude and phase features from multiple scales and directions.

·Global Semantic Alignment:

Cross-attention–based fusion between Swin Transformer features and pose embeddings to maintain semantic coherence.

·High-Fidelity Diffusion Backbone:

Built upon Stable Diffusion v1.5 with optimized conditional injection and frequency-domain enhancement.

·End-to-End Architecture:

Integrates MLGFN and GSPAM seamlessly for joint optimization of texture fidelity and structural alignment.

## 🎨 Visual Results

<p align="center">
  <img src="FrGPose/demo.gif" alt="FreqPose Demo">
  <br>
  <em>FreqPose generates realistic and detail-preserving results even under complex pose transformations.</em>
</p>

<p align="center">
  <img src="docs/visual_comparison.png" width="800">
  <br>
  <em>Comparison with state-of-the-art approaches on the DeepFashion dataset.</em>
</p>

