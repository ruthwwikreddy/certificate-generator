<div align="center">

# certificate-generator

**Automated Certificate Generation for Microsoft Learn Student Ambassadors**

This project utilizes Python and Microsoft Word templates to generate certificates for participants in Microsoft Learn events. It simplifies the process of creating certificates by automating the task, saving time and effort. The output includes a Word document, PDF, and QR code.

[Source](https://github.com/ruthwwikreddy/certificate-generator) · Built by [Ruthwik Reddy](https://www.ruthwikreddy.live/)

MIT licensed · Key technical highlight: Utilizes Python-docx and docx2pdf libraries for certificate generation.

</div>

---

## Table of contents

1. [What certificate-generator does](#1-what-certificate-generator-does)
2. [Architecture](#2-architecture)
3. [Key Features](#3-key-features)
4. [Prerequisites](#4-prerequisites)
5. [Quick start](#5-quick-start)
6. [Environment variables](#6-environment-variables)
7. [Project Structure](#7-project-structure)
8. [Known Limitations](#8-known-limitations)
9. [Future Improvements](#9-future-improvements)
10. [License and credits](#10-license-and-credits)

---

## 1. What certificate-generator does

| Capability | Detail |
|---|---|
| Generates certificates | Utilizes Python-docx and docx2pdf libraries to create Word documents and PDFs |
| QR code generation | Uses a library to generate QR codes for easy scanning |
| Automated process | Simplifies the certificate generation process by automating tasks |

## 2. Architecture

```
main_certificate.py
  |
  |-- requirements.txt
  |-- Templates/
  |    |
  |    |-- Certificate Template.docx
  |    |-- Certificate Template - Copy.docx
  |    |-- Event Participants.csv
  |
  |-- Output/
  |    |
  |    |-- PDF/
  |    |    |-- Ruthwik Reddy_certificate.pdf
  |    |-- Doc/
  |    |    |-- Ruthwik Reddy_certificate.docx
  |    |-- QR/
  |    |    |-- Ruthwik Reddy_qr.png
```

## 3. Key Features
- Automated certificate generation
- QR code generation
- Simplified process

## 4. Prerequisites
- Python 3.x
- Python-docx library
- docx2pdf library

## 5. Quick start

```bash
git clone https://github.com/ruthwwikreddy/certificate-generator.git
cd certificate-generator
pip install -r requirements.txt
python main_certificate.py
```

## 6. Environment variables
None required

## 7. Project Structure
```
certificate-generator/
  |
  |-- main_certificate.py
  |-- requirements.txt
  |-- Templates/
  |    |
  |    |-- Certificate Template.docx
  |    |-- Certificate Template - Copy.docx
  |    |-- Event Participants.csv
  |
  |-- Output/
  |    |
  |    |-- PDF/
  |    |    |-- Ruthwik Reddy_certificate.pdf
  |    |-- Doc/
  |    |    |-- Ruthwik Reddy_certificate.docx
  |    |-- QR/
  |    |    |-- Ruthwik Reddy_qr.png
```

## 8. Known Limitations
- Limited customization options for templates
- QR code generation may require additional setup

## 9. Future Improvements
- Add more customization options for templates
- Improve QR code generation process

## 10. License and credits

Released under the **MIT License**.

Designed and engineered by **[Ruthwik Reddy](https://www.ruthwikreddy.live/)** · [github.com/ruthwwikreddy/certificate-generator](https://github.com/ruthwwikreddy/certificate-generator)
