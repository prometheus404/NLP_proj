# Boardgames Are Made Of Rules
## Project Overview
This project evaluates how well different large language models (LLMs) process, analyze, and extract information from board-game rule texts. By testing models on real board games from the BoardGameGeek Hall of Fame, we assess their ability to interpret formal logic and adapt complex information to different contexts.
## Objectives
The primary objectives of this project are to:
- **Evaluate explanation generation**: Test LLMs' ability to extract fundamental game concepts and adapt them for different audiences (ages 7, 11, and 16)
- **Assess error detection**: Determine how well models can identify missing or contradictory information in rule texts
- **Estimate game properties**: Compare model predictions of game complexity, optimal player count, mechanics, and duration against BoardGameGeek data

## Models Tested
This study compares three open-source LLMs:
- **LLaMA**
-  **Gemma**
-  **Qwen**

## Dataset
Rules from 5 board games (subset of BoardGameGeek Hall of Fame):
- 7 Wonders
- Catan
- Dominion
- Power Grid
- Ticket to Ride

## Methodology
### Explanation Task
Models generate age-appropriate explanations evaluated on readability (SMOG, Flesch-Kincaid, Dale-Chall), completeness (rule coverage), and conciseness (compression ratio).
### Error Detection Task
Models identify intentional flaws in rule texts across 5 difficulty levels: original, missing rules, contradictions, incoherent combinations, and game-breaking mechanics.
### Parameter Estimation Task
Models estimate game mechanics, complexity, optimal player count, and duration, with results validated against BoardGameGeek data.
## Key Findings
- Models show strong performance in rule extraction and player count estimation
- Error detection capabilities are limited, especially for subtle inconsistencies
- Smaller model size is a significant constraint for complex logical reasoning
- Duration estimation remains unreliable across all tested models

----

# AI usage disclaimer
Parts of this project have been developed with the assistance of OpenAI's ChatGPT (GPT-oss). 
AI was used to summarize ideas, generate code for some visualization (marked with a comment), rephrasing, help restructure data for the report tables and generate this README. All content produced with AI assistance has been carefully reviewed, edited, and validated by me. I take full responsibility for the final content and its accuracy.
