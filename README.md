# BridgeAI

## What I Built

BridgeAI is an AI-powered website audit platform that evaluates websites for AI discoverability and agent readiness. The platform audits websites across multiple pillars including Agent Experience, API Readiness, Semantic Structure, Automation Readiness, and Generative Engine Optimization.

Tech Stack: FastAPI, PostgreSQL, Redis, Celery, Gemini, AWS

## One Ambiguity

Whether recommendations should be generated entirely through deterministic rules or enhanced using LLMs.

## One Trade-off

Using Celery and Redis increased system complexity but enabled scalable background processing and prevented long-running audit requests from blocking users.

## One Mistake

Initially relying too heavily on LLM-generated outputs. This led to inconsistencies and was later solved with validation layers and fallback mechanisms.

## One Review Comment That Changed My Mind

A teammate pointed out that prompt engineering should not replace application-level validation and business logic. Since then I use LLMs as an enhancement layer rather than the source of truth.

## Link

BridgeAI Website: https://buildbridges.co/
Portfolio: https://ayush-portfolio-one-flame.vercel.app/
LinkedIn: https://www.linkedin.com/in/michael-ayush-237461202/
