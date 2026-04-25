# TaskMind AI – Autonomous AI Agent System

## Overview
TaskMind AI is an autonomous agent system designed to execute real-world tasks by integrating external APIs using structured tool-calling and multi-step reasoning.

## Features
- Multi-step reasoning pipeline for task decomposition
- Tool calling (weather, email, scheduling APIs)
- Context-aware memory using Redis
- FastAPI backend for scalable API interaction
- Modular agent architecture
- Extensible tool system

## Tech Stack
Python, FastAPI, Redis, OpenAI/Gemini APIs, REST APIs

## Architecture
User Input → Task Decomposition → Tool Selection → API Execution → Memory Update → Response

## Future Enhancements
- Voice interaction using Whisper
- Multi-agent collaboration
- Real-time monitoring dashboard
