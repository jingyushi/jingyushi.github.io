---
layout: post
title: My Taste in Human-AI Interaction
date: 2023-10-30 16:40:16
description: What I see and not see from the current research in human-AI interaction.
tags: writing
categories: personal
---
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/momo.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Wingman (Facai) and Yuumi under my bed.
</div>

As a Ph.D. student who had had no experience in HCI research before, I suffered a lot when I was trying to transit my ways of thinking from an AI developer (or say a Machine Learning engineer or a Deep Learning engineer?) to an HCI researcher. My suffering majorly resulted from the fact that I did not know what was held dear in the HCI community (and that I had not formed a taste of research in general myself). Never, do I dare to announce my expertise at solving HCI problems, yet I wish to summarize some points that might contribute to anyone who are interested in both topics (AI and HCI) and my take-aways through my learning and scattered moments of Eureka.

The very first thing I realized was that HCI or Human-AI Interaction (HAII, I might use them interchangably but I meant HAII mostly, but some claims can be generalized to the broad topic of HCI. I would slack off here a bit to welcome some thinking.) research emphased more on the functionality and functions of a computing or an AI system, while AI research preferred the performance over an specific problem or task or the abilities to solve novel forms of problems and tasks. Of course, I am not asserting that exclusively HCI research does not care about performance or AI research is not functional, but rather pointing out an interesting phenomenon or say difference between HCI and AI that is induced by the very essences of both topics: When we talk about AI alone, we do not bring in the human factor. And when human factors are involved, researchers have to bring in a whole different set of **metrics** to evaluate the systems. Such **metrics** tend to be diverse and unaligned, because humans, as compared to (existing) computing systems, are way too complex and dynamic, not to mentioned when human factors are to be considered across diverse contexts or tasks.

What are these metrics? To answer this question, I would like to go back to the functionality and functions of a computing/AI system aforementioned. I define functionality as the inherent quality of a system to work for some purposes of some users, while functions as the nuanced capabilities of a system to accomplish some specific tasks. For example, an image classification network has the function to classify a given image, but it does not have the functionality to work for image classification purposes until an integrated system is developed to allow some target users to use all the functions with an interface.

Metaphorically, let's say HCI is the design of using some tool and AI is the function of the tool. Consider a hammer, where the head is AI, with which we smash (functions), the handle is the HCI design, and the ideology that the momentum of the head can be increased by grabbing and swinging the handle (functionality) is the utimate principle that we follow to make a tool **usable**. To assess the functionality and functions of a computing, **metrics** are designed.

How do we design better heads and better handles for hammers? This question sounds easy if we seperate the heads and the handles - On the one hand, we can improve the performance of the AI on the specific task by introducing novel architectures, better algorithms, or utilizing more information. On the other hand, we can make the handles more human-friendly by designing more intuitive interfaces, increasing the system usability, or making it adaptive to a larger user groups. However, but the principle that we are following couples the heads and the handles and therefore complicates the problem. It is impossible (or at least constrained by strong assumptions) to consider the heads without considering the handles. E.g. the specific tasks have to be meaningful to certain users in some impactful real-world problems. More frequently, designing the handles depends on the heads. The interactions to be enabled by the systems are dependent of the functions of the AI models/algorithms, and the more coupled systems allow deeper interactions with the architecture.

I personally discover that there exists a trade-off between the depth of the HAII and the user-friendliness of the HAII. When interactions that allow users to tweak or modify the architecture, the algorithms, or the mechanism of an AI system, they shrink the possible user groups because of the expertise in AI they require. Put simply, interactions that change the AI performance require the users to know what their actions lead to, i.e. they know how AI works.

Is there anyway of allowing users interact deeply with the AI without expertise? Yes, and I think that is the very core and essence of HAII research, which is to map the human-intuitive interactions to complex interactions that changes the AI. For the users, they only need to do simple actions that, in their expectation, will lead to some results. The tasks for HAII researchers are
- to model the mapping between the human-intuitive interactions to the change in the AI mechanism,
- and build a surrogate model that depicts the cognitive mapping between the human input and their expectation of output (not the value of the output but the form and mechanism of the output).

I will come up with an example to better depict what I mean here. But going back the point that the HAII problems are coupled by the factors of the AI functionality and functions and interaction principles, I would like to assert a gap that I identify between current research and the future of HAII: the research of AI and the research of HAII are decoupled. Communities follow different metrics, which I am not saying is wrong, but merely questioning the existence of a possible general framework that considers not only the performance of an AI model on tasks but also its usability in the context of the designated tasks? Envisioning this framework, I think decoupled research is not enough. What we have been doing is like digging up a tunnel from two sides (AI and HCI) of a mountain, with no guarantee that the two sides will meet. What if they do not meet? (I do not know) What should be done to align or share the interests of both sides to guarantee or foster a convergence?


draft:
- the capabilities of AI systems solving novel tasks enable new domains to explore in HCI
- how well under some measurement should a computing system perform in a task to be considered **usable**? What is the definition of **usable**.
To be continued...