# AI Meeting Minutes Generator

An AI-powered tool that converts raw meeting audio into structured, professional meeting minutes automatically using speech recognition and NLP summarization.

---

## Description

This project uses OpenAI Whisper for speech-to-text transcription and Hugging Face Transformers for summarization to generate clean and organized Minutes of Meeting (MoM) documents from audio recordings.

The workflow includes:

* Audio transcription using Whisper
* Transcript chunking for long meetings
* AI-based summarization
* Automatic extraction of key meeting sections
* Cleaning and polishing of generated text
* Final business-style meeting minutes formatting

The system is designed to reduce manual note-taking and quickly generate readable meeting summaries.

## Features

* Converts meeting audio into text
* Summarizes long discussions automatically
* Extracts:

  * Agenda
  * Key Discussion Summary
  * Decisions
  * Action Items
* Cleans and formats outputs professionally
* Generates business-style Minutes of Meeting documents
* Handles long transcripts through chunking

---

## Tech Stack

* Python
* OpenAI Whisper
* Hugging Face Transformers
* PyTorch
* NLP Summarization

---

## Project Workflow

1. Upload meeting audio
2. Transcribe audio using Whisper
3. Split transcript into chunks
4. Summarize each chunk
5. Combine summaries
6. Extract meeting sections
7. Clean and polish text
8. Generate formatted Minutes of Meeting document

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/ai-meeting-minutes-generator.git
cd ai-meeting-minutes-generator
```

Install dependencies:

```bash
pip install torch openai-whisper transformers
```

---

## Usage

Run the notebook:

```bash
jupyter notebook
```

Open:

```bash
Untitled(1).ipynb
```

Add your meeting audio file:

```python
audio_path = "Sample_audio.mpeg"
```

Run all notebook cells.

---

## Example Output

### Meeting Minutes

**Agenda**

* Discussion about council bylaws and fine amounts

**Key Discussion Summary**

* Council reviewed and approved proposed fine structures

**Decisions**

* Council accepted the bylaw fine amounts

**Action Items**

* No action items identified

---

## Future Improvements

* Web application interface
* Real-time meeting transcription
* Speaker identification
* Export to PDF/DOCX
* Multi-language support
* Cloud deployment

---

## Folder Structure

```bash
├── Untitled(1).ipynb
├── Sample_audio.mpeg
├── Meeting_Minutes.docx
└── README.md
```

---

## Use Cases

* Business meetings
* College project meetings
* Team standups
* Council meetings
* Interview recordings
* Client discussions

---

## License

This project is open-source and available under the MIT License.

---

## GitHub Repository Short Description

AI-powered Meeting Minutes Generator using Whisper and NLP summarization to convert meeting audio into structured business-style MoM documents automatically.
