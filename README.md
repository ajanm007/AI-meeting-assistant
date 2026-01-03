# AI Meeting Assistant

[▶️ Open in Google Colab]([https://colab.research.google.com/...](https://colab.research.google.com/drive/1mAdLf_qWpcvaaGO9HJrP2V4lg9gF47yB?usp=sharing))

## Description
<description text>

## Problem Statement
Convert raw meeting transcripts into structured summaries and actionable insights.

## Approach
- Transcript preprocessing
- Chunking + overlap for long context handling
- Prompt decomposition (summary, decisions, actions)
- Map-reduce summarization
- Schema validation with fallback

## How to Run
python process_meeting.py data/input/meeting.txt

## Output
- JSON summary
- Human-readable report
- CSV action items
