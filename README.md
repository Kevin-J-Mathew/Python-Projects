# Python-Projects
These are some of the python projects I've made. Some of them display their output as a seperate web page, so please refer to the output files to see the results. 

**Project Descriptions:**

**1. Brain Tumor Classification Using EfficientNetV2M:**

This project presents a deep learning model based on EfficientNetV2M with transfer learning, achieving nearly 99% accuracy in classifying brain tumors from the BR35H dataset — outperforming traditional CNN-based models.

By automating tumor classification, it accelerates diagnosis and reduces human error, offering strong potential as a clinical decision support tool.
While highly effective, a few tumor cases were misclassified, highlighting the need for further refinement to improve reliability. Future work will focus on enhancing sensitivity to subtle tumor variations, incorporating 3D MRI analysis, and integrating explainability techniques to build clinician trust.


The project underscores the growing impact of AI in medical imaging, providing a faster, more reliable approach for brain tumor detection in clinical workflows.



**2. AI Powered Medical Transcription App:**

This project developed an AI-powered pipeline to automate medical documentation by converting spoken clinical notes into structured text. It integrates audio preprocessing, speech-to-text conversion using OpenAI’s Whisper, and clinical entity extraction via SciSpaCy’s biomedical NER model.

The system processes raw audio files of any format through voice activity detection, noise reduction, transcription, and extracts patient details, vitals, medications, diagnoses, and symptoms using a combined NER and regex approach. Outputs include a clean transcript and a structured dictionary of clinical information.

Designed for future integration into a Streamlit-based interface, this pipeline improves documentation speed, accuracy, and transparency—helping reduce clinician workload while offering an interpretable, scalable solution for modernizing healthcare records.


**3. IDC Prediction using Whole Slide Images:**

   
This project developed an interpretable deep learning pipeline for classifying Invasive Ductal Carcinoma (IDC) in Whole Slide Images (WSIs) using a weakly supervised Attention-Based Multiple Instance Learning (ABMIL) framework. It utilized high-resolution pathology slides from the TCGA-BRCA repository, which were manually downloaded and organised into a structured dataset. The project aims to work without pixel-level annotations to reflect real clinical constraints.

The pipeline involved stain normalization, tissue-rich patch extraction, bag-level augmentation, feature embedding via a pretrained ResNet-50, and classification through an attention-based MIL model. It was trained with 5-fold cross-validation and achieved 94.12% test accuracy and an AUC of 0.9965 on a hold-out test set.

Crucially, attention-based visualizations—including bar plots and spatial heatmaps—addressed the AI black box problem by highlighting which specific image patches contributed to each diagnosis. This interpretability ensures clinically meaningful, transparent decision-making and supports ethical, trustworthy integration of AI in diagnostic workflows.


