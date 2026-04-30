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

## From silence to shared conversations

Many women were initially hesitant to record her voice, as they feared that speaking publicly about her experiences might lead to social consequences. During a demonstration session, they observed how voice anonymity could alter the identity of a recording.
After several interactions and gaining confidence in the process, they started to record folklore stories, their stories, experiences and issues related to gender and caste discrimination, domestic violence, education and villages. When their story was later played on the community radio platform, it resonated with other women, who began sharing similar experiences.
That moment marked a significant shift, as an issue that was previously considered personal became part of a collective conversation. The ability to speak anonymously enabled participation, which in turn enabled shared understanding and dialogue.

