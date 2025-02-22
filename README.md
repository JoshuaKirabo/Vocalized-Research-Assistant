# Vocalized Research Assistant

Vocalized Research Assistant transforms academic papers, reports, and other PDFs into engaging podcast-style audio. Simply upload your PDF, and our AI-powered system converts it into a spoken-word format, allowing you to listen to research on the go.

## 🚀 Project Overview

- Convert PDFs into high-quality, natural-sounding audio.
- Allow researchers, students, and professionals to consume content in an auditory format.
- Provide a seamless web interface for uploading documents and retrieving podcast episodes.

## 📌 Project Features
- **PDF Upload**: Drag-and-drop or file selection for easy uploads.
- **AI-powered Text Processing**: Extracts key sections, abstracts, or entire content from PDFs.
- **Voice Synthesis**: Converts extracted text into high-quality spoken audio.
- **Downloadable Audio**: Get a podcast-style audio file for easy listening.
- **Multi-language Support** (Future): Enable text-to-speech conversion in different languages.
- **Summarization** (Future): AI-generated summaries for quicker insights.

---

## 🏗 Tech Stack
<img align="left" alt="Next.js" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" />
<img align="left" alt="FastAPI" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/fastapi/fastapi-original.svg" />
<img align="left" alt="PDF Miner" width="30px" style="padding-right:10px;" src="./GitHub_icons/pdfminer.svg" /> 
<img align="left" alt="Python FFMPEG" width="30px" style="padding-right:10px;" src="./GitHub_icons/python_ffmpeg_logo.png" /> 
<img align="left" alt="PyTorch" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" />
<img align="left" alt="BART AI" width="30px" style="padding-right:10px;" src="./GitHub_icons/Bart-logo.svg" />
<img align="left" alt="T5 Transformer" width="30px" style="padding-right:10px;" src="./GitHub_icons/T5.webp" />
<img align="left" alt="HiFi-GAN" width="30px" style="padding-right:10px;" src="./GitHub_icons/hifigan.png" />
<img align="left" alt="FastSpeech2" width="30px" style="padding-right:10px;" src="./GitHub_icons/bubble-chat.png" />
<img align="left" alt="AWS EC2" width="30px" style="padding-right:10px;" src="https://icon.icepanel.io/AWS/svg/Compute/EC2.svg" />
</br>

---
## ⚙️ How it Works
- User uploads a PDF
- PDFMiner extracts raw text (messy and unstructured)
- BART cleans & structures the text
- Fine-tuned T5 formats text into a casual podcast script
- FastSpeech2 + HiFi-GAN generate AI voice narration
- Overlay AI speech with background music using ffmpeg
- The final MP3 file is sent to the frontend

This is a work in progress. Excited to see how it evolves! 🚀

