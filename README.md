# Moderator

## Overview
This is an implementation of parallel workflow in langgraph. I have created an **AI - automated Moderation & Brand Safety pipeline** , using 
- Langgraph
- groq

## Premise
Instead of processing an input text sequentially. It takes any raw piece of text whether its an video script , a blog draft or a user comment and broadcasts it to three specialised AI agents running simultaneously in parallel.

- Each agent evaluates the text from completely different perspective.
- Each agent scores the content in scale from 0 to 100.

## Agents
The three agents are:

- **The Toxicity Monitor** : Scan the text for aggressive language , profanity or hate speech.
- **The Copyright Cop** : Analyse the text for plagiarism, trademark violations or unoriginal copyrisks.
- **The Cultural Guide**: Flags regional sensitivities or political landmine that could offend a global audience.

*Disclaimer : These names are generated using AI.*

- *This is a minor project made only for pratice*


*Adios Amigo, Dhruv Signing off.*
