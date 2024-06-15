# Multimodal Material Estimation

Implementation of a material estimation model using audio-visual cues using CLIP and Whisper to encode the Image and Audio inputs, and an LLM to align them to a fixed size text embedding space which is later used for Material class prediction.

![MLP](./mlp.png)

To run the training code:
`python train.py`
