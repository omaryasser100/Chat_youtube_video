# Chat with YouTube

An interactive AI application that allows users to chat with any YouTube video using its transcript.  
This notebook extracts the transcript from a YouTube video, summarizes its content, and answers user questions with the help of a Large Language Model (LLM) through LangChain and OpenAI.

## Project Overview

This project demonstrates a simple Retrieval-Augmented Generation (RAG)-style workflow applied to YouTube content.  
It uses the **YouTube Transcript API** to fetch the video transcript, then uses **LangChain** and **OpenAI GPT models** to generate accurate and context-aware responses to user queries.  
A **Gradio interface** provides a user-friendly web app where users can input a YouTube video URL and their question, receiving AI-generated answers in real time.

## Features

- Fetches the transcript from any public YouTube video using its URL  
- Uses a prompt-based LLM (via LangChain) for concise, factual answers  
- Works as a lightweight RAG chatbot over video transcripts  
- Provides a simple, intuitive **Gradio** web interface  
- Supports deployment on Hugging Face Spaces or Colab  

## Requirements

Install the dependencies with:

```bash
pip install -qU langchain-core langchain-openai langchain_huggingface langchain-community langsmith
pip install youtube-transcript-api gradio
