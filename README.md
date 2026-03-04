## Title: Emotion Aware Mental Health Detection using VAE-Enhanced BERT Representations and Reinforcement Learning
# Project Overview
This project presents a multimodal AI-based system for detecting mental health conditions such as anxiety, stress, and depression using emotional analysis.

The system accepts four types of inputs:
- Text
- Audio
- Video
- Psychological assessments (PHQ-9 and GAD-7)

The model uses BERT embeddings, Variational Autoencoder (VAE), and Reinforcement Learning to analyze emotional patterns and classify mental health severity levels.

# Features
- Multimodal emotion analysis
- BERT-based contextual understanding
- VAE-based feature compression
- Reinforcement Learning for adaptive prediction
- Automated PDF report generation
- CPU-efficient implementation

# Technology Stack
- Python
- PyTorch
- HuggingFace Transformers
- OpenCV
- fpdf
- Google Colab

## Output
The system predicts mental health risk levels such as:
- Minimal
- Mild
- Moderate
- Severe
It also generates a structured PDF report summarizing emotional analysis and assessment results.

# Project Structure
src/      -> Source code files
docs/     -> Project documentation
requirements.txt -> Python dependencies
setup_instructions.md -> Steps to run the project
