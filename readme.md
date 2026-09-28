# MediGrid AI – AI-Powered Prescription Assistant

MediGrid AI is a Generative AI application that analyzes prescription images and converts handwritten prescription information into structured digital data.

The application uses AI to extract patient and medication information, provide contextual safety warnings, generate pharmacy map links, and save prescription records for future reference.

## Features

- Prescription image analysis
- AI-based handwritten prescription extraction
- Patient information extraction
- Medicine, dosage, frequency and duration extraction
- Contextual critical warnings
- Nearby pharmacy map links
- Prescription history using SQLite
- Downloadable analysis report
- AI assistant
- Browser-based location detection
- FastAPI backend

## Application Workflow

```text
Prescription Image
        ↓
FastAPI Backend
        ↓
Gemini AI
        ↓
Prescription Data Extraction
        ↓
┌──────────────────────┐
│ Extracted Data       │
│ Critical Warnings    │
│ Pharmacy Map Links   │
└──────────────────────┘
        ↓
SQLite Database
        ↓
Prescription History