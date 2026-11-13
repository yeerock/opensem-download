# AiSEM - AI Native Structural Equation Modeling Software

AiSEM is free AI native desktop software for **CB-SEM** (covariance-based structural equation modeling) and **PLS-SEM** (partial least squares SEM). Free to download and use, including for business. AiSEM was called OpenSEM up to version 0.6.

- **AI Copilot:** Autopilot drafts the model from your columns, chooses the methods, runs the analysis, reviews the results against published guidelines, improves the model and writes up the findings. AiSEM's own engine checks every AI suggestion and computes every number; numbers in AI-written text are matched against the report.
- **Your AI, your key:** OpenAI (ChatGPT), Anthropic (Claude), Google Gemini, DeepSeek, Kimi, GLM, Grok, Meta Muse, Alibaba Qwen, Mistral, Groq, OpenRouter or any OpenAI-compatible service, or free private models on your computer with Ollama or LM Studio. Keys stay on your computer.
- **Complete:** CB-SEM (ML, robust ML, FIML, GLS, ULS, ADF, WLSMV), PLS-SEM and PLSc, Bayesian SEM, two-level SEM, latent class and profile analysis, FIMIX-PLS, necessary condition analysis, PLSpredict, multigroup analysis and MICOM, IPMA, mediation and Monte Carlo power
- **Backed by research:** every method and threshold cites its published source, and the report includes a methods paragraph and reference list
- **Fast:** uses every CPU core
- **Private:** the statistics run on your computer; the AI only sees what you choose to share

Website: https://www.vyrox.com/aisem

## Download

Get the latest version for Windows, macOS or Linux from **[Releases](https://github.com/yeerock/aisem-download/releases)**. Each file has a `.sha256` checksum.

## Quick Start

Double-click `aisem` (or run it in a terminal) and the app opens in your browser. Open AI Copilot to connect an AI model.

```bash
aisem
aisem demo
aisem analyze --data mydata.csv --model mymodel.txt
```

Model syntax:

```text
Trust   =~ T1 + T2 + T3      # reflective construct
Image   <~ I1 + I2           # formative construct
Loyalty =~ L1 + L2
Loyalty ~  Trust + Image     # structural paths
```

## Licence

Free for personal, academic and business use. You may share the unmodified download free of charge. No resale, modification or reverse engineering. See [LICENSE](LICENSE).

The source code is not public. This repository only hosts the downloads.
