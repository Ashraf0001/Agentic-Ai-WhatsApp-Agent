<p align="center">
        <img alt="logo" src="img/ava_final_design.gif" width=1000 />
    <h1 align="center">📱 Ava 📱</h1>
    <h3 align="center">Turning the Turing Test into a WhatsApp Agent</h3>
</p>

<p align="center">
    <img alt="logo" src="img/whatsapp_logo.png" width=100 />
</p>

## Table of Contents

- [Course Overview](#course-overview)
- [Who is this course for?](#who-is-this-course-for)
- [What you'll get out of this course](#what-youll-get-out-of-this-course)
- [Course syllabus](#course-syllabus)
- [Getting started](#getting-started)
- [The tech stack](#the-tech-stack)
- [Contributors](#contributors)
- [License](#license)

## Project  Overview

What happens when [two ML Engineers](#contributors) with a love for sci-fi movies team up? 🤔

You get **Ava**, a Whatsapp agent that can engage with users in a "realistic" way, inspired by the great film [Ex Machina](https://www.imdb.com/es-es/title/tt0470752/). Ok, you won't find a fully sentient robot here, but you **will** have some pretty interesting Whatsapp conversations.

By the end of this course, you'll have built your own Ava too, capable of:


* Receiving and sending Whatsapp messages 📲
* Understanding your voice 🗣️
* Recognizing your images 🖼️
* Sending voice notes back 🎤
* Sharing updates about its "daily activities" 🚣
* Sending you images of its current activities 🖼️

>You can think of it as a modern reinterpretation of the Turing Test 🤣

Excited? Let's get started! 

<div style="text-align: center;">
    <video src="https://github.com/user-attachments/assets/6d1abefc-b4d8-4f66-9db6-a0e54b8df944" controls width="100%"></video>
</div>

---

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td width="20%" style="border: none;">
      <a href="https://theneuralmaze.substack.com/" aria-label="The Neural Maze">
        <img src="https://avatars.githubusercontent.com/u/151655127?s=400&u=2fff53e8c195ac155e5c8ee65c6ba683a72e655f&v=4" alt="The Neural Maze Logo" width="150"/>
      </a>
    </td>
    <td width="80%" style="border: none;">
      <div>
        <h2>📬 Stay Updated</h2>
        <p><b><a href="https://theneuralmaze.substack.com/">Join The Neural Maze</a></b> and learn to build AI Systems that actually work, from principles to production. Every Wednesday, directly to your inbox. Don't miss out!
</p>
      </div>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://theneuralmaze.substack.com/">
    <img src="https://img.shields.io/static/v1?label&logo=substack&message=Subscribe Now&style=for-the-badge&color=black&scale=2" alt="Subscribe Now" height="40">
  </a>
</p>

---



## What you'll do this app

* Build a fully working WhatsApp agent you can chat with on your phone
* Get a solid understanding of how to build LangGraph workflows
* Set up a long-term memory system using Qdrant as a Vector Database
* Use Groq models to power AI Agent responses
* Implement STT systems using Whisper
* Implement TTS systems using ElevenLabs
* Generate high-quality images using diffusion models, like FLUX models
* Process images using VLM models, like llama-3.2-vision
* Create chat interfaces using Chainlit
* Deploy agentic applications to Cloud Run
* Connect agentic applications to the WhatsApp API

## Getting started

Before you begin the course, there are a few things you need to do. 

I'm referring to the virtual environment creation, dependencies installation, `.env` file creation, etc. I know, it's very boring, but it's a necessary evil! 😅

All of this is detailed in the following doc: [GETTING STARTED.md](docs/GETTING_STARTED.md).

> Make sure you follow the instructions in the doc, as it's crucial for the course to work.

## Course syllabus

| Lesson Number | Written Lesson | Video Lesson | Description |
|---------------|----------------|--------------|-------------|
| <div align="center">1</div> | [Project overview](https://theneuralmaze.substack.com/p/meet-ava-the-whatsapp-agent) | <a href="https://youtu.be/u5y06cFK2WA?si=RCx__sJNtr2DYf0U"><img src="img/video_thumbnails/thumbnail_1_play.png" alt="Thumbnail 1" width="400"></a> | Understand the project architecture and the tech stack. |
| <div align="center">2</div> | [Dissecting Ava's brain](https://theneuralmaze.substack.com/p/dissecting-avas-brain) | <a href="https://youtu.be/nTsLL3htkCU?si=aSmSkpL-U3rzw9Za"><img src="img/video_thumbnails/thumbnail_2_play.png" alt="Thumbnail 2" width="400"></a> | Learn the basics of LangGraph and implement complex workflows using this framework. |
| <div align="center">3</div> | [Unlocking Ava's memories](https://theneuralmaze.substack.com/p/can-agents-get-nostalgic-about-the) | <a href="https://youtu.be/oTHqYEpdFXg?si=MXEvjUJ8Xbc6h9l2"><img src="img/video_thumbnails/thumbnail_3_play.png" alt="Thumbnail 3" width="400"></a> | Build a short-term memory system for graph state persistence and chat history. Also, implement a long-term memory system using Qdrant. |
| <div align="center">4</div> | [Giving Ava a Voice](https://theneuralmaze.substack.com/p/the-ultimate-ai-voice-pipeline) | <a href="https://youtu.be/RNmwvMjtIt0"><img src="img/video_thumbnails/thumbnail_4_play.png" alt="Thumbnail 4" width="400"></a> | Build a STT and a TTS pipeline to make Ava process input and output audio. |
| <div align="center">5</div> | [Ava learns to see](https://theneuralmaze.substack.com/p/reading-images-drawing-dreams-vlms) | <a href="https://youtu.be/LS7k-XFBbeo"><img src="img/video_thumbnails/thumbnail_5_play.png" alt="Thumbnail 5" width="400"></a> | Understand how to process images using VLM models. Implement an image generation pipeline using FLUX models. |
| <div align="center">6</div> | [Ava installs Whatsapp](https://theneuralmaze.substack.com/p/connecting-an-ai-agent-to-whatsapp) | <a href="https://youtu.be/dFsI4lnUkKo"><img src="img/video_thumbnails/thumbnail_6_play.png" alt="Thumbnail 6" width="400"></a> | Connect Ava to WhatsApp. Learn how to deploy a LangGraph application to Google Cloud Run. |

---


---

## The tech stack

<table>
  <tr>
    <th>Technology</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><img src="img/groq_logo.png" width="100" alt="Groq Logo"/></td>
    <td>Powering the project with Llama 3.3, Llama 3.2 Vision, and Whisper. Groq models are awesome (and fast!!)</td>
  </tr>
  <tr>
    <td><img src="img/qdrant_logo.png" width="100" alt="Qdrant Logo"/></td>
    <td>Serving as the long-term database, enabling our agent to recall details you shared months ago.</td>
  </tr>
  <tr>
    <td><img src="img/cloud_run_logo.png" width="100" alt="Cloud Run Logo"/></td>
    <td>Deploying your containers easily to Google Cloud Platform</td>
  </tr>
  <tr>
    <td><img src="img/langgraph_logo.png" width="100" alt="LangGraph Logo"/></td>
    <td>Learn how to build production-ready LangGraph workflows</td>
  </tr>
  <tr>
    <td><img src="img/elevenlabs_logo.png" width="100" alt="ElevenLabs Logo"/></td>
    <td>Amazing TTS models</td>
  </tr>
  <tr>
    <td><img src="img/together_logo.png" width="100" alt="Together AI Logo"/></td>
    <td>Behind Ava's image generation process</td>
  </tr>
</table>





