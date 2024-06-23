# MrBeast-Words-Analyzer

## Overview

This project analyzes YouTube video captions from **MrBeast's** channel, extracting and visualizing **linguistic features**, **sentiment**, and **statistics over time**. The analysis focuses on several key aspects:

- **Total Word Count**: Measuring the total number of words spoken in MrBeast's videos.
- **Speech Rate**: Determining how fast words are spoken in terms of words per minute.
- **Sentiment Analysis**: Evaluating the positivity or negativity of the spoken words.
- **Impact on Views and Growth**: Analyzing how the way he talks affects his views and growth.

## Technologies Used

- **Python**: Primary programming language.
- **NLTK (Natural Language Toolkit)**: Text processing and sentiment analysis.
- **Matplotlib**: Data visualization and plotting.
- **JSON**: Parsing and handling data files.
- **Regular Expressions (re module)**: Text cleaning and pattern matching.
- **Collections**: Efficient data storage and counting with **defaultdict**.

## Key Features

- **Data Cleaning & Preprocessing**: Systematic parsing and cleaning of YouTube video captions.
- **Sentiment Analysis**: Analysis of emotional tone in captions using NLTK.
- **Statistical Analysis**: Calculation of words per minute, video durations, and view counts over time.
- **Exploratory Data Analysis (EDA)**: Insights and visualizations of caption data.
- **Information Retrieval**: Search for specific words, phrases, or patterns in captions.
- **Yearly Plots**: Visualizations of words per minute for videos each year, including yearly averages.
- **Lexical Analysis**: Identification and counting of unique and long words in captions.

## How to Use

1. **Requirements to download transcripts**:
   - Set up an account with **YouTube API Client**: [Quickstart Guide](https://developers.google.com/youtube/v3/quickstart/python)
   - Install **YouTubeTranscriptApi**: [YouTubeTranscriptApi on PyPI](https://pypi.org/project/youtube-transcript-api/)
   - Obtain the **client-secret.json** file.

2. **Download Transcripts**:
Open **run-download.py** and run:
   ```bash
   python run-download.py
   ```
   - This will open a website and guide you through the process to give access to the script. You may need to accept an unsafe connection warning for the script to work.
   - The script will generate a new directory with a **.json file** for every video in the channel, named by its video ID.

3. **Run the Main Project**:
   - Open the **.ipynb** file, which is the main project file.
   - Install all the imported libraries in the first code segment, and everything will work after that.

## Credits

The idea for this project came from the [**Data Time**](https://www.youtube.com/watch?v=lXeNZeLSsgY&list=LL&index=4&pp=gAQBiAQB) YouTube channel.

## License

This project is licensed under the terms of the [GNU GPLv3](LICENSE).