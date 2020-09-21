---
layout: post
title:  "Papad Annotating Audio"
description: "Papad aims to be the audio visual publishing platform for the low literates, without barriers of knowing to read and write."
categories: [ web annotation, papad, audio annotation ]
author: janastu
featured: true
image: https://i.imgur.com/y5QHHzQ.png
toc: false
comments: false
---


> History is something that very few people have been doing while everyone else was ploughing fields and carrying water buckets.
Sapiens: A Brief History of Humankind, Book by Yuval Noah Harari - page 114
>

Humans, *Homo Sapiens* in particular, are believed to be telling and re-telling stories since as far as we can go to the earlier civilizations and far beyond. As a collective we have been able to weave incredibly complex network of stories over the years. From which have emerged our current culture's fictions, beliefs, rituals, history and more. While if that's what we engage in a constant learning process with history, then can we imagine futures that make more sense to us and don't alienate us? 

### Can we reshape, reinterpret, and reinvent these ways of storytelling?

Re-narration is an attempt to bridge digital divide  between grass root rural culture and urban culture. It can assist anyone in voicing their views on their community related topics. It would be a way to preserve and revive the knowledge for next geneartion. As a tool to share, learn and explore from other communities' perspectives on art, culture, education, technology, tradition for health and farming.

Though we need these capabilities, we still haven't able to do it even after 25 years of internet and browsers. We weren't producing as much Audio and Audiovisual content for the web until recently. With that happening now, there is a need for tools that can enable contextual engagement with content for different users. The way that the internet is navigated right now is  primarily through hyperlinks and modularised text. Sense making on the internet therefore becomes much harder due to the Euro-centric gatekeeping that is put up by text-based navigation. This definitely brings up barriers for low-literate communities to access the internet.

We started to explore if we can take the current capabilities of the browser, and resolve these shortcomings? With a collaborator we worked with the existing technologies - HTML, CSS, JS - to  release a browser extension as a proof of concept. [Bookmark Audio Fragment](https://addons.mozilla.org/en-US/firefox/addon/bookmark-audio-fragment/), replaces the default audio player of the browser, also adds features to select a moment/range on the audio, copy link to selection to share with others, and finally save the bookmark to your browser. Though we could address the issues with the user interface, this experiment still is a personal application at best. Now we wanted to see, what would we need to run a server and allow for collaboration to listen, tag, describe, and remix.
![modular tagging of audio files](https://i.imgur.com/y5QHHzQ.png)

> Eventually I hope we’ll get open web annotation of audio and video that’s fully native, meaning not only that the standard players support selection, but also that they directly enable creation and viewing of annotations. Until then, though, this flavor of audio/video annotation — let’s call it annotating on media — will require separate tooling both for selecting quotes, and for creating and viewing annotations directly on those quotes. 
> **Jon Udell** wrote on 10th March, 2018 in his blog post here - https://blog.jonudell.net/2018/03/10/open-web-annotation-of-audio-and-video/
> 

We started working on the Audio Tagger via Development Alternatives in 2015. The intent was to explore how to organize and understand the large volume of calls that were received by community radio stations. Soundcloud has a great feature through which you can time-index the comments. This seemed quite promising to us. Time-indexed comments can help in organising these files as they open up new ways 

> (...) selection in audio and video isn’t like selection in text. Nor is it like selection in images, which we easily and naturally crop. Selection of audio and video happens in the temporal domain. If you’ve ever edited audio or video you’ll appreciate what that means.
> **Jon Udell** wrote on 10th March, 2018 in his blog post here - https://blog.jonudell.net/2018/03/10/open-web-annotation-of-audio-and-video/


Another important need for organising such crowd-sourced data is the capability to annotate the material. This is an important aspect of contextualising the media. While tools for annotating on text is already evolving on the web, with many services like [Hypothes.is](https://hypothes.is), browser standards such as chrome's [Scroll to Text fragment](https://chromestatus.com/feature/4733392803332096), and community efforts like the [Apache Annotator](https://annotator.apache.org/). In media such as audio and video, annotation tools serve to mark out fragments of the media that are interesting or specific to a context. 

> (...) All audio and video editors support making and checking selections. But what’s built into modern browsers is a player, not an editor. It provides a slider with one handle. You can drag the handle back and forth to play at different times, but you can’t mark a beginning and an end. 
> **Jon Udell** wrote on 10th March, 2018 in his blog post here - https://blog.jonudell.net/2018/03/10/open-web-annotation-of-audio-and-video/
> 

Our research focus has been on web accessibility for Indian needs in the local context of culture, literacy, and socio-economic conditions. Since, most of the internet still is dominated by text-based mediums, it excludes many people, cultures and languages. Until the recent popularity of cheap 4G networks, it wouldn't have been possible for us to imagine the high quality of sound and video deliveries. The popularity of podcasts and other video streaming services has made us wonder if there was a hyperlink equivalent in HTML for audio/video mediums on the internet/accessed through one's browser. 

Papad allows the community to upload audio recording to a local server, browse, listen to audio and tag the entire audio or relevant parts (fragments), annotate a image tag, which can later be used in making audio visual stories that is relevant for the communities. Papad aims to be the audio visual publishing platform for the low literates, without barriers of knowing to read and write.


Written and edited by Janastu team's Bhanu, TB Dinesh, Micah and Shafali.
