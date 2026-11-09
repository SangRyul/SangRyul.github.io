---
layout: about
title: about
permalink: /
subtitle: Machine Learning Engineer at NAVER · ksr970330(at)gmail.com

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I'm Sangryul Kim, a `Machine Learning Engineer` at [NAVER](https://www.navercorp.com/en). I design and build `Agentic AI` systems, and right now that means LLM evaluation systems and agent prototypes for the content feeds in the NAVER app. Someone tells me the result they want; I work out an architecture that gets there and keep reshaping a working version from their feedback. Many of the people I build for don't write code, so I start from the outcome they care about and check whether the system reaches it.

How much room the model gets decides the architecture. Where the rules are clear, a single judge with a strict rubric does the job. Where the model has real choices to make, a planner proposes, code holds it to a fixed schema, and a blind judge scores the result without knowing which strategy produced it; when one viewpoint isn't enough, I split the work across cooperating agents, such as persona agents that each read an A/B test for one user segment while a synthesizer combines them. I write that orchestration in plain Python rather than starting from a framework.

Retrieval is where I started. I researched `RAG` and question answering at [KAIST](https://gsai.kaist.ac.kr/), where I received my M.S. in AI in Feb. 2025 with Prof. James Thorne in the [XFACT](https://xfact.net/) lab. In my last months there I interned at NAVER Search, training a Korean text embedding model, and afterwards designed a pipeline for [LINER](https://liner.com/)'s agent search service in which an LLM agent decides what to search for and gathers what it needs to answer a question. In the NAVER app I still build retrievers and run ranking experiments for the feeds.

Before graduate school, I interned as an ML engineer at [NAVER WEBTOON](https://www.webtoons.com/en/) and built the web service for the pre-release version of [IMQA](https://www.imqa.io/en/) at [ONYCOM](http://www.onycom.com/en/main.do). During my military service, I wrote software at the Cyber Operations Command. I studied Computer Science and Engineering at Chung-Ang University, with a minor in Applied Statistics.
