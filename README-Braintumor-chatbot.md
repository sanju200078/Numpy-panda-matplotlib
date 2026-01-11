🧠 Brain Tumor Screening Chatbot

Medium Project Description (README / Workshop)

This project presents an AI-based Brain Tumor Screening Chatbot that combines medical image analysis and clinical symptom assessment to support early tumor screening. A CNN trained on brain MRI images performs multi-class tumor classification, identifying glioma, meningioma, pituitary tumors, and normal cases. In parallel, an interactive chatbot collects responses to ten clinically relevant yes/no questions related to neurological symptoms. The model fuses CNN confidence scores with questionnaire-based symptom severity to generate a final risk score. The system is deployed using a web-based interface (Gradio/Streamlit) with visual outputs, including probability bar charts, to enhance interpretability. The application serves as a decision-support and educational tool rather than a diagnostic system.

🔹 Detailed Project Description (Thesis / Viva / Proposal)

The Brain Tumor Screening Chatbot is a multimodal AI system designed to assist in early brain tumor screening by integrating deep learning–based MRI image analysis with patient-reported clinical symptoms. The system employs a convolutional neural network (CNN) trained on a class-wise organized brain MRI dataset to perform multi-class classification of tumor types, including glioma, meningioma, pituitary tumors, and non-tumor cases.

To complement image-based predictions, an interactive chatbot module collects binary (yes/no) responses to ten clinically significant neurological symptom questions, such as headaches, seizures, vision impairment, and cognitive changes. A fusion strategy combines the CNN’s probabilistic output with the normalized symptom severity score to compute a final tumor risk estimate. The results are presented through an intuitive web-based interface featuring textual predictions, risk scores, and graphical probability visualizations to improve transparency and user understanding.

This system is intended as an AI-assisted screening and decision-support tool for research and educational purposes. It does not provide a medical diagnosis and is designed to support, not replace, professional clinical judgment.

🔹 One-Line Viva Statement (Very Useful)

“This project integrates CNN-based brain MRI classification with a chatbot-driven clinical questionnaire to provide an AI-assisted brain tumor screening and risk assessment system.”
