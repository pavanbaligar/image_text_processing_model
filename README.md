# OCR-Based Question Paper Structuring and Enrichment

## Project Overview

This project automates the extraction, structuring, and enrichment of scanned question papers using Optical Character Recognition (OCR) and the Gemini AI API. The system processes a scanned PDF file, extracts questions, formats them, and enriches them with additional metadata and explanations.

## Features

Converts scanned PDFs to images using pdf2image.

Extracts text from images using pytesseract (Tesseract OCR).

Structures extracted text into a question-answer format.

Uses the Gemini AI API to:

Identify subjects, courses, and topics.

Verify correct answers (if available).

Generate short explanations for answers.

Saves the final structured data in a text file.
