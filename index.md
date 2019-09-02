---
layout: default
---


# The project

**SpeechBrain** is an **open-source** **all-in-one** speech toolkit
relying on [PyTorch](https://pytorch.org).

The goal is to develop a *single*, *flexible*, and *user-friendly* toolkit that can be used to easily develop state-of-the-art speech technologies of different types, including systems for **speech recognition** (both end-to-end and HMM-DNN), **speaker recognition**, **speech separation**, **multi-microphone signal processing** (e.g, beamforming), **self-supervised and unsupervised learning**, **speech contamination/augmentation**,  and many others.
The toolkit will be designed to be a stand-alone framework, but simple interfaces with well-known toolkits, such as [Kaldi](http://kaldi-asr.org) will be implemented as well.

**SpeechBrain** is currently **under development** and has been announced in September, 2019. A first alpha version will be available in the next months.  

Stay tuned!

# Why a single toolkit?
Some speech processing toolkits have gained popularity in the last years. For speech recognition purposes, for instance, [Kaldi](http://kaldi-asr.org) is an established framework.  Some other speech recognition toolkits have been recently developed using the Python language such as [PyTorch-Kaldi](https://github.com/mravanelli/pytorch-kaldi), [PyKaldi](https://github.com/pykaldi/pykaldi), and [ESPnet](https://github.com/espnet/espnet). Beyond speech recognition, a variety of other toolkits have been developed for speech applications such as speech separation, speech enhancement, speaker recognition, and language model training.

Even though many of these frameworks could be very helpful for the specific task for which they are designed, our experience in the field suggests that having a single, efficient, and flexible toolkit can significantly **speed up research and development** of speech and audio processing techniques. It is significantly easier to familiarize oneself with a single toolkit than to learn several different frameworks. Moreover, the use of a **single platform** for different speech and audio applications makes it more natural to develop **multi-task systems** that jointly solve different problems.


# Why PyTorch?
To ensure the needed flexibility and the user-friendliness of our system, we think that our platform must be built on the top of PyTorch for the following reasons:  
- PyTorch is a well-designed, flexible, popular, and well-document toolkit and a very large community has adopted it.
- most speech applications rely on deep learning and signal processing techniques, that can be naturally implemented in PyTorch.

- we can easily perform the processing steps either on GPUs or CPUs.
- we can employ end-to-end differentiable systems, where the gradient can potentially flow through all the different parts of the architecture, including parts solving different audio and speech tasks.  

# How to collaborate
Our goal is to build a large community working on this ambitious project. Feel free to contact us if you are interested to give a contribution.


# Join us!
Thanks to our [sponsors](#Sponsors), we are looking for talented interns (3-6 months internships) at Mila (Montréal, QC, Canada) with the core development team. The ideal candidate is a PhD student with a strong experience in both PyTorch and speech technologies.

If you are interested to hear more about these opportunities, please contact speechbrainproject@gmail.com.


# Sponsors
- Mila
- Samsung
- NVIDIA
- Dolbly

# Current collaborators
- Facebook
- IBM
- Fluent AI
