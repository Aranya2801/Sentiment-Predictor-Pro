# Changelog

## [1.0.0] — 2026-06-14

### Added
- Ensemble sentiment analysis (BERT + RoBERTa + DeBERTa + DistilBERT + FinBERT)
- 8-emotion detection (GoEmotions inspired: joy, sadness, anger, fear, surprise, love, disgust, neutral)
- Aspect-Based Sentiment Analysis (ABSA) — SemEval-2016 inspired
- Sarcasm detection with template + incongruity analysis
- 6-class toxicity classifier (Jigsaw/Perspective API methodology)
- Fake review detector (genuine/suspicious/AI-generated)
- 8-language multilingual support (EN/HI/BN/ES/FR/DE/AR/JA)
- Sentiment forecasting (Prophet + LSTM + TFT ensemble)
- Explainable AI (SHAP + LIME token attributions)
- FastAPI backend with WebSocket streaming
- Personal sentiment journal
- 73 unit + integration tests (all passing)
- Docker + docker-compose full stack
- GitHub Actions CI/CD pipeline

### Research References
- BERT (Devlin et al., 2019), RoBERTa (Liu et al., 2019), DeBERTa (He et al., 2021)
- GoEmotions (Demszky et al., 2020), ABSA SemEval-2016, SHAP (Lundberg & Lee, 2017)
- TFT (Lim et al., 2021), Prophet (Taylor & Letham, 2018)
