---
layout: post
title:  "Enabling Safe Storytelling for Rural Women through Voice Anonymity"
excerpt: "Making storytelling more safer"
author: Janastu
featured: true
image: /assets/images/radio-demo.jpg
toc: false
comments: true
tags: people, AI, COWMesh, village, Janastu
---
# Enabling Safe Storytelling for Rural Women through Voice Anonymity

In the rural communities we work with in Karnataka, many women are comfortable sharing their experiences orally, but hesitate to express them publicly. This hesitation is not only due to literacy barriers or lack of access to devices, but also due to social risk.
Women often want to talk about their stories, experiences and issues such as domestic violence, caste and gender discrimination. However, sharing these experiences openly can lead to stigma or conflict within their families and communities.
At the same time, most digital platforms are designed for text-based interaction, making them difficult to use for people who rely more on oral communication. This creates a gap where women have stories to share, but lack safe and accessible ways to do so.


We addressed this challenge by combining community spaces, voice-based platforms and privacy-focused technology.


## Setting up a local digital kiosk

![Demo](/assets/images/radio.jpg)

We set up a digital kiosk with a microphone in a craft centre where women regularly gather. By placing the technology in a familiar environment, we made it easier for women to explore and use it comfortably. They began using the kiosk to access internet, record stories, listen to others and access local digital resources.

## Creating a community radio platform

![Radio Page](/assets/images/Screenshot_20260430_210705.png)

We developed a community radio application that runs locally within a WiFi mesh network. This allows audio content to be shared and accessed without internet connectivity. Women could record and listen to stories within their own community.

## Building a privacy-focused voice anonymization system

To address concerns around safety and identity, we developed a fully automated, privacy-focused voice anonymization pipeline integrated directly into the community radio system.

Instead of relying on speech-to-text tools such as Whispering, which presented limitations in handling local dialects and required higher computational resources, we shifted to a voice-to-voice conversion approach. Using the Retrieval-based Voice Conversion (RVC) framework, we built a system that transforms voices without converting them into text, allowing us to bypass language constraints and work effectively on low-spec hardware.

The entire system runs locally on our server, ensuring that no data leaves the community network. When a user uploads an audio recording, it automatically triggers a background anonymization process. The transformed audio is then made available on the community radio platform.

We also used open-source Indian voice models and implemented an interface that allows administrators to upload and manage voice models over time. To improve accessibility, the radio interface was localized with Kannada translations.

Click to check out voice anonymity code repo: [link](https://gitlab.com/servelots/ai-voice-anonymizer)

## Presenting the work and sharing learnings

we also presented our work at the workshop on Indigenous Languages and Small Language Models: Creating Open Source Protocols for Community Toolkit. The presentation focused on the challenges faced by low-literate rural communities particularly women in accessing digital technologies and how privacy-focused voice technologies can support safer participation and storytelling.

The presentation also discussed the importance of building locally relevant and community-driven AI systems, especially for low aand semi-literate communities that are often excluded from mainstream language technologies.

You can read more about the workshop here:

[Click here to know about workshop](https://llncolab.notion.site/Indigenous-languages-and-Small-Language-Models-Creating-Open-Source-Protocols-for-Community-Toolkit-2edf2a1a5b73801aab03cbd92683da3d)

Click here to access the ppt [Link](https://files.janastu.org/s/tNLXqj2cQ8oLLDR)

We have also demonstrated how AI voice conversion converts the original voice into different voices and how animated story looks like.
Click here to access the demo audio and video content [Link](https://files.janastu.org/s/bpGKc9NLkW2GqWR)

## Understanding feminist vocabularies in local dialects

we conducted discussions and workshops with women to understand the vocabularies and expressions they use while talking about gender, caste and everyday struggles.

These workshops helped us better understand how women articulate issues related to discrimination, care work, mobility, safety and social expectations in their own language practices.

In the long term, this work can contribute towards building small language models and language resources that are more grounded in the lived realities, dialects and communication styles of rural communities rather than depending entirely on standardised or urban-centric datasets.

## From silence to shared conversations

Many women were initially hesitant to record her voice, as they feared that speaking publicly about her experiences might lead to social consequences. During a demonstration session, they observed how voice anonymity could alter the identity of a recording.
After several interactions and gaining confidence in the process, they started to record folklore stories, their stories, experiences and issues related to gender and caste discrimination, domestic violence, education and about villages. When their story was later played on the community radio platform, it resonated with other women, who began sharing similar experiences.
That moment marked a significant shift, as an issue that was previously considered personal became part of a collective conversation. The ability to speak anonymously enabled participation, which in turn enabled shared understanding and dialogue.

