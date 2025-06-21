Summary
In this project, I developed a robust image captioning pipeline using state-of-the-art vision-language models to generate descriptive captions for test images. Initially, the open_clip model was employed to extract joint image and text embeddings for measuring semantic similarity between images and training captions. To explore performance improvements, BLIP and BLIP-2 models were also integrated and tested, aiming to leverage their advanced vision-language generation capabilities. However, despite their strengths, these models resulted in lower evaluation scores on the competition dataset.

Consequently, the pipeline was refined to rely primarily on the CLIP model, which demonstrated more consistent and higher-quality caption retrieval performance. This strategic return to CLIP ensured a balance of efficiency and accuracy, maximizing prediction quality while adhering to computational constraints.

