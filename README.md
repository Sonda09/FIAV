# Image Quality Assessment for Facial Image Authenticity Verification (FIAV)
FIAV (Face Image Assessment for Verification) assesses image quality features to differentiate real from AI-generated face images. The key steps of FIAV method are :

    - **Input: Facial Image**  
  Accepts any facial image (real or AI-generated) for analysis.

- **Feature Extraction**  
  Leverages 4 advanced NR-IQA metrics (MANIQA, NIQE, IL-NIQE, TOPIQ) + 4 basic metrics (blur, contrast, brightness, sharpness).

- **Feature Selection**  
  Recursive Feature Elimination (RFE) optimizes feature relevance.

- **Classification Model**  
  Random Forest/SVC trained on 2,097 images (balanced real/AI).

- **Output: Real/Fake Decision**  
  Binary output: Real (label ‘1’) / AI-generated (label ‘0’).


