# Website Reconnaissance Tool

An automated website reconnaissance tool powered by AutoGen that combines multiple scanning techniques to gather information about web applications.

## Features

- Technology Stack Detection
- Port Scanning
- Subdomain Enumeration
- Content Discovery
- Automated Report Generation

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd reconnaissance-autogen
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# OR
venv\Scripts\activate     # Windows
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Basic usage:
```bash
python src/main.py example.com
```

With custom output directory:
```bash
python src/main.py example.com --output custom_outputs
```

## Project Structure

```
recon_auto/
├── src/
│   ├── agents/                 # AutoGen Agents
│   ├── core/                   # Core functionality
│   └── tools/                  # Reconnaissance Tools
├── data/
│   ├── wordlists/             # Wordlists for content discovery
│   └── signatures/            # Technology signatures
└── outputs/
    ├── scans/                 # Raw scan results
    └── reports/               # Processed reports
```

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. #   r e c o n n a i s s a n c e - a u t o g e n  
 