# DALL-E_type_model_build

### Overview: 
This repository documents my journey of building an image generator inspired by DALL-E, using the COCO dataset and combining the strengths of Transformers and GANs. While the project is still a work in progress, it’s been a rollercoaster of challenges, trial and error, and invaluable learning moments. The model isn’t quite generating the magic yet, but every setback has been a step forward in understanding this complex domain.

---

### Goal
The ultimate aim is to build a model capable of generating images based on textual descriptions without relying on pretrained solutions. The goal is to explore the inner workings of generative models and understand the synergy between Transformers and GANs in crafting meaningful visuals.

---

### Challenges Faced

1. **Massive Dataset Issues**: 
The COCO dataset is enormous, and loading it into memory has been a consistent challenge. Using a fraction (10%) of the dataset for training and validation helped, but the sheer size still caused resource limitations on platforms like Kaggle.

2. **Training Time**:
Training even a single epoch took hours, and after three epochs, the model wasn’t learning anything substantial. Optimizing this process is still a work in progress.

3. **Tokenization**:
Leveraged a `bert-base-uncased` tokenizer to process captions for image generation. While this worked fine, the integration with the GAN pipeline led to dimension mismatches and bugs that took significant time to resolve.

4. **Model Design**:
Balancing the GAN architecture with Transformer-based encoding for captions has been a steep learning curve. It’s clear that conditional GANs alone may not be sufficient for this task.

5. **Inferencing**:
The inferencing notebook showed that while the model works on paper, it isn’t producing meaningful outputs. There’s still a long way to go before achieving functional image generation.

---

### Status of the Project:
<br>
<div align= "center">
    <img src= "https://i.postimg.cc/m25mQMWF/Underconstruction-v2-5.gif" width="500px"> 
</div>
<br>
But, will keep it on hold for some time.

---








