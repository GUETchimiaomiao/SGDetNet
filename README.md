# SGDetNet
SGDetNet: A Structure-Guided Framework for Medical Image Anatomica Landmark Detection

Anatomical landmark detection is a crucial prerequisite for quantitative clinical analysis. However, existing deep learning methods, particularly heatmap-based approaches, are constrained by information-sparse supervisory signals (e.g., conventional Gaussian heatmaps). These signals fail to encode the structural context of the underlying anatomy, limiting detection accuracy and robustness.To address this, we propose SGDetNet, a structure-guided landmark detection network that refines the learning process through a global-to-local paradigm.
Our framework consists of two main components:
1. Structure-Guided Supervisory Module (SGSM): Generates supervisory signals enriched with anatomical structural context, replacing the simple Gaussian heatmap.
2. Landmark Detection Network (DetNet): A novel encoder-decoder network that learns the intrinsic relationship between the global anatomical context and local landmark features, enabling precise localization.
3. Validated on diverse multimodal datasets (Cephalometric X-ray, Chest X-ray, and Cardiac MRI), SGDetNet consistently outperforms other state-of-the-art methods in both accuracy and generalization, offering a robust approach to enhancing automated clinical workflows.

The full source code will be made publicly available once the paper is accepted.
