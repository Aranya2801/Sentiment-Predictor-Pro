# Contributing to Sentiment Predictor Pro

## Setup
```bash
git clone https://github.com/yourusername/sentiment-predictor-pro.git
cd sentiment-predictor-pro
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt && pip install -e .
```

## Branch Strategy
| Branch | Purpose |
|--------|---------|
| `main` | Stable production code |
| `develop` | Active development |
| `feature/name` | New features |
| `fix/issue` | Bug fixes |

## Running Tests
```bash
python tests/test_all.py        # Quick (no pytest needed)
pytest tests/ -v --cov=src      # With coverage
```

## Priority Areas
- New language support (currently 8 languages)
- Model fine-tuning scripts
- UI components
- Voice/audio pipeline improvements
- Real data collector integrations

## Commit Convention
```
feat: add Japanese sentiment support
fix: ABSA context window boundary error
docs: update API reference for /analyze/full
test: add sarcasm edge cases
```
