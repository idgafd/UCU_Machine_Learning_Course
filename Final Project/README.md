# Final Project: Improving Parameter-Efficiency of Particle Transformer for LHC Jet Tagging

This folder contains the final deliverables for our Machine Learning course project on **jet tagging** (classifying particle origins of hadronic jets) using state-of-the-art architectures and parameter-efficient modifications.
- `JetTagging_Report.pdf` – full technical report
- `JetTagging_Presentation.pdf` – final presentation slides

We experimented with multiple baselines and then focused on **Particle Transformer (ParT)**. Key directions:
- **Same Weights**: sharing weights across encoder blocks and across decoder blocks to improve parameter-efficiency.
- **Weighted Layer Decoders (WLD)**: decoding intermediate encoder layers and aggregating predictions to improve accuracy per parameter.
- **Optimization experiments**: comparing optimizers (Ranger, Lion, SOAP) and training dynamics.

## Authors
Mikhailyna Bondarenko, Anastasiia Mazur, Oleh Prostakov. 
