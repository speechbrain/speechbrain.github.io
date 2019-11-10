---
layout: default
---


# The project

**SpeechBrain** is an **open-source** and **all-in-one** speech toolkit
relying on [PyTorch](https://pytorch.org).

The goal is to create a *single*, *flexible*, and *user-friendly* toolkit that can be used to easily develop state-of-the-art speech technologies, including systems for **speech recognition** (both end-to-end and HMM-DNN), **speaker recognition**, **speech separation**, **multi-microphone signal processing** (e.g, beamforming), **self-supervised and unsupervised learning**, **speech contamination / augmentation**,  and many others. The toolkit will be designed to be a **stand-alone framework**, but simple interfaces with well-known toolkits, such as [Kaldi](http://kaldi-asr.org) will also be implemented.

**SpeechBrain** is currently **under development** and has been announced in September 2019. A first alpha version will be available in the next months.

[See a short introductory video on the SpeechBrain project](https://youtu.be/XETiKbN9ojE)

Stay tuned!

# Why SpeechBrain?
Speech processing toolkits have gained popularity in the last years. For automatic speech recognition (ASR) purposes, for instance, [Kaldi](http://kaldi-asr.org) is an established framework. Some other ASR toolkits have been recently developed using the Python language such as [PyTorch-Kaldi](https://github.com/mravanelli/pytorch-kaldi), [PyKaldi](https://github.com/pykaldi/pykaldi), and [ESPnet](https://github.com/espnet/espnet). Beyond speech recognition, a variety of other solutions have been developed for speech-related applications, such as speech separation, speech enhancement, speaker recognition, and language model training.

Even though many of these frameworks could be very helpful for the specific task for which they are designed, our experience in the field suggests that having a *single*, *efficient*, and *flexible* toolkit can significantly **speed up research and development** of speech and audio processing techniques. Indeed, it is significantly easier to familiarize oneself with a single toolkit than to learn several different frameworks. Moreover, the use of a **single platform** for different speech and audio applications makes it more natural to develop **multi-task systems** that jointly solve different problems. It is also easier to build a strong and fruitful community when considering a unique and self-contained framework.

# Why PyTorch?
To ensure the needed *flexibility* and the *user-friendliness* of our system, we think that our platform must be built on the top of PyTorch for the following reasons:  
- PyTorch is a well-designed, flexible, popular, and well-documented toolkit with a very large community.
- Most speech applications rely on deep learning and signal processing techniques, that can be naturally implemented in PyTorch.
- Processing steps are performed either on GPUs or CPUs.
- It is feasible to design end-to-end differentiable systems, where the gradient can potentially flow through all the different parts of the architecture, including parts solving different audio and speech tasks (*e.g. joint training, multi-task learning, cooperative learning).

# Toolkits
During the project, we plan to collaborate with the PyTorch Audio team of Facebook and with NVIDIA, that has recently developed the Neural Modules toolkit (Nemo), which provides flexibility and modularity to accelerate speech applications.

# How to collaborate
A strong toolkit needs a strong community. While a core team will be dedicated to develop and maintain the core functionalities of SpeechBrain, we need the help of the entire community to extend this ambitious project to numerous and various applications. Feel free to contact us, if you are interested to contribute.

# Join us!
Thanks to our [sponsors](#Sponsors), we are hiring talented interns (3-6 months internships) that will work at Mila (Montréal) with the core development team. The ideal candidate is a PhD student with a strong experience in both PyTorch and speech technologies. Send us your CV if you are interested in this opportunity!

# Contact us
If you are interested to collaborate or sponsor us, or if you simply want to hear more about this project, please **contact us at *speechbrainproject@gmail.com***.

# SpeechBrain and Social Good
The development and use of SpeechBrain technologies are parts of a policy of concern for AI for the “social good”. Therefore, all partners, collaborators and participants declare having read the [Montreal Declaration for a responsible development of AI](https://www.montrealdeclaration-responsibleai.com), adhere to these principles and implement them as part of the SpeechBrain project.

# Current Sponsors

![Mila](https://speechbrain.github.io/assets/logo_mila_small.png)
![Nvidia](https://speechbrain.github.io/assets/logo_nvidia.png)
![Dolby](https://speechbrain.github.io/assets/logo_dolby.png)
![Samsung](https://speechbrain.github.io/assets/samsung_official.png)

# Current collaborators
![LIA](https://speechbrain.github.io/assets/logo_LIA.png)
![LIA](https://speechbrain.github.io/assets/logo_lium.png)
![PyTorch](https://speechbrain.github.io/assets/logo_pytorch.png)
![IBM](https://speechbrain.github.io/assets/logo_ibm.png)
![FluentAI](https://speechbrain.github.io/assets/logo_fluent.png)
