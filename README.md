# FORKCAST 🍳🤖  
AI-Powered Recipe Generator from Fridge Photos

## Overview
FORKCAST is a multimodal Generative AI application that generates personalized recipes
from images of ingredients available in a user’s fridge.

The system integrates computer vision and large language models to automate
recipe creation in a real-world consumer use case.

## Tech Stack
- Python
- YOLOv8 (Computer Vision)
- GPT-3.5 (Large Language Model)
- Streamlit
- HTML, CSS

## How It Works
1. User uploads a fridge image
2. YOLOv8 detects ingredients from the image
3. Detected ingredients are passed to GPT-3.5 using prompt engineering
4. AI generates a structured recipe with steps

## Live Demo
👉 https://twinkleigdtuw.github.io/FORKCAST_/

## My Contribution
- Integrated GPT-3.5 API into the backend
- Designed prompt templates for recipe relevance
- Implemented error handling for missing/invalid inputs
- Performed system testing and debugging

## Future Improvements
- Voice-based ingredient input
- Nutrition-aware recipe ranking
- Mobile app deployment
