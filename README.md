# n8n-nodes-sign-pdf

[![NPM Version](https://img.shields.io/npm/v/n8n-nodes-sign-pdf.svg)](https://www.npmjs.com/package/n8n-nodes-sign-pdf)
[![License](https://img.shields.io/npm/l/n8n-nodes-sign-pdf.svg)](LICENSE.md)

> Add signature images or typed text signatures to PDF documents — with precise positioning and date stamps.

This is an [n8n](https://n8n.io/) community node powered by **[PDF API Hub](https://pdfapihub.com)**.

---

## 🚀 Install

1. Go to **Settings → Community Nodes** in n8n
2. Enter `n8n-nodes-sign-pdf`
3. Click **Install**

## 🔑 Setup

Sign up at [pdfapihub.com](https://pdfapihub.com) → copy your API key → add to n8n credentials.

---

## ✨ Features

### Signature Types
- **Image (URL)** — provide a URL to your signature image (PNG/JPG/WebP)
- **Image (Base64)** — provide a base64-encoded signature
- **Typed Text** — render typed text as a signature with custom color and font size

### Placement

| Parameter | Description |
|-----------|-------------|
| **Page** | Specific page number or 0 for last page (most common for contracts) |
| **Sign All Pages** | Stamp signature on every page |
| **Position** | Bottom Right (default), Bottom Left/Center, Top positions, Center, or Custom X/Y |
| **Date Stamp** | Add UTC date below the signature text |

### Output

| Parameter | Description |
|-----------|-------------|
| **Output Format** | Binary File (default), URL, or Base64 |
| **Opacity** | Signature transparency (1.0 = fully opaque) |
| **Width / Height** | Custom signature dimensions in PDF points |

> 🖊️ [Draw your signature and get a URL →](https://pdfapihub.com/free-tools/get-signature-URL)

---

## 💡 Use Cases

- **Contract signing** — automate signature placement on agreements
- **Approval workflows** — stamp manager signatures on approved documents
- **Certificate signing** — add official signatures to certificates
- **Batch signing** — sign hundreds of documents in one workflow

## License

[MIT](LICENSE.md)
