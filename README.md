# Real-Time Financial News Sentiment Analysis using Cerebras Inference
## Overview
This project implements a real-time Financial News Sentiment Analysis tool leveraging the powerful LLaMA 3.1 model for natural language processing. The tool scrapes financial news articles, analyzes their sentiment (positive, neutral, or negative), and visualizes the results in a dashboard. By providing instant insights into market sentiment, this tool aids investors and traders in making informed decisions quickly.

## Features
1. Real-time financial news scraping
2. Sentiment analysis using LLaMA 3.1 model
3. Visualization of sentiment distribution
4. Fast inference powered by Cerebras API
   
## How It Works
  **Data Collection:** Financial news articles are collected using external APIs such as NewsAPI or Yahoo Finance.
  **Sentiment Analysis:** The LLaMA 3.1 model, accessed through the Cerebras API, analyzes the sentiment of each article.
  **Visualization:** Results are displayed in a dashboard using matplotlib, showing sentiment distribution in a bar chart.
  
## Technology Stack
- Python
- Cerebras API
- LLaMA 3.1 model
- Matplotlib for visualization
  
## Installation
bash
git clone https://github.com/aanyabhandari3/cerebras_POC.git
cd cerebras_POC
pip install -r requirements.txt

## Cerebras Fast Inference
This project leverages Cerebras' fast inference capabilities to analyze large volumes of financial data in real-time. The ultra-fast infrastructure provided by Cerebras enables near-instantaneous sentiment analysis, crucial for responding to rapidly changing market conditions.

## Future Roadmap
- Incorporate social media sentiment analysis
- Integrate with portfolio optimization engines
- Fine-tune the LLaMA model for financial domain-specific language
- Expand dashboard features (sector-specific sentiment, historical trends)

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

### License
This project is open source and available under the MIT License.
