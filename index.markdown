---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: single
classes: wide
author_profile: true
excerpt: ""
permalink: /

---


<!--<h2>Recent Posts</h2>
{% for post in site.posts offset:1 limit:2 %}
... Show the next two posts ...
{% endfor %}-->



# About me

My interests lie in researching non-verbal aspects in speech communication (also known as paralinguistics) to develop voice and speech technology that enhances human-human and human-machine communication. I have worked on/am working on for example:

 							
- Automatic analysis of paralinguistics (e.g., affective states, mental states, physical states, non-verbal vocalizations)
- Spoken Conversational AI (e.g., automatic analysis of laughter, non-verbal vocalisations, backchanneling, prosodic synchrony in conversation)
- Human-agent/robot communication (e.g., voice design and interaction for robots)

I am currently working both at Radboud University (Centre for Language Studies) and University of Twente (Human Media Interaction). Previously, I was employed by TNO Human Factors in Soesterberg where I worked towards my PhD on automatic emotion recognition in speech and automatic laughter detection. During my master research at Radboud University in Nijmegen, I worked on automatic pronunciation error detection in second language learners’ speech. I obtained my Master's in (computational) linguistics from Utrecht University.

# Some keywords
paralinguistics / spoken conversational ai / voice technology / social signal processing / affective computing / multimodal interaction / speech prosody / non-verbal vocalisations / laughter / dialogue / embodied conversational agents / human-human interaction / human-agent interaction / human-robot interaction

# Recent academic service (a summary)

- **Interspeech:** 2026 (Area Chair, area 11), 2025 (General Co-Chair), 2023 (Lead Area Chair, area 3), 2022 (Lead Area Chair, area 3), 2021 (Lead Area Chair, area 3), 2017 (Area Chair, area 3), 2015 (Area Chair, area 3), reviewer since 2011
- **ACM ICMI:** 2026 (Special Sessions CoChair), 2024 (Program Co-Chair), 2023 (Publicity Chair), 2021 (Social Media Chair), 2020 (General Chair), 2012-2019 reviewer or Senior Program Committee
- **ACM/IEEE HRI:** 2024, 2023 (PC member), 2021, 2019, 2016, 2015
- **Speech Prosody:** 2026, 2024, 2022, 2021, 2020, 2018, 2016, 2014
- **IEEE International Conference on Affective Computing and Intelligent Interaction (ACII):** 2024, 2023, 2022 (Program Co-Chair), 2021 (Senior PC), 2019 (Senior PC, Tutorial Chair), 2017 (Social Media Chair, Senior PC), 2015, 2013
- **ACM International Conference on Intelligent Virtual Agents (IVA):** 2024, 2021, 2019, 2018, 2016 (Senior PC), 2015 (Doctoral Consortium Chair)
- **HRI Pioneers:** reviewer since 2021
- **IEEE ICASSP, LREC:** i also review for these conferences
- **Member of Editorial Board Computer Speech and Language:** 2021 - 2025
- **Associate Editor IEEE Transactions of Affective Computing:** 2019 - 2023
												

# Most recent news

{% for post in site.posts limit:3 %}
  <p>
    <a href="{{ post.url | relative_url }}">{{ post.title}}</a>
  </p>
{% endfor %}