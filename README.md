# AI Meeting Assistant

[▶️ Open in Google Colab]([https://colab.research.google.com/drive/1mAdLf_qWpcvaaGO9HJrP2V4lg9gF47yB?usp=sharing])

## Description
An AI-powered meeting assistant that converts raw, noisy meeting transcripts into structured summaries and actionable insights using an LLM. It handles long transcripts via chunking and map-reduce summarization, with prompt decomposition for reliable extraction.

## Problem Statement
Convert raw meeting transcripts into structured summaries and actionable insights.

## Approach
- Transcript preprocessing
- Chunking + overlap for long context handling
- Prompt decomposition (summary, decisions, actions)
- Map-reduce summarization
- Schema validation with fallback

## How to Run
AI_meeting_assistant_pipeline.ipynb data/input/meeting.txt

## Output
- JSON summary
- Human-readable report
- CSV action items
