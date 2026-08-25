# Introduction

Hi, I'm Thiago. I like building AI projects that solve real-world problems. My main project is Intelligent CareGuardian, a privacy-first patient monitoring system that runs locally on NVIDIA Jetson Orin Nano. 

## Intelligent CareGuardian 

A privacy-first edge-AI system that detects falls and other concerning events and alerts caregivers. I built a patient care system called Intelligent CareGuardian. It is an AI-powered system designed to help monitor a patient’s safety and well-being. It uses a camera, a Jetson Orin Nano, and pose-detection artificial intelligence to follow the patient and predefined behaviors that may indicate discomfort, such as hand placement near the chest, stomach, or eyes. The system estimates the locations of different body parts and detects when the patient’s hands or wrists remain near an affected area. When it detects a concerning event, it first will have a confirmation system, where you have to hold it for 5 seconds, it can then record the event, take a screenshot, and send an email alert. It also includes face blurring for privacy, voice interaction, scheduled reminders, and daily email summaries. My goal is to create a helpful care assistant that can monitor patients locally and quickly notify a caregiver when assistance may be needed. Video processing and AI inference run locally on the Jetson Orin Nano, reducing the need to send sensitive video to cloud AI services.

## Summary of what I built

Edge AI: Runs pose detection locally on Jetson Orin Nano.
Event detection: Detects falls and recognizes predefined body/hand-position patterns associated with potentially concerning events.
Alerts: Can record an event, capture a screenshot and notify a caregiver.
Privacy: Processes camera data locally and supports face blurring.
Assistant features: Voice interaction, scheduled reminders and daily summaries.

## What I'm working on right now

Right now, I am working on exploring reinforcement learning papers to see if it could possibly help my project. We have a journal club to talk about different reinforcement learning methods from papers.

<img width="998" height="677" alt="Screenshot 2026-08-24 085026" src="https://github.com/user-attachments/assets/43f159d1-4782-4995-9e20-64466c4133ea" />

<img width="746" height="757" alt="Screenshot 2026-08-24 085303" src="https://github.com/user-attachments/assets/46a37f58-561e-4109-b6bf-3ccc4adeeda1" />
