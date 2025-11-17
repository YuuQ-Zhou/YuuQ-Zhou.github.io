
# 📝 Research Experience 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Decoding Schizophrenia with EEG & ERP</div><img src='../../images/流程图1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Decoding Schizophrenia: Superior Discriminative Power of Resting-State EEG over Event-related Potentials in a Comparative Machine Learning Framework**
This work establishes that for machine learning-based diagnosis, resting-state EEG provides a more powerful and reliable basis for classifying schizophrenia than brain activity recorded during cognitive tasks (ERPs).

[**Content**]
- **EEG/ERP Data Preprocessing**: Systematically processed resting-state EEG and N-back task ERP signals using EEGLAB, implementing a full pipeline of filtering, artifact rejection, and normalization to maximize signal integrity and ensure high-quality data for analysis.
- **Frequency-Domain Biomarker Identification**: Employed Fourier Transform to extract power and energy spectrum features, converting complex time-series data into a clear frequency-domain representation to uncover potential biomarkers of schizophrenia.
- **Interpretable Machine Learning for Diagnosis**: Developed diagnostic models using interpretable algorithms (SVM, GBDT, KNN, Random Forest). Leveraged the Fisher-score algorithm for feature selection to pinpoint the most discriminative neural patterns across different frequency bands and brain regions.
- **Key Findings**: Demonstrated that GBDT model achieved superior performance in classifying resting-state EEG, while SVM was optimal for task-based ERP data. This highlights a state-dependent optimal model choice. Identified the occipital lobe during visual processing tasks as a critical region containing highly discriminative features, suggesting its key role in the pathophysiology of schizophrenia.
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Decoding Age-Related Schizophrenia</div><img src='../../images/mos&sh-图总_画板 1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Age-Related Neural Signatures of Schizophrenia: A Cross-Cohort Deep Learning Analysis of EEG Functional Connectivity**

This research investigates age-related neural signatures of schizophrenia by conducting a comparative analysis of adult and adolescent EEG data, leveraging advanced brain network modeling and deep learning

[**Content**]
  - **Cross-Cohort & Cross-Age Comparative Framework**: Initiated a novel comparative study between a privately collected adult schizophrenia EEG dataset (Shanghai) and a public adolescent dataset (Moscow), establishing a framework to test the generalizability of neural biomarkers across different age groups and populations.
  - **Functional Brain Network Construction & Analysis**: Constructed functional brain networks using Power Spectral Density (PSD) as node features and Phase Lag Index (PLI) / Phase Locking Value (PLV) as edge weights. This approach enabled a direct comparison of functional connectivity patterns between the two distinct patient cohorts.
  - **Graph-Based Deep Learning for Neuropathology**: Applied Graph Convolutional Network to model the brain's functional connectome, successfully identifying complex, non-linear neuropathological patterns that distinguish the adult and adolescent schizophrenia cohorts.
  - **Developing a Superior Hybrid Diagnostic Model**: Designed and benchmarked multiple deep learning architectures for diagnostic classification. The proposed LSTM-Transformer model demonstrated superior performance and robustness, outperforming other hybrid models across both datasets, providing a powerful solution for cross-cohort diagnosis.
</div>
</div>




<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">AI-Assisted Clinical Diagnosis
      </div>
      <img src='../../images/Electroencephalogram (EEG) Visualization.png' alt="sym" width="100%">
      <img src='../../images/rag.png' alt="sym" width="100%">
     # <video src='../../images/scz_web.mp4' alt="video" width="100%" controls preload="none">
     #   Your browser does not support video playback. 
     #   您的浏览器不支持视频播放。
     # </video>
    </div>
  </div>
<div class='paper-box-text' markdown="1">

**An Interactive Platform for AI-Assisted Clinical Diagnosis**
This website demonstrates the translation of foundational AI research into a tangible clinical tool. I independently conceived and developed an interactive web-based platform designed to bridge the gap between computational models and real-world clinical practice.
[**Content**]
  - **A Holistic, LLM-Enhanced Diagnostic Framework**: Drawing on my industry experience with Large Language Models (LLMs), I engineered a novel platform that integrates three critical data sources: objective EEG-based diagnostic predictions, standardized clinical assessment scales, and a dynamic, interactive patient consultation module.
  - **Rapid Prototyping and Research-to-Practice Translation**: I demonstrated strong self-learning and execution capabilities by mastering the Streamlit framework from the ground up to build and deploy a functional prototype in just two weeks. This platform is specifically designed to create a seamless workflow between computational research and hands-on clinical assessment.
  - **Domain-Specific Language Model Customization**: To power the platform’s consultation module, I built a specialized, lightweight language model. By leveraging Retrieval-Augmented Generation (RAG), the model was fine-tuned on a curated corpus of medical literature and clinical reports to provide context-aware and evidence-based responses for clinical inquiries.
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Interventions for DCD</div><img src='images/图总结.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Interventions for Developmental Coordination Disorder (DCD)**
This study provides a comprehensive analysis of the research landscape for interventions targeting DCD in children, combining a wide-ranging bibliometric review with a detailed meta-analysis of intervention effectiveness.

[**Content**]
  - **Systematic Mapping of the Global Research Landscape**: Conducted a large-scale bibliometric analysis to identify key research trends, geographical patterns, and influential institutions and authors in the field of DCD intervention. The study highlights Canada, particularly McMaster University, as a central hub for DCD research.
  - **Evidence-based Evaluation of Intervention Efficacy**: Performed a meta-analysis to quantitatively assess the effectiveness of various motor interventions using the standardized Movement Assessment Battery for Children-2 (MABC-2).
  - **Identification of Optimal Intervention Strategies**: The findings demonstrate that different interventions yield distinct benefits. Notably, multi-component exercises are most effective for improving balance, while task-oriented and skill-based activities show significant advantages for enhancing manual dexterity, aiming, and catching.
  - **Guidance for Future Clinical Practice and Research**: By integrating bibliometric trends with quantitative efficacy data, this research identifies critical gaps in the literature and proposes a clear, data-driven framework for designing and implementing targeted DCD management strategies.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EEG-Based Fatigue Prediction</div><img src='images/疲立测.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**"PLEISURE" - An On-Chip, Real-Time System for EEG-Based Fatigue Prediction**
This work encompasses the end-to-end development of an intelligent IoT system for real-time fatigue prediction, from algorithm design and on-chip hardware implementation to advanced deep learning analysis.
[**Content**]
  - **FPGA-Based Real-Time Algorithm Implementation**: A fatigue detection algorithm was designed and implemented on an FPGA. This on-chip processing enables real-time signal analysis at the edge for a wearable predictive warning system.
  - **Non-Linear Feature Engineering**: A feature extraction pipeline was developed to quantify fatigue from raw EEG signals. The process involves computing non-linear dynamic metrics, including Sample Entropy and Approximate Entropy, to characterize changes in brain activity associated with physiological fatigue.
  - **Dual-Approach Deep Learning for Classification**: Two deep learning models were architected and benchmarked for fatigue classification. A CNN-LSTM fusion model was applied to capture spatio-temporal dependencies in EEG signals, while GNN was used to model the brain's functional connectivity.
</div>
</div>



