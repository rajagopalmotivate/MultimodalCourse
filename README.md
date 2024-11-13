# Multi-Modal Models with Hugging Face  - Course Outline

##  This is a submission towards Datacamp's Audition process
![data camp](https://assets.bitdegree.org/online-learning-platforms/storage/media/datacamp-workspace-review-logo-big.o.png)


## What problem(s) will students learn how to solve?

1. <sub>[ Concept + Problem Solving + Architecture ] </sub> How to solve a real world use case by designing an architecture with Multimodal AI.

    - Use case: Assistive technology for Persons with Visual impariment  
    - Use case: Text search to reterive product images in eCommerce store 
    - Use case: Your use case 

2. <sub>[ Design + Code ] </sub> Design and implement Multimodal Human Computer Interaction experiences

    - <sub>[Basic Level] </sub> Understand different modalites and code different multimodal tasks such as VQA (Visual Question Answering).  
    - <sub>[Medium Level] </sub> Can you combine two multimodal models to design a new multimodal experience. Create an app for multilingual speech interaction with visual question answering task ( Multilingual Speech interaction + VQA ).
    - <sub>[Architecture Choices + Analysis] </sub> When to use what? Cost vs Latency vs Accuracy trade offs of different multimodal models. 

3. <sub>[ Concept + Data + Design + Code ] </sub> Design and implement Multimodal Few Shot Learning 

    -  Few Shot Learning in Multimodal models vs Unimodal models.  
    -  Zero/ One / Few Shot Learning Techniques
    -  Providing Contrastive examples
    -  <sub>[Design + Code] </sub> How to provide one-shot multimodal examples to Llama 3.2 Vision
    -  <sub>[Design + Code] </sub> How to provide Few-shot Image examples to GEMINI  (Contrastive examples)
    -  <sub>[Design + Code] </sub> How to provide Few-shot Video examples to GEMINI
    -  <sub>[Advanced Design + Code] </sub> How to find needle in a multimodal haystick  (Search for a visual object in a video)
     
  
4.  <sub>[ Concept + Dataset Design + FineTuning + Code ] </sub> Create a custom multimodal model by fine-tunning a multimodal LLM on a multimodal dataset

    -  <sub>[Concept] </sub> PeFT, LoRA, QLoRA of Multimodal LLMs 
    -  <sub>[Design + Code] </sub> How to Fine tune a Multimodal LLM on a multimodal datasets




Start from the basics and go to advanced concepts with multimodal AI.  

#1:  Conceptual understanding: Real world Problem-solving with multimodal AI
Learning objective #1.  How to apply multimodal model to solve real-world use cases. We will learn the Human-centric design of Multimodal AI solutions using a sample use case of applying  Multimodal LLM for persons with  visual impariment.    
Specifics: We will learn the Human-centric design of Multimodal AI solutions using a sample use case of applying  Multimodal LLM for persons with  visual impariment.    

#2:  Design and implement various multimodal tasks, and combine multiple mutlimodal models to do more complex multimodal tasks
Learning objective #2.  Learn to Design and code various multimodal tasks (visual question answering) . Learn the pipeline technique for multimodal tasks. (combine Sarvam speech models and LLama models) to create speech interaction with vision language models in local languages. 
#2.1: How to apply Multimodal models from Hugging Face for various multimodal tasks such as Visual Question Answering with  Vision-and-Language Transformer (ViLT) model and Captioning images with Generative Image-to-text Transformer (GIT), reasoning over charts with Microsoft Phi-3 Vision (Phi).  (technique:  pipeline of multimodal tasks). 
#2.2: How to combine the power of multiple multimodal models.  In our example , combine Sarvam speech models and LLama models) to create speech interaction with vision language models in local languages. 

#3:  Design and implement Multimodal Few Shot Learning . Also, understand when to use multimodal One-Shot Learning vs Zero Shot Learning. 
Learning objective #3.  How to design and implement Multimodal Few Shot Learning with  Llama3.2 Vision (technique: Multimodal Few Shot Learning by sending more than one image to Llama )  . (implement multimodal few shot with multiple interleaved image support for Llama 3.2 vision) .    

#4:   Create a custom multimodal model by fine-tunning a multimodal LLM on a multimodal dataset
Learning objective #4.   How to LoRA fine-tune a multimodal LLM to create a custom multimodal model. Learn to design/code LoRA fine-tune a Llama-3.2-11B-Vision .  (technique: Fine tune a Multimodal LLM on a multimodal datasets) . 
Learn to design/code LoRA fine-tune a Llama-3.2-11B-Vision . Note the dataset that combines image and text (dataset: amazon-product-descriptions-vlm).  (technique: Fine tune a Multimodal LLM on a multimodal datasets)


#5:  Chain of multimodal LLMs. 
Learning objective #5. How to chain multimodal LLMs to do interesting new challenging tasks.    How to do video question answering with multimodal LLM Llama-3.2-11B-Vision on short and long videos.   How to do video reasoning with Llama-3.2-11B-Vision on a 5 min video by combining various techniques (technique: Multimodal LLM chains,  action recognition from image frames, converting video into image frames and processing each clip separately and then chain multimodal LLM ) 

