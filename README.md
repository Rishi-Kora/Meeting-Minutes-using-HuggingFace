# Meeting-Minutes-using-HuggingFace
Generate professional meeting minutes from audio recordings using state-of-the-art models from [Hugging Face Transformers](https://huggingface.co/).

## Project Overview

This project uses a real-world example (Denver City Council meeting) to demonstrate how to transcribe and summarize audio into concise meeting minutes. It combines speech-to-text and natural language summarization using Hugging Face models.

## Folder Structure

```bash

├── meeting_minutes_product_using_HF.ipynb  
├── README.md                               
                                 
```

## Setup Instructions

To run this notebook in Google Colab:

1. Upload your `.wav` audio file to Colab or reference a file in `/kaggle/input/` or Google Drive.
2. Install the required packages using pip (already included in the notebook).
3. Run all cells to generate transcriptions and meeting summaries.

```bash
!pip install -q requests torch bitsandbytes transformers sentencepiece accelerate openai httpx==0.27.2
```

## Key Features

- Audio transcription using Whisper or similar speech-to-text models
- Summarization using transformer-based models
- Generates clean, readable meeting minutes

## Tech Stack

- Python
- Hugging Face Transformers
- Torch / Accelerate
- SentencePiece
- OpenAI / HTTPX for API integration

## Workflow Diagram

<img width="767" height="645" alt="image" src="https://github.com/user-attachments/assets/76166d62-6e67-4a8e-88be-b0702de55c83" />


## Example Use Cases

- Internal meeting documentation
- Public governance meetings
- Academic discussions or research meetings

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Hugging Face](https://huggingface.co/) for pre-trained models
