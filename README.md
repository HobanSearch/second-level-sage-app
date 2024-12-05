# Second Level Sage ($SAGE)

An AI-powered crypto market analysis assistant inspired by Howard Marks' investment philosophy.

## Overview

Second Level Sage is a sophisticated AI chatbot that helps crypto investors develop second-level thinking skills and make more informed decisions. By combining Howard Marks' investment philosophy with advanced market analysis, the platform provides deep insights beyond surface-level metrics.

## Features

- Neural Precision™ Analysis
- Contrarian Insights™
- Risk Spectrum Guidance™
- Wisdom in Action™

## Project Structure

```
second-level-sage/
├── backend/
│   ├── api/
│   │   ├── main.py
│   │   ├── routers/
│   │   └── core/
│   ├── config/
│   └── utils/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── utils/
│   └── public/
├── ai_engine/
│   ├── training/
│   │   ├── data_collection/
│   │   └── model_training/
│   └── inference/
│       ├── personality/
│       └── analysis/
├── data_pipelines/
│   ├── collectors/
│   └── processors/
└── models/
    ├── market/
    ├── risk/
    └── sentiment/
```

## Getting Started

### Prerequisites

- Python 3.9+
- Node.js 16+
- npm 8+

### Installation

1. Clone the repository
```bash
git clone https://github.com/HobanSearch/second-level-sage-app.git
cd second-level-sage-app
```

2. Install backend dependencies
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3. Install frontend dependencies
```bash
cd frontend
npm install
```

4. Set up environment variables
```bash
cp .env.example .env
# Edit .env with your configuration
```

5. Start the development servers
```bash
# Backend
python backend/api/main.py

# Frontend (in another terminal)
cd frontend
npm start
```

## Development Workflow

1. Backend Development
- FastAPI for API endpoints
- SQLAlchemy for database operations
- Alembic for database migrations

2. Frontend Development
- React for UI components
- TailwindCSS for styling
- Axios for API calls

3. AI Engine Development
- Transformers for NLP
- Custom training pipelines
- Inference optimization

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.