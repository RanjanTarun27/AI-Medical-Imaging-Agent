# AI-Medical-Imaging-Agent
# 🏥 Medical Imaging Diagnosis Agent

This is a **web-based AI tool** that provides **professional analysis of medical images** using Google's Gemini AI model. The agent can analyze images (X-ray, MRI, CT, Ultrasound) and provide structured diagnostic insights, key findings, patient-friendly explanations, and references from online research.  

⚠ **Disclaimer:** This tool is for educational and informational purposes only. All analyses should be reviewed by qualified healthcare professionals. Do not make medical decisions based solely on this analysis.

---

## Features

- Upload medical images in **JPG, JPEG, PNG, or DICOM** format.
- AI-powered **multi-modal analysis** combining images and text prompts.
- Structured report including:
  1. Image type & region
  2. Key findings
  3. Diagnostic assessment
  4. Patient-friendly explanation
  5. Research references
- Integration with **DuckDuckGo search** for recent literature and treatment protocols.
- Streamlit-based interactive **web interface**.

---

How it Works

Image preprocessing

Resizes images to fit the interface while keeping the aspect ratio.

Agent creation

Uses agno.Agent with Gemini as the LLM and DuckDuckGoTools for research references.

Multi-modal analysis

The agent processes both the uploaded image and structured prompt to produce a diagnostic report.

Display results

Streamlit shows a Markdown-formatted report with headings, bullet points, and disclaimers.

Supported Image Formats

.jpg, .jpeg, .png, .dicom

Note: DICOM files may require additional preprocessing for pixel array extraction.

Technologies Used

Python 3.10+

Streamlit – interactive web app

Pillow (PIL) – image processing

Agno AI Library – agent framework and multi-modal AI

Google Gemini – AI model

DuckDuckGoTools – web search integration
