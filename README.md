# Hey, I'm Mete.

I'm building Evreon AI and Project Atlas.

I'm 21, based in Budapest, from Ankara. Most of my work sits in the same place: hospitals, messy workflows, and AI that has to be useful after the demo is over.

## What I'm Building

**Project Atlas** -> a local abdominal CT agent stack.

DICOM in -> multi-window CT preprocessing -> YOLO detection -> anatomy masks -> research layers -> FHIR report -> Vue viewer.

The current repo-audited pipeline runs 4 active inference models in about 60-70 seconds on a full-volume CT. Clean held-out macro AUROC is about 0.935, with AAA and pancreatitis currently the strongest deployed classes.

A TUSEB 2026-A3 grant is confirmed for clinical validation at Ankara Bilkent City Hospital. I built the detection stack behind the project.

The point is not "one more model." Hospitals already have enough tools. The hard part is making the output fit the way doctors actually work.

## Other Things I've Built

**NeuroLens** -> medical imaging project. I led business, data collection, partnerships, and pitch. It won €10K at a mesh hackerhouse and reached 5 LOIs.

**ClaimGraph** -> research-claim verification with graph analysis. 2nd place at the Agentic Discovery Hackathon.

**BrailleBuddy** -> voice-first braille tutor with a physical ESP32 braille cell. Grand Prize + ElevenLabs Prize at the 2nd Hungarian Robotics Hackathon.

**Overseer** -> shipped 24/7 AI intelligence monitor: 80+ sources, Telegram bot, web dashboard, Docker + Nginx + SSL.

## Stack

Python, PyTorch, YOLOv11, MONAI, TotalSegmentator, VISTA3D, pydicom

FastAPI, SQLAlchemy, FHIR R4, OpenRouter, CrewAI, pgvector

Vue, Next.js, React, Tailwind, Supabase, Docker Compose, Nginx, PM2, Hetzner VPS

## Let's Talk

If you're a doctor frustrated with hospital IT, an engineer who wants to work on healthcare infrastructure, or someone who thinks AI should actually work in the real world:

[![Website](https://img.shields.io/badge/Website-evreonai.com-2B2A26?style=for-the-badge&logo=safari&logoColor=white)](https://evreonai.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/hasan-mete-erdogan-a36975285)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/hmeteerd)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hmeteerd5@gmail.com)
