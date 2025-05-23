# YouTube Transcripts Summarizer

This Jupyter Notebook is designed to fetch transcripts from YouTube videos and summarize them using OpenAI's GPT-4o model. The primary use case is to help traders determine a directional bias from video content, providing insights into market trends and potential trading strategies.

## Features

- **Fetch Transcripts**: Automatically retrieves transcripts from YouTube videos using the `youtube-transcript-api`.
- **Summarization**: Utilizes OpenAI's GPT-4o to summarize the transcript, highlighting key points and potential market implications.
- **Directional Bias Analysis**: Analyzes the content to determine the speaker's directional bias and provides a deeper understanding of the underlying message.

## Requirements

- Python 3.11 or later
- Jupyter Notebook
- Required Python packages:
  - `youtube-transcript-api`
  - `openai`
  - `pyonepassword`

## Setup

1. **Install Python Packages**: Run the following command in a Jupyter Notebook cell to install the necessary packages:
   ```python
   %pip install youtube-transcript-api openai pyonepassword
   ```

2. **OpenAI API Key**: Ensure you have access to an OpenAI API key. This key should be securely stored and accessed using `pyonepassword`. You can remove this and hardcode your key or add it some other way.

3. **YouTube Video ID**: Update the `video_id` variable in the notebook with the ID of the YouTube video you wish to summarize.

## Usage

1. **Run the Notebook**: Execute the cells in the notebook sequentially. The notebook will fetch the transcript, summarize it, and provide an analysis of the directional bias.

2. **Review the Output**: The summarized content and analysis will be displayed in the notebook's output cells.

## Example

The notebook includes an example using a specific YouTube video ID. You can replace this ID with any other video ID to analyze different content.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs or feature requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.