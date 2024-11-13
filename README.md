# Multi-Modal Models with Hugging Face  - Course Outline

##  This is a submission towards Datacamp's Audition process
![data camp](https://assets.bitdegree.org/online-learning-platforms/storage/media/datacamp-workspace-review-logo-big.o.png)


## What problem(s) will students learn how to solve?

1. <sub>[ Concept + Problem Solving + Architecture ] </sub> How to solve a real world use case by designing an architecture with Multimodal AI.

    - Use case: Assistive technology for Persons with Visual impariment  
    - Use case: Text search to reterive product images in eCommerce store 
    - Use case: **Your use case**

2. <sub>[ Design + Code ] </sub> Design and implement **Multimodal Human Computer Interaction experiences**

    - <sub>[Basic Level] </sub> Understand different modalites and code different multimodal tasks such as VQA (Visual Question Answering).  
    - <sub>[Medium Level] </sub> Can you combine two multimodal models to design a new multimodal experience. Create an app for multilingual speech interaction with visual question answering task ( **Multilingual Speech interaction + VQA** ).
    - <sub>[Architecture Choices + Analysis] </sub> **When to use what?** Cost vs Latency vs Accuracy trade offs of different multimodal models. 

3. <sub>[ Concept + Data + Design + Code ] </sub> Design and implement Multimodal Few Shot Learning 

    -  **Few Shot Learning in Multimodal models vs Unimodal models**  
    -  Zero/ One / Few Shot Learning Techniques
    -  Providing Contrastive examples
    -  <sub>[Design + Code] </sub> How to provide one-shot multimodal examples to Llama 3.2 Vision
    -  <sub>[Design + Code] </sub> How to provide Few-shot Image examples to GEMINI  (Contrastive examples)
    -  <sub>[Design + Code] </sub> How to provide Few-shot Video examples to GEMINI
    -  <sub>[Advanced Design + Code] </sub> How to find needle in a multimodal haystick  (Search for a visual object in a video)
     
  
4.  <sub>[ Concept + Dataset Design + FineTuning + Code ] </sub> Create a **custom multimodal model by fine-tunning a multimodal LLM on a multimodal dataset**

    -  <sub>[Concept] </sub> PeFT, LoRA, QLoRA of Multimodal LLMs 
    -  <sub>[Design + Code] </sub> How to Fine tune a Multimodal LLM on a multimodal datasets


5.  <sub>[ Concept + Design + Code ] </sub> **Got lot of visuals to send to MLLM? What to do when the MLLM Context window limits the visual data in multimodal prompts?** Optimizing for inference cost in multimodal LLMs  

    -  <sub>[Concept + New idea] </sub>  Does the context window limit the number of few shot visual examples?  Learning to chain Multimodal LLMs.  Learning in image modality vs text modality.
    -  <sub>[Concept + New idea] </sub>   **LLM chains in the context of multimodality** ,  **Learning to learn abstract visual concepts by MLLM chains**
    -  <sub>[New idea + Code] </sub> How to learn from many visual examples with chaining of multiple MLLMs?


6.  <sub>[ Concept + Design + Code ] </sub> **Multimodal embeddings, Search accross modalities , Multimodal Latent space arthimetic** ,  Cross-modal Reterival 

    -  <sub>[Concept + Code] </sub>  Joint embedding across six different modalities - images, text, audio, depth, thermal, and IMU data
    -  <sub>[Concept + Code] </sub>  Multimodal Latent space arthimetic
    -  <sub>[Concept + Code] </sub>  Cross-modal Reterival 

7.  <sub>[ Concept + Design + Code ] </sub> **Responsbile AI principles for Multimodal models**   

    -  <sub>[Concept] </sub>  Ethical use of multimodal AI.    
    -  <sub>[New idea + Design + Code] </sub>  **How to adapt a multimodal LLMs for lower age group (children age<x)?**  Designing Guardrails in input and output of multimodal LLMs

8.  <sub>[ Concept + Design + Code  ] </sub> Responsible generation of multimodal content    

    -  <sub>[Concept] </sub>  Safety / Creating safety gaurdrails for image generation tasks 
    -  <sub>[New idea + Design + Code] </sub>  Implement a custom guardrail for generation. **How to combine Diffusion models with VLMs for responsible image generation?**
      
9.  <sub>[ Business case + Architecture ] </sub> **Why use Multimodal models with HuggingFace?**

    -  <sub>[Business case] </sub> Concerns in moving Enterprise data beyond network firewall? On-premise multimodal models vs GEMINI.     
    -  <sub>[Architecture concept] </sub> On-premise vs API

10.  <sub>[ Captsone Project + Design + Code + New idea ] </sub> **Video reasoning with LLama Vision. How to do video question answering in long videos?**  ,  **Bonus: Real world deployment of multimodal AI? Safety checks in multimodal prompts**

     -  <sub>[Concept] </sub>  Can LLama 3.2 Vision process videos?
     -  <sub>[Concept + New idea] </sub>  Does the context window limit the number of few shot visual examples?  
     -  <sub>[Design + Code] </sub>  How to process short video with LLama? **Action recognition** of 1 minute video with LLama 3.2 Vision.  (convert video into image frames) 
     -  <sub>[New idea + Design + Code] </sub> **How to process long video with LLama?** How to design and implement Video question anwering for 5 min videos with LLama  Vision
     -  <sub>[Design + Code] </sub>  Design custom Safety guardrails for video inputs to multimodal LLMs : How to design and implement safety gaurdrails for multimodal prompts 
     -  <sub>[New idea + Design + Code] </sub> **Safety checks: Detecting malicious prompting** If the prompt contains a combination of visual and text that causes the MLLM to reason over explict content , how to detect such prompts.    Checking for safety in a combination of text and visual

11. end 

-------

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

