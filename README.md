# Hi, I'm Shahid 👋

**Computer Vision / ML Engineer** building real-time AI systems, video analytics pipelines, and production infrastructure.

I enjoy working close to the system — from **computer vision models and GPU inference to distributed services, debugging, optimization, and deployment**.

Most of my learning comes through building and breaking things: tracing failures, reading logs, profiling bottlenecks, experimenting with different approaches, and understanding **why a system behaves the way it does**.

---

## 🧠 What I Work With

- **Computer Vision & Deep Learning**
  - Object Detection & Tracking
  - OCR / Vision-Language Models
  - ROI & spatial analytics
  - Multi-camera video analytics
  - Real-time inference

- **AI / ML Engineering**
  - Python
  - OpenCV
  - YOLO
  - NVIDIA DeepStream
  - TensorRT
  - NumPy

- **Backend & Distributed Systems**
  - FastAPI
  - Apache Kafka
  - Redis
  - REST APIs
  - Concurrent processing
  - Inter-process communication

- **Infrastructure & Deployment**
  - Linux
  - Docker / Docker Compose
  - Kubernetes
  - NVIDIA Container Toolkit
  - MediaMTX

---

## What I've Built

### Real-Time Airport Baggage Vision System

A production computer vision platform processing **multi-camera airport CCTV streams** for baggage and ground-equipment analytics.

The system combines:

**RTSP → DeepStream → YOLO → Tracking → Kafka → OCR → Redis → Platform APIs**

Some of the engineering challenges involved:

- Multi-camera GPU inference with NVIDIA DeepStream
- POSIX shared-memory IPC for high-throughput frame transfer
- Object re-identification when tracker IDs change after occlusion
- Domain-specific OCR parsing and character-level voting
- Redis-backed stateful session management
- Concurrent OCR processing using nested thread pools
- Multi-session processing across overlapping camera views
- Asynchronous video merging using Docker workers
- Automatic configuration generation for large camera deployments

The interesting part isn't just getting a model to work — it's making the **whole system reliable under real-world conditions**.

---

## How I Like to Engineer

I care about systems that are:

- **Simple where possible**
- **Observable**
- **Resilient to failure**
- **Efficient under load**
- **Easy to debug**
- **Designed with clear intent**

I’m particularly interested in the gap between a model that works in a notebook and a system that works **continuously in production**.

---

## Currently Exploring

- AI Agents & autonomous workflows
- Advanced Computer Vision
- ML system design
- Real-time inference optimization
- Distributed video processing
- Infrastructure & reliability
- Open-source developer tooling
- Human-centered technology

---

## Beyond Engineering

I'm also interested in **psychology, communication, language, and human behavior**.

I find the intersection between **technology and people** particularly interesting — how technical systems affect humans, and how understanding humans can lead to better technology.

> **I don't just want to build systems that work. I want to understand why they work.**
