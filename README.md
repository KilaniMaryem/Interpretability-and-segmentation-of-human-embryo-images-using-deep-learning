# Description


This project focused on the interpretability of deep learning models in the medical domain, particularly for human embryo image segmentation. By utilizing the Comprehensive Attention Network (CANET), a public dataset of human embryo images was processed to not only perform segmentation but, more importantly, to provide insights into the model’s decision-making process. Each ipynb file is for segmenting one of the relevant parts of a human embryo (the Zona Pellucida, Inner Cell Mass, and Trophectoderm).


# Key aspects of the project:

- Segmentation with CANET: Employed CANET to segment human embryo images into its 3 relevant zones (Inner Cell Mass,Trophectoderm,Zona Pellucida), leveraging attention mechanisms to enhance the model's focus on relevant image regions. This deep learning architecture was particularly suited for medical imaging tasks requiring high precision.
- Attention Maps for Explainability: Generated Attention Maps to visualize the areas of the image that the model considered most important during the segmentation process. These maps highlight which regions contributed the most to the decision.
