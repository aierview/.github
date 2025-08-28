# AIRVIEW

**AIRVIEW** is a platform that allows simulating technical interviews using artificial intelligence. Through the platform, users can **listen to questions asked by the interviewer** (an AI) and **respond via audio**.

AIRVIEW **focuses on the user's technical content**, prioritizing the quality of technical answers rather than spelling or grammar.

---

## AIRVIEW Services

### Speech Service
##### Language: Python 3.12
The **Speech Service** is responsible for audio processing and includes two main modules:

- **TTS (Text-to-Speech)**: converts text into audio.
- **STT (Speech-to-Text)**: transcribes audio into text.

You can find the full documentation of the Speech Service at [SPEECH SERVICE DOCUMENTATION](https://github.com/aierview/speech-service).

### Interview Service
##### Language: Java 21 with Spring Boot
Responsible for **generating and evaluating interviews** using artificial intelligence.

The full documentation can be accessed at: [INTERVIEW SERVICE DOCUMENTATION](https://github.com/aierview/interview-service)

### Infra Repository
Manages the entire infrastructure, including Zookeeper, Kafka, KafDrop, and Redis.  
You can access the complete documentation for the Infra Service at: [INFRA DOCUMENTATION](https://github.com/aierview/infra)

### Front-end
Web application developed with **React** and **Next.js**.

## Project Objectives

The project was developed to:

- Enhance **microservices skills** using different languages (Java and Python).
- Work with relational databases and **Redis cache**.
- Implement **automated testing**, including unit and integration tests.
- Build a modern front-end with **Next.js and React**.

> Each module of the project contains its own README, detailing the technologies used and the functionality of each component.
