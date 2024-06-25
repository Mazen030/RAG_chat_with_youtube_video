# Retrieval-Augmented Generation (RAG) for YouTube Video Q&A
## Overview
This project demonstrates a simple Retrieval-Augmented Generation (RAG) application using Pinecone, OpenAI's API, and Langchain. The application allows users to ask questions about the content of any YouTube video and receive accurate and context-aware answers. By leveraging Pinecone for efficient indexing and retrieval and OpenAI for advanced natural language processing, this project showcases the power of combining these technologies for enhanced information retrieval and generation.
## Features
YouTube Video Transcription: Automatically download and transcribe the audio from a YouTube video using OpenAI's Whisper model.<br>
Chunking and Indexing: Split the transcription into manageable chunks and index them using Pinecone for efficient retrieval.<br>
Advanced Query Handling: Use Langchain to manage the retrieval process and OpenAI's GPT-3.5 model to generate detailed answers to user queries based on the video content.<br>
Seamless Integration: Demonstrates the seamless integration of multiple APIs and tools to build a powerful and scalable Q&A system.
