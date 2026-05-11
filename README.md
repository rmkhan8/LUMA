# LUMA - PDF Knowledge Base

A repository for storing and managing PDF files for access by Copilot agents.

## Directory Structure

- **`/pdfs/`** - Contains all PDF files
- **`/pdf-metadata/`** - Contains metadata JSON files describing each PDF
- **`/docs/`** - Documentation and guides

## Quick Start

1. Add your PDF files to the `/pdfs/` directory
2. Create corresponding metadata files in `/pdf-metadata/`
3. Update the `pdf-index.json` to register new documents

For detailed instructions, see [PDF_MANAGEMENT.md](./docs/PDF_MANAGEMENT.md)

## Usage by Copilot Agent

The Copilot agent can access PDFs through:
- Direct file retrieval via GitHub API
- Metadata-driven queries using `pdf-index.json`
- Context loading from PDF metadata files
