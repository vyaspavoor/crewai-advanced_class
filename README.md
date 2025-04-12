# CrewAI Advance Functionalites

A comprehensive AI agent system built using CrewAI framework, featuring multimodal capabilities, memory integration, and various knowledge sources.

## Features

- **Multimodal Agents**: Support for both text and image analysis using GPT-4 and Gemini models
- **Memory Integration**: Long-term memory capabilities using mem0
- **Knowledge Sources**: Multiple knowledge source types supported:
  - String-based
  - Text files
  - PDF documents
  - CSV files
  - JSON files
  - Custom knowledge sources (e.g., Weather API)

- **Human-in-the-Loop**: Tasks with human validation and feedback

## Prerequisites

- Python 3.11+
- API keys for:
  - OpenAI (GPT-4)
  - Google Gemini
  - Serper
  - mem0

## Installation

1. Clone the repository
2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Copy `.env.example` to `.env` and fill in your API keys:
```bash
cp .env.example .env
```

## Project Structure

```
├── crewai_advanced.ipynb    # Advanced CrewAI implementations
├── knowledge.ipynb          # Crewai Knowledge source implementations
├── memory.ipynb            # Crewai Memory system implementations
├── multimodal-*.py         # Crewai Multimodal agent implementations
├── memtest.py              # Mem0 simple test
├── knowledge/
│   └── company_info.json   # Sample knowledge data
```


## Environment Variables

Required environment variables in `.env`:
- `GEMINI_API_KEY`
- `OPENAI_API_KEY`
- `SERPER_API_KEY`
- `MEM0_API_KEY`

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request
