# Semantic Book Recommendation with LLMs

This project is a semantic book recommendation system powered by large language models (LLMs), built to help users discover books based on themes, emotions, and genres. The repository includes the following key components:

data-exploration.ipynb – Handles text preprocessing and cleaning of book descriptions to ensure high-quality input for downstream tasks.

vector-search.ipynb – Implements semantic search using vector embeddings. Users can input natural language queries (e.g., "a book about a person seeking revenge") and retrieve the most similar books based on content.

text-classification.ipynb – Uses zero-shot classification with LLMs to categorize books into genres like fiction and non-fiction, enabling genre-based filtering for users.

sentiment-analysis.ipynb – Applies LLM-powered sentiment analysis (using models like Roberta) to detect emotional tones in book descriptions, allowing recommendations based on moods such as suspenseful, joyful, or sad.

gradio-dashboard.py – Powers the interactive web application built with Gradio, where users can input descriptions, select genres or emotional tones, and receive personalized book recommendations.

A requirements.txt file containing all the project dependencies is provided as part of this repo.

