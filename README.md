# Youtube_Success_Analyzer
"Unleash the Secrets of YouTube Success: Analyzing Top YouTubers' Data to Uncover the Key Factors Driving Subscribers and Views."

![image](https://github.com/arrytiwari/Youtube_Success_Analyzer/assets/91563115/86bcde88-6e33-4cab-aeb1-2ac3df7f6348)


## Overview
The YouTube Success Analyzer is a data analysis project that utilizes the YouTube API v3 to gather data from the top 10 most favorite YouTubers. The project aims to analyze various elements such as views, likes, comments, the number of videos, and other metrics to gain insights into the factors that contribute to higher subscriber counts and views. By examining the data, this project seeks to uncover patterns and correlations to understand what drives YouTube success.

## Features
- Retrieve data from the YouTube API v3 for the top 10 favorite YouTubers.
- Compare metrics such as views, likes, comments, and the number of videos across channels.
- Analyze the relationship between metrics and subscriber/view counts.
- Identify the month(s) with the highest video uploads and investigate seasonal trends.
- Determine the most viewed videos from each channel and analyze their characteristics.

## Prerequisites
To use the YouTube Success Analyzer, make sure you have the following prerequisites:

1. YouTube API v3 Key: Obtain a YouTube API v3 key from the Google Cloud Console.

2. Python Environment: Set up a Python environment with the necessary libraries. You can use virtual environments like Anaconda or create a virtual environment using `venv`.

3. Dependencies: Install the required Python libraries listed in the `requirements.txt` file.

## Installation
Follow these steps to install and set up the YouTube Success Analyzer:

1. Clone the repository:git clone https://github.com/your-username/YouTubeSuccessAnalyzer.git

css
Copy code

2. Navigate to the project directory:
cd YouTubeSuccessAnalyzer

markdown
Copy code

3. Install the dependencies:
pip install -r requirements.txt

markdown
Copy code

4. Configure API Key:
- Open the `config.py` file.
- Replace `'YOUR_API_KEY'` with your YouTube API v3 key.

5. Run the analyzer:
python analyzer.py

css
Copy code

## Usage
Once the analyzer is running, it will retrieve data from the YouTube API for the top 10 favorite YouTubers. The analysis results will be displayed in the console and saved to a CSV file for further exploration.

## Customization
Feel free to customize the YouTube Success Analyzer according to your needs. You can modify the metrics analyzed, expand the analysis to more channels, or incorporate additional data visualizations.

## Acknowledgements
- The YouTube Success Analyzer is an ongoing personal project by Aryan Tiwari.
