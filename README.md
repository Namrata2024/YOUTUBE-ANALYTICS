


---

# YouTube Comment Analysis

## Introduction

This project utilizes the YouTube API from Google Cloud Platform (GCP) to analyze comments on a specific YouTube video. The Python code provided connects to the YouTube API, retrieves comments for a specified video, and stores the relevant information in a Pandas DataFrame.

## Setup

### Requirements

- Google Cloud Platform (GCP) Account
- YouTube API Key

### Installation

1. Enable YouTube API in GCP.
2. Obtain a YouTube API Key from GCP.
3. Replace the placeholder in the code with your actual API key.

```python
DEVELOPER_KEY = "YOUR_YOUTUBE_API_KEY"
```

4. Execute the code in a Colab notebook or any Python environment.

## Code Overview

- `youtube_comment_analysis.ipynb`: The main Jupyter notebook containing the Python code.
- Two code snippets are provided: one for extracting comment text and another for creating a DataFrame with additional comment details.

## Usage

1. Run the Jupyter notebook in a Python environment.
2. The code will connect to the YouTube API, retrieve comments for the specified video (`videoId`), and print or store them in a Pandas DataFrame.

## Additional Notes

- The provided code is a basic example and can be extended for more advanced comment analysis.
- Ensure you follow Google's terms of service and guidelines when using the YouTube API.

## References

- [Google Cloud Platform - YouTube API](https://cloud.google.com/apis/docs/getting-started)

---

Feel free to customize the README based on your project's specific details and requirements.
